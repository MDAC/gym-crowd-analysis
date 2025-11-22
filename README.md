# Gym Crowdness Analysis & Prediction

This project analyzes the crowdness of a university gym and builds predictive models to estimate the busiest times.  
It was completed as a final project for the course **“Análisis Inteligente de Datos”**.

The work includes:
- Data exploration and cleaning
- Feature engineering (weather, datetime processing, etc.)
- Visual analysis of crowd patterns
- Dimensionality reduction (PCA)
- Predictive modeling (Random Forest, SGDRegressor, Logistic Regression)
- Visualization of predictions and trends

---

## 📁 Project Structure
├── Tp Final - Crowdedness at the Campus Gym.ipynb

├── data.csv

├── README.md

└── requirements.txt

---

## 📊 Methods Used

### **1. Data Analysis**
- Exploration of variables, datatypes and distributions  
- Temperature conversion (Fahrenheit → Celsius)  
- Date parsing and time-based feature extraction  

### **2. Feature Engineering**
- Hour, weekday, weather variables  
- Normalization / Standardization  
- Dimensionality reduction using PCA  

### **3. Machine Learning Models**
- **RandomForestRegressor**
- **SGDRegressor**
- **Logistic Regression**
- Train/test split using `sklearn`  
- Prediction and performance comparison  

### **4. Visualization**
- Correlation heatmaps  
- Scatter plots for trends  
- Prediction curves vs. real values  

---

## 🧰 Technologies Used
- Python  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn (modeling, preprocessing, PCA)

---

## 🚀 How to Run the Project

1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Start Jupyter:
```bash
jupyter notebook
```
3. Open:
Tp Final - `Crowdedness at the Campus Gym.ipynb`

4. Make sure `data.csv` is in the same folder.

# 📌 **Results (Summary)**

Identified the hours with the highest gym occupancy

Extracted relevant factors such as hour, weekday, temperature, and more

Built predictive models capable of estimating crowd levels

Visualized model performance and busiest periods

# 📄 **License**

This project is for academic and portfolio purposes.
