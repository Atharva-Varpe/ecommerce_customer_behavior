# E-commerce Customer Behavior Prediction

This project analyzes customer purchasing patterns and predicts customer lifetime value using machine learning techniques. We'll use the **Online Retail Dataset** from Kaggle to build predictive models.

## Dataset

- **Source**: [Kaggle Online Retail Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- **Size**: 500K+ transaction records
- **Features**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Key Features

- **Customer Segmentation**: Utilizes RFM (Recency, Frequency, Monetary) analysis to group customers into meaningful segments like 'Champions', 'Loyal Customers', and 'At Risk'.
- **CLV Prediction**: Employs machine learning models (Random Forest, XGBoost, Neural Networks) to predict the Customer Lifetime Value (CLV), helping to identify high-value customers.
- **Purchase Probability**: A classification model predicts the likelihood of a customer making a purchase within the next 30 days.
- **Interactive Dashboard**: A Streamlit dashboard allows for interactive analysis and visualization of customer data and model predictions.

## Analysis and Models

1.  **RFM Analysis**: Customers are segmented based on their transaction history, allowing for targeted marketing campaigns.
2.  **CLV Prediction**:
    -   **Random Forest Regressor**: Best performing model with an R² of 0.77.
    -   **XGBoost & Neural Networks**: Used for comparative analysis.
3.  **Purchase Probability**: A Random Forest Classifier is trained to identify customers likely to make a purchase soon.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have Python installed, then install the necessary libraries:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn xgboost tensorflow streamlit
