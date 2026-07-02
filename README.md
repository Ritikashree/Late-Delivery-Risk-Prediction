# Late Delivery Risk Prediction using Machine Learning

## Project Overview
This project predicts whether an order is at risk of being delivered late using Machine Learning techniques. The model is trained on the DataCo Supply Chain Dataset and helps identify potential delivery delays before they occur.

## Problem Statement
Late deliveries can negatively impact customer satisfaction and supply chain efficiency. The objective of this project is to build a predictive model that classifies orders as either having a late delivery risk or not.

## Dataset
- Dataset: DataCo Supply Chain Dataset
- Records: 180,519+
- Features: 50+
- Domain: Supply Chain Analytics

## Target Variable
`Late_delivery_risk`

- 0 → No Late Delivery Risk
- 1 → Late Delivery Risk

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Label Encoding
6. Feature Scaling
7. Model Building
8. Model Evaluation
9. Prediction System Development

## Machine Learning Models Used

### Logistic Regression
Accuracy: 99.33%

### Gaussian Naive Bayes
Accuracy: 99.91%

### Random Forest Classifier
Accuracy: 100.00%

## Selected Model
Random Forest Classifier was selected as the final model because of its superior performance and ability to handle complex relationships within the dataset.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

## Project Structure

```
Late-Delivery-Risk-Prediction/
│
├── dataCosupplychain.ipynb
├── late_delivery_model.pkl
├── scaler.pkl
└── README.md
```

## Prediction Output

| Prediction | Meaning |
|------------|---------|
| 0 | No Late Delivery Risk |
| 1 | Late Delivery Risk |

## Conclusion

This project successfully developed a machine learning model capable of predicting late delivery risk using supply chain data. The Random Forest Classifier achieved the best performance and can assist organizations in proactively managing delivery operations and improving customer satisfaction.

## Author

**Ritika Shree**  
B.Tech Artificial Intelligence and Data Science  
K. Ramakrishnan College of Engineering
