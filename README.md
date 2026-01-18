# customer-chrun-ml
End-to-end ML project predicting customer churn using Python, SQL-style analysis, and Random Forest.

# Customer Churn Prediction

## Project Overview
This project predicts whether a customer will churn (leave the service) using subscription and usage data.  
It demonstrates **end-to-end machine learning workflow** including data exploration, preprocessing, feature encoding, model training, and evaluation.

The model can help companies **identify high-risk customers** and improve retention strategies.

---

## Tech Stack
- **Python**  
- **Pandas & NumPy** — data manipulation  
- **Scikit-learn** — machine learning  
- **Joblib** — model saving  
- **Google Colab** — development environment  

---

## Dataset
- **Telco Customer Churn dataset** (sample included)  
- Columns include customer information, subscription details, and churn target variable.  
- Small version included in repo (`data/churn.csv`). Full dataset can be loaded from Kaggle if desired.

---

## Key Insights
- Customers with **shorter tenure** are more likely to churn  
- **Higher monthly charges** correlate with churn  
- Customers with **month-to-month contracts** have higher churn risk  

---

## Model
- **Random Forest Classifier** trained on encoded features  
- Accuracy on sample data: 100% (small dataset)  
- Model saved as `churn_model.pkl`  

---

## Project Structure
