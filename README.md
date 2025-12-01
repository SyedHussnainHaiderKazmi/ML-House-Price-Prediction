# 🏡 ML House Price Prediction

A machine learning project that predicts house prices using structured housing data from Kaggle. The project applies multiple regression models, compares performance, and identifies the best-performing algorithm for price forecasting.

---

## 📁 Project Structure

ML-House-Price-Prediction/
│
├── 1_Google_Colab_notebook/
│   └── ML_Final_Project_A25_Syed_Kazmi.ipynb
│
├── 2_Dataset_files/
│   ├── House price data.csv
│   └── House price data.xlsx
│
├── 3_Presentation/
│   ├── ReDI_ML_Final_Project.pptx
│   └── ReDI_ML_Final_Project.pdf
│
├── 4_Results_Plots/
│   └── All model evaluation & EDA plots (8)
│
└── README.md

---

## 📌 Project Overview
This project builds a machine learning system to **predict house prices** using features such as size, location, condition, and construction details.  
Multiple regression models were trained and evaluated using **MAE**, **RMSE**, and **R²** to identify the most accurate predictor.

**Best Model:** XGBoost (highest R², lowest errors)

---

## 📊 Included Files
- **Colab Notebook:** Complete workflow with EDA → preprocessing → modeling
- **Datasets:** CSV & Excel versions of the Kaggle housing dataset
- **Presentation:** Final slides (PPTX + PDF)
- **Plots Folder:** EDA and model performance visualizations

---

## 🧠 Methodology (Short Summary)
- Data cleaning, outlier removal (IQR), and feature engineering  
- Exploratory Data Analysis (EDA)  
- Training 5 models:  
  - Linear Regression  
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting  
  - XGBoost  
- Model comparison with MAE, RMSE, R²  
- Best model selection + interpretation

---

## 📈 Best Model Selection
XGBoost delivered the most reliable results:
- **MAE:** Lowest among all models  
- **RMSE:** Best error stability  
- **R²:** ≈ 0.69 (strongest predictive performance)

---

## ⚖️ Ethical Considerations
- **Location bias:** City/statezip may reflect socio-economic differences  
- **Historical patterns:** Renovation & age features may embed inequality  
- **Sampling bias:** Dataset from a single region limits generalization  
- **Responsible use:** Predictions are property-level, not individual-level  

---

## 🚧 Limitations
- Limited geographic region  
- Missing key real-estate factors (schools, crime, HOA fees, interior quality)  
- Market trends not captured (interest rates, seasonal shifts)  
- Outlier removal may exclude luxury/low-end properties  

---

## 🚀 Future Improvements
- Hyperparameter tuning for XGBoost  
- Incorporating neighborhood & market-level features  
- Using robust models or log-transformed targets  
- Adding temporal trends (month/year/seasonality)  
- SHAP-based explainability analytics  

---

## ▶️ How to Run the Notebook
1. Open the `.ipynb` file in Google Colab  
2. Upload datasets from `2_Dataset_files/`  
3. Run all cells from top to bottom  
4. Ensure required libraries are installed

---

## 📚 Libraries Used
- **pandas**, **numpy**  
- **matplotlib**, **seaborn**  
- **scikit-learn**  
- **xgboost**

---

## 📞 Contact
**Author:** Syed Hussnain Haider Kazmi  
**GitHub:** github.com/SyedHussnainHaiderKazmi  

---

## ✅ End of README
Thank you for reviewing this project!