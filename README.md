# Customer-Lifetime-Value-Prediction-Model

# Customer Lifetime Value Prediction

This project aims to predict the **Customer Lifetime Value (LTV)** for an e-commerce business using historical transaction data. The model helps identify high-value customers and enables strategic marketing and retention efforts.

---

## 📁 Project Files

| File Name                                      | Description                                                                 |
|-----------------------------------------------|-----------------------------------------------------------------------------|
| `Customer Lifetime Value Prediction Model Report.pdf` | Final 2-page project report with overview, methodology, tools, and conclusions |
| `cleaned data set.zip`                        | Cleaned transactional data used for modeling                                |
| `customer metrics.csv`                        | Features engineered per customer: Recency, Frequency, AOV, and Monetary     |
| `final ltv predictions.csv`                   | Predicted LTV values and customer segments (Low, Medium, High)              |
| `Customer Lifetime Value Prediction Model.ipynb` | Jupyter Notebook with complete analysis, feature engineering, modeling      |
| `Project_graphs.zip`                          | Visualizations created from the predicted LTV and customer segments         |

---

## 🛠️ Tools & Technologies

- **Python**: Data wrangling, modeling, and analysis
- **Pandas / NumPy**: Data manipulation
- **Seaborn / Matplotlib**: Data visualization
- **Scikit-learn / XGBoost**: Machine learning and regression modeling
- **Google Colab**: Notebook environment

---

## 📊 Key Steps in the Project

1. **Data Cleaning**: Removed missing customer IDs, calculated total price per order
2. **Feature Engineering**: Computed Recency, Frequency, Monetary, and Average Order Value
3. **Model Training**: Used XGBoost Regressor to predict LTV
4. **Evaluation**: Evaluated model using MAE and RMSE
5. **Customer Segmentation**: Grouped customers into High, Medium, and Low-value based on predicted LTV
6. **Visualization**: Created plots for LTV distribution, segment insights, and feature relationships

---

## 📌 Conclusion

The model provides a data-driven approach to forecast customer value and supports businesses in prioritizing customer engagement strategies. This approach is scalable and can be enhanced with more features or applied to other domains like credit scoring or churn prediction.

---

## 📬 Author

**Vanshika Garg**  
Intern, Data Analyst Program  
Project submitted as part of final evaluation

