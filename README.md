# Amna-Kauser-TASK---4-Data-Science-and-Analytics-
Data Science and Analytics Internship Tasks
## Task 4: Predicting Insurance Claim Amounts

### Objective
Estimate medical insurance claim amounts based on 
personal data such as age, BMI, and smoking status.

### Approach
- Loaded the Insurance dataset
- Encoded categorical columns (sex, smoker, region)
- Trained a Linear Regression model (80% train, 20% test)
- Visualized impact of BMI, Age, and Smoking on charges
- Evaluated model using MAE, RMSE, and R² score

### Results and Insights
- R² Score: 0.78 — model explains 78% of variation in charges
- MAE: $4,187 — predictions are off by $4,187 on average
- RMSE: $5,800
- Smoking is the biggest factor — smokers pay 3-4x more 
  than non-smokers ($20,000-$40,000 vs $5,000-$10,000)
- Charges increase with both age and BMI especially for smokers
