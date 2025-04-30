# Customer-Churn-Prediction

📊 Customer Churn Prediction in Telecom Industry
A machine learning-based predictive analytics project designed to identify customers at risk of leaving a telecom service. This solution leverages customer demographic, service usage, and feedback data, applying both predictive modeling and natural language processing (NLP) techniques to uncover patterns and forecast churn with actionable insights for customer retention.

📖 Overview
Customer churn is a major challenge for telecom companies, directly affecting profitability and operational costs. This project addresses the issue by developing a predictive model capable of identifying high-risk customers and uncovering the key reasons behind churn behavior using structured data and text-based feedback.

🎯 Objectives
Analyze factors contributing to customer churn in the telecom industry.

Preprocess, clean, and visualize telecom churn data for model building.

Apply NLP on textual churn reasons to extract meaningful patterns.

Build and evaluate a Multilayer Perceptron (MLP) model for churn prediction.

Derive actionable insights to help reduce churn and enhance retention strategies.

Assess the predictive model's accuracy and performance.

🔍 Approach
Data Preprocessing: Handled missing values, encoded categorical data, and performed exploratory data analysis (EDA) to uncover demographic and behavioral patterns.

Feature Engineering: Analyzed attributes like marital status, multiple line subscriptions, age groups, and churn reasons.

Natural Language Processing (NLP):

Removed stopwords and pronouns from churn reason texts using NLTK.

Calculated Term Frequency (TF), Document Frequency (DF), and Inverse Document Frequency (IDF).

Applied TF-IDF weighting to identify the most impactful reasons for churn.

Top churn reason identified: “Competitor offered higher download speeds.”

Model Building:

Developed a Multilayer Perceptron (MLP) neural network classifier with two hidden layers and logistic activation.

Trained on labeled customer data to predict three customer statuses: Stayed, Joined, and Churned.

📊 Model Performance

Metric	Value
Accuracy	84%
Prediction Classes	Stayed, Joined, Churned
NLP Result	Identified top churn reasons by TF-IDF score
The model was validated using test data and successfully predicted customer churn status with a high degree of accuracy.

Prediction tests with new inputs showed reliable class assignments.

📈 Key Insights
Marital Status: Unmarried customers churn more frequently.

Multiple Lines: Customers using multiple lines are more likely to stay.

Age Factor: Customers aged 41+ showed the highest churn rates.

Churn Reason Analysis: Speed offered by competitors was the most common reason for churn.

🛠️ Technologies Used
Python 3

Pandas

NumPy

Scikit-learn

NLTK

Matplotlib / Seaborn

Multilayer Perceptron (MLP) from sklearn.neural_network

📦 Dataset
A telecom industry dataset containing customer demographic details, service plan data, service usage statistics, and churn reasons [LINK](https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics/data?select=telecom_customer_churn.csv)

📌 Conclusion
The project effectively demonstrates how predictive analytics combined with NLP techniques can empower telecom companies to reduce churn rates. By understanding demographic trends, service usage patterns, and customer feedback, telecom providers can create targeted retention strategies to improve customer satisfaction and business profitability.
