# Decision-Tree-Car-Purchase-Decision-Maker
This repository contains a **Decision Tree Classifier** implementation on the **Car Evaluation dataset** using Python and `scikit-learn` to predict car acceptability based on features such as buying price, maintenance, doors, persons capacity, luggage boot size, and safety.

---

## 🤖 What is a Decision Tree Classifier?

A **Decision Tree Classifier**:
- Is a supervised learning algorithm used for **classification and regression tasks**.
- Splits the dataset into branches based on feature conditions, leading to decision leaves.
- Is **easy to interpret** and can handle categorical features efficiently.

---

## 🚀 Features

✅ Loads the **Car Evaluation dataset** and assigns clear column names.  
✅ Encodes **categorical features using Label Encoding** for numeric model compatibility.  
✅ Splits the dataset into **training and testing sets (70%-30%)**.  
✅ Trains a **Decision Tree Classifier** on the dataset.  
✅ Evaluates the model using:
- **Classification report (precision, recall, f1-score)**
- **Accuracy score (%)**

---

## 🗂️ Dataset

The **Car Evaluation dataset** is commonly used for multiclass classification and contains:
- **Features:**
  - Buying price
  - Maintenance
  - Number of doors
  - Persons capacity
  - Luggage boot size
  - Safety
- **Target:**
  - Car acceptability (`unacc`, `acc`, `good`, `vgood`)

The dataset is encoded using `LabelEncoder` to convert categorical values into numerical labels for the classifier.

---

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies using:

```bash
pip install pandas numpy scikit-learn
