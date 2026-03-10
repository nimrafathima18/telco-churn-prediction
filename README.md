# Customer Churn Prediction

## Project Overview
Customer churn prediction is an important problem for businesses, especially in industries such as telecommunications, banking, and subscription-based services. Churn occurs when customers stop using a company's service.

The goal of this project is to build a machine learning model that predicts whether a customer is likely to churn based on their service usage, account information, and demographics.

By predicting churn early, companies can take proactive steps to retain customers and improve customer satisfaction.

---

## Dataset
The dataset used in this project is the Telco Customer Churn Dataset, which contains information about customers and their service usage.

Important features include:

- CustomerID – Unique customer identifier  
- Gender – Gender of the customer  
- SeniorCitizen – Whether the customer is a senior citizen  
- Tenure – Number of months the customer has stayed with the company  
- MonthlyCharges – Monthly amount charged to the customer  
- TotalCharges – Total amount charged to the customer  
- Contract – Type of contract (Month-to-month, One year, Two year)  
- InternetService – Type of internet service used  
- Churn – Target variable indicating whether the customer left the service  

---

## Data Preprocessing
Before building the machine learning model, the dataset was cleaned and prepared.

The preprocessing steps included:

- Handling missing values  
- Converting categorical variables into numerical form using encoding techniques  
- Feature scaling for numerical variables  
- Separating features and target variable  
- Splitting the dataset into training and testing sets

These steps help improve model performance and ensure reliable predictions.

---

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to understand patterns and relationships in the data.

Some analyses included:

- Distribution of churned vs non-churned customers  
- Relationship between tenure and churn  
- Impact of contract type on churn  
- Effect of monthly charges on churn  

Visualizations used:

- Count plots  
- Histograms  
- Correlation heatmaps  
- Bar charts

---

## Machine Learning Models
Different classification models can be applied to predict customer churn.

Typical models include:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine  

These models help identify patterns in customer behavior and predict whether a customer is likely to leave the service.

---

## Model Evaluation
Model performance is evaluated using classification metrics such as:

- Accuracy – Percentage of correctly predicted instances  
- Precision – Correct positive predictions  
- Recall – Ability to detect churned customers  
- F1 Score – Balance between precision and recall  
- Confusion Matrix – Visualization of prediction results

These metrics help determine how well the model predicts churn.

---

## Business Impact
Predicting customer churn provides several benefits:

- Identifying customers at risk of leaving  
- Improving customer retention strategies  
- Designing targeted marketing campaigns  
- Increasing long-term revenue

Businesses can use churn predictions to offer discounts, improve service quality, or personalize customer experiences.

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. Prediction and Insights  

---

## Conclusion
Customer churn prediction helps businesses proactively identify customers who may stop using their services. Using machine learning techniques, companies can analyze customer behavior patterns and take preventive actions to reduce churn and improve customer retention.

---

## Author
Fathima
