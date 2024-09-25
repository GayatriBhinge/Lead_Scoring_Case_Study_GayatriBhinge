# Lead-Scoring-Case-Study
## Objective
For building the logistic regression model to predict lead conversion for X Education, follow these steps to ensure the model is robust and adaptable to future requirements:

## Step-by-Step Approach:
### 1] Data Understanding & Preprocessing:

- Start by collecting all the data related to leads, including their browsing behavior, form fills, referrals, etc.
- Clean the data by handling missing values, outliers, and encoding categorical variables (e.g., gender, source of the lead, etc.).
- Ensure all features are in the correct format (numeric vs. categorical) and handle any imbalance in the dataset if conversion rates are skewed.

### 2] Feature Engineering:

- Create new features based on the data, such as: <br>
  --- Time spent on the website<br>
  --- Number of courses browsed<br>
  --- Source of the lead (Google, referral, etc.)<br>
  --- Lead form completion percentage<br>
  --- Email interaction metrics (opens, clicks)<br>
- Consider normalizing or standardizing numerical features to improve the model's performance.

### 3] Feature Engineering:

- Model Building: <br>
   - Use Logistic Regression as the primary model:<br>
   --- Train the model on a subset of your data, using a portion for validation.<br>
   --- The logistic regression model will output probabilities between 0 and 1. Multiply these by 100 to assign lead scores between 0 and 100.<br>


### 4] Model Evaluation:

- Evaluate the model using performance metrics like:<br>
  --- Accuracy<br>
  --- ROC-AUC Score<br>
  --- Precision & Recall<br>
  --- F1-Score<br>
- Perform cross-validation to ensure the model generalizes well to unseen data.<br>
- Consider using threshold tuning to optimize the probability cutoff that defines a "hot lead."


### 5] Handling Future Requirements:

- To adjust for future changes, implement a modular approach where new features can be added easily.
- Regularly retrain the model as more lead data comes in, to account for changes in lead behavior or marketing strategies.
- Monitor performance over time to ensure it continues to deliver accurate lead scores.

### 6] Documenting in PPT:

- Clearly explain the problem statement and approach in the PPT.
- Include visualizations of the model performance (confusion matrix, ROC curve).
- Summarize the business impact: by focusing on hot leads, the sales team can improve their efficiency and the conversion rate.
- Provide actionable recommendations based on the model results.



## Details of files given
- Lead Score Case Study Aayushi Meenu .ipynb : The python file showing coding and data analysis
- Assignment Subjective Questions.pdf : Some subjective questions answered
- Lead Score Case Study.pdf : Final Presentation
- Leads.csv : Data worked on
- Leads Data Dictionary.xlsx : Data Dictionary
- Summary.pdf : Summary on what's done in the entire py file

