# 🧠 DSA4262: Machine Learning for PCOS Prediction and Analysis

This project explores the application of machine learning (ML) techniques to predict Polycystic Ovary Syndrome (PCOS) using clinical and lifestyle data. PCOS is a common hormonal disorder among women of reproductive age, with symptoms ranging from irregular menstrual cycles to long-term health risks such as diabetes and cardiovascular disease.

Our project investigates traditional ML models as well as deep learning architectures, including a novel TabTransformer-based model, to enhance diagnostic accuracy.

## 📊 Dataset
We used a cleaned and feature-engineered version of the [PCOS dataset from Kaggle](https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos). The dataset includes clinical, lifestyle, and hormonal features.

### Data Preprocessing:
- Handled missing and incorrectly typed values
- Removed outliers and non-informative columns
- Discretised continuous features using clinically meaningful bins
- Scaled numerical variables and applied one-hot encoding to categorical variables

---
## 🧪 Models Implemented
1. **Traditional ML Models**
   - Logistic Regression (LR)
   - Random Forest Classifier (RFC)
   - Support Vector Machine (SVM)
   - XGBoost
   - Gaussian Process Classifier (GPC)
2. **Deep Learning Models**
   - Multi-Layer Perceptron (MLP)
   - TabTransformer (Deep learning model for tabular data)
   - Novel TabTransformer (Enhanced TabTransformer Architecture)
---

## 🔍 Key Contributions
- Proposed a discretisation approach for clinical variables to align with medical standards
- Enhanced TabTransformer architecture to jointly process continuous and categorical features
- Demonstrated that deep learning models, when properly adapted, can handle real-world structured medical data effectively

---
## 🚀 How to Run
1. **Clone the repository**
   ```git clone https://github.com/stacychann/dsa4262_pcos.git```
2. **Create virtual environment**
   ```python -m venv venv```
   ```source venv/bin/activate```
3. **Install dependencies**
```pip install -r requirements.txt```

---
🤝 Acknowledgements
- This project was developed as part of **NUS DSA4262 Sense-making Case Analysis: Health and Medicine**. We thank our professor and TA for their feedback and support.



 
