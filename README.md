# Customer-churn-analysis-project
# Customer Churn Analysis  

This project focuses on **customer churn prediction** using **Logistic Regression** and **K-Means Clustering**.  
It includes **data preprocessing, feature scaling, PCA for dimensionality reduction, and clustering analysis**.  

---

## Project Structure  

- `Churn_prediction.ipynb` → Jupyter Notebook containing all analysis and modeling steps.  
- `train_cxid.csv` & `test_cxid.csv` → Training & testing datasets with customer churn labels (**Not included in this repo due to size. See below for download link**). 
- `main.csv` → The main dataset (**Not included in this repo due to size. See below for download link**).  

---

## Dataset Information  

The dataset includes:  
✔ Customer IDs  
✔ Usage patterns over **90 days**  
✔ Churn labels (0 = Retained, 1 = Churned)  
✔ Usage type across different platforms  

 **Dataset Download:** Since `main.csv` is **too large for GitHub**, download it from:  
 **[Google Drive Link](https://drive.google.com/drive/folders/1ebykU9ddt6HYcT5q7RDqacXVptOYw4ww?usp=drive_link)**  

---

## How to Run the Project  

**1️. Install Required Libraries**  
Before running the notebook, install dependencies:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
**2️. Open Jupyter Notebook**
Run:

```bash
jupyter notebook
```
Open Churn_prediction.ipynb and run all cells.

### **Machine Learning Approach**
1. Churn Prediction using Logistic Regression
- Preprocessing: Encoded categorical features & standardized numerical data.
- Training: Applied Logistic Regression with L2 regularization.
- Accuracy: 79%
- Precision/Recall: Higher for retained customers than churned customers.

2. Customer Segmentation using K-Means Clustering
- Used PCA for dimensionality reduction.
- Applied Elbow Method to determine the optimal K.
- Clustered customers into 3 groups based on their usage behavior.






