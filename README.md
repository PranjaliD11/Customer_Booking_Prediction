# Customer Booking Prediction: Handling Imbalanced Data with SMOTE & Random Forest

## 📌 Project Overview
This project aims to predict customer bookings based on various features using machine learning models. The dataset was preprocessed using encoding techniques and oversampling methods to handle class imbalance. The final model, **Random Forest**, achieved an accuracy of **87%**.

## 📂 Dataset
The dataset contains customer booking details with categorical and numerical features. The target variable indicates whether a customer completed a booking or not.

## 🛠️ Data Preprocessing
1. **Data Mapping:** Converted categorical variables into meaningful numerical values.
2. **Encoding Techniques:**
   - `pd.get_dummies()` for one-hot encoding.
   - Label encoding for categorical features.
3. **Handling Imbalanced Data:**
   - Used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset.

## 🚀 Model Training & Evaluation
We trained multiple machine learning models to predict customer bookings:
- **Logistic Regression**
- **Random Forest Classifier** (Best Model)

### 📊 Model Performance
| Model | Accuracy |
|--------|----------|
| Logistic Regression | ~85% |
| Random Forest | **87%** |

## 📈 Key Takeaways
✅ Preprocessing steps like encoding and data mapping improved model performance.  
✅ Using **SMOTE** effectively addressed class imbalance, improving predictive accuracy.  
✅ **Random Forest outperformed Logistic Regression** with an accuracy of **87%**.  

## 📝 Next Steps
🔹 Fine-tune hyperparameters for further improvements.  
🔹 Experiment with other classification models like XGBoost.  
🔹 Feature selection to enhance model interpretability.  

---
📌 **Author:** Pranjali Deshmukh  
📌 **Tools Used:** Python, Pandas, Scikit-Learn, SMOTE, Random Forest  
📌 **Feel free to fork and contribute!** 🚀

