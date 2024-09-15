
# Lead Scoring Case Study

The objective is to build a logistic regression model that assigns a lead score (between 0 and 100) to each lead, helping the company identify potential leads. A higher score indicates a "hot" lead that is more likely to convert, while a lower score represents a "cold" lead with a lower likelihood of conversion.

### 1. Read Data
- Import necessary libraries.
- Load the leads data into a dataframe.
- Conduct a quick review of the dataframe.
- Check the shape of the leads dataframe.
- Assess the overall conversion rate.

### 2. Analyze and Prepare Data
- Check for missing values.
- Analyze the levels of categorical columns.
- Identify columns with default "Select" values.
- Re-examine missing values in the dataframe.
- Separate categorical columns with missing data.
- Identify quantitative columns with missing values.
- Calculate and recheck the percentage of missing values.
- Review the distribution of quantitative variables.
- Impute missing values for quantitative columns.
- Drop columns with more than 70% missing data.
- Impute missing values for categorical columns with fewer missing values.
- Update lists of numerical and categorical columns after dropping irrelevant columns.
- Use boxplots to analyze quantitative variables.
- Perform bivariate analysis.
- Conduct an outlier analysis.
- Create dummy variables for categorical columns.
- Apply label encoding for high-cardinality categorical columns.
- Drop columns with no variance.
- Check for correlations between variables.

### 3. Data Preparation for Modeling
- Split the dataset into training and testing sets.
- Apply feature scaling to ensure consistency.

### 4. Model Building
- Create a function to streamline model building.
- Apply feature scaling to the dataset.
- Use Recursive Feature Elimination (RFE) for feature selection.
- Build the logistic regression model using selected features.
- Make predictions with the model.
- Generate and interpret a confusion matrix.
- Plot the ROC curve to evaluate model performance.
- Determine the optimal cutoff value based on accuracy, sensitivity, and specificity.
- Plot the accuracy, sensitivity, and specificity curves.
- Create a precision-recall plot.

### 5. Make Predictions on the Test Set

### 6. Principal Component Analysis (PCA)
- Extract principal components from the dataset using PCA.

### 7. Logistic Regression on PCA
- Perform logistic regression using the principal components.

### 8. Model Conclusion
- Merge predictions from the training and test sets.
- Combine the predictions with the original dataframe.
- Create a new "Lead Score" column to reflect each lead's probability of conversion.
- Generate a dataframe showing the relationship between different cutoff values and conversion percentages.
