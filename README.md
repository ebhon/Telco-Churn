# Data Kingdom: Customer Churn Prediction

Welcome to **Data Kingdom: Customer Churn Prediction**, a deep-dive into understanding customer behavior, retention, and churn in a fantasy world inspired by Mario’s journey through the kingdom. In this project, we analyze various factors like financial aspects, customer contracts, support services, and demographics to predict churn behavior and identify key drivers that influence customers to leave or stay.

## 🌟 Project Overview

In this whimsical, yet insightful, project, Mario embarks on an adventurous exploration through the Data Kingdom. Along the way, he encounters challenges, hidden insights, and valuable data that reveal the true nature of customer behavior. Through analyzing different features, such as Monthly Charges, Tenure, Contract Types, and Tech Support, the project aims to:

- Decode the patterns behind customer churn.
- Offer insights on how pricing, contract types, and customer support impact retention.
- Propose strategies to reduce churn by targeting key areas like Mid-range Payers, Single Explorers, and TechSupport.

## 🚀 Key Objectives

- **Customer Churn Exploration:** Understand the factors that influence customers’ decisions to stay or leave.
- **Data Cleaning & Feature Engineering:** Fill missing values, handle categorical features, and extract meaningful information.
- **Segmentation & Analysis:** Group customers based on key features and analyze churn behavior across segments.
- **Model Building:** Use machine learning models like Random Forest to predict churn and identify important features.
- **Strategy Recommendations:** Propose actionable insights to improve retention and reduce churn.

## 🔍 Key Insights

1. **Churn & Monthly Charges:**  
   The churn rate rises as Monthly Charges increase. Residents with charges between 60-90 coins face the highest churn rates, making this group particularly sensitive to price changes.

2. **Contract Type Impact:**  
   Month-to-Month contracts have the highest churn rate (42.7%), suggesting that flexibility is leading to higher dissatisfaction.  
   Two-Year contracts have the lowest churn rate (2.8%), indicating long-term residents tend to be more loyal or face higher switching costs.

3. **Tech Support:**  
   Customers with Tech Support have a significantly lower churn rate (24%) compared to those without it (45%). Offering consistent support reduces churn, especially for customers facing technical difficulties.

4. **Single vs. Family-Oriented Residents:**  
   Single Explorers are more likely to churn than Family-Oriented residents. These lone travelers have fewer ties to the kingdom, making them more vulnerable to leaving.

## 🧑‍💻 Technical Overview

### Tools & Libraries Used:
- **Python** for data processing and analysis
- **Pandas** for data manipulation
- **Scikit-learn** for machine learning models and preprocessing
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebooks** for exploratory data analysis (EDA)

### Data Preprocessing:
- **Handling Missing Data:** Missing values in TotalCharges were replaced with 0 to reflect new residents with no charges.
- **Categorical Encoding:** The SeniorCitizen column was decoded from numeric values (0/1) to Yes/No labels for better readability.
- **Feature Selection:** Non-correlated columns were dropped to focus on the most impactful features related to churn.

### Model Pipeline:
- **Preprocessor:** A pipeline was created to handle feature scaling and encoding.
- **RandomForestClassifier:** A robust model was used to predict customer churn based on the features.
- **Model Evaluation:** The model was trained on a balanced dataset, ensuring good performance even with imbalanced classes.

## 📈 Visualizations & Insights

The project includes the following key visualizations to help visualize the relationship between different features and churn:
- **Churn vs Monthly Charges:** A line graph showing the relationship between churn rate and monthly charges.
- **Churn vs Contract Type:** A bar chart highlighting churn rates for different contract types.
- **Churn vs Tech Support:** A comparison between churn rates for customers with and without Tech Support.
- **Segmented Churn Analysis:** A segmentation chart showing churn behavior across different demographic and usage groups.

## 💡 Recommendations

1. **Mid-Range Payees (30-90 coins):**  
   Offer personalized discounts, loyalty rewards, or perks to reduce churn in this vulnerable group.

2. **Month-to-Month Contract Holders:**  
   Increase loyalty incentives for residents with month-to-month contracts. Consider introducing longer-term benefits like One-Year or Two-Year contract offers.

3. **Tech Support Expansion:**  
   Extend Tech Support services to all residents. Proactively assist those showing signs of dissatisfaction to ensure a stronger connection and lower churn.

4. **Community Engagement for Single Explorers:**  
   Provide special offers and organize events that encourage Single Explorers to engage with the community and build connections, reducing their likelihood of leaving.

## 📊 Datasets

The data used for this analysis includes several key columns related to customer demographics, contract details, service usage, and churn behavior:
- **SeniorCitizen:** Whether the customer is a senior citizen.
- **MonthlyCharges:** Monthly service charges.
- **TotalCharges:** Total charges incurred.
- **Tenure:** Length of time the customer has been with the service.
- **Contract:** Type of contract (Month-to-Month, One-Year, Two-Year).
- **TechSupport:** Whether the customer has access to technical support.
- **Churn:** Whether the customer has left the service.

## 🛠️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/data-kingdom-churn-prediction.git
2. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
3. Run the Jupyter notebooks for EDA, modeling, and evaluation.
4. Follow the steps in the notebooks to analyze the data, train the model, and make predictions.

## 🚀 Future Work
Deep Learning Models: Experiment with neural networks or other deep learning techniques to improve churn prediction accuracy.
Real-Time Predictions: Implement real-time churn prediction for new customer data as they sign up or interact with the service.
Optimization: Work on hyperparameter tuning for the RandomForest model or experiment with other models to achieve better performance.
🙌 Contributing
Feel free to fork this project, submit issues, or make pull requests if you have suggestions or improvements to share. Your contributions are always welcome!

## 📄 License
This project is licensed under the MIT License.

