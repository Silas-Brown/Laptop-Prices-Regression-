# 💻 Laptop Price Prediction  

## (1) Overview  

This project builds a **regression model** to predict laptop prices based on specifications, brands, and operating systems.  

✅ **Dataset:** 11,768 laptops, 9 features  
✅ **Goal:** Predict laptop prices & analyze prediction intervals  

---

## (2) Methodology  

### 🔹 2.1 Data Processing  
- **Feature Representation:**  
  - **GPU & Processor** → Ranked categories  
  - **Resolution** → Pixel count (e.g., 1920×1080 → 2,073,600)  
  - **Brand & OS** → One-hot encoded  
- **Data Cleaning:** No missing values, extreme values removed  

### 🔹 2.2 Model Training & Validation  
- **Regression Assumptions Checked:**  
  - Homoscedasticity & normality of residuals (visual analysis)  
  - No autocorrelation (Durbin-Watson test)  
- **Feature Selection:**  
  - Pruned features based on **95% confidence intervals of coefficients**  
  - **Negligible impact** on performance metrics  

### 🔹 2.3 Model Performance  
- **10-Fold Cross-Validation Metrics:**  
  - **Mean Squared Error (MSE)**  
  - **Mean Absolute Error (MAE)**  
  - **R-squared (R²)**  

### 🔹 2.4 Prediction Intervals  
- **Train-Test Split Applied**  
- **90% Prediction Intervals Calculated**  
- **Coverage Rate of Actual Prices Analyzed**
- - **Distribution of margins of error analyzed**  

---

## (3) Implementation  

### **🔗 Full Implementation in Colab:**  
https://colab.research.google.com/drive/1Mas1-huzLF4Db91OiauHwVFSJJW_uhZv#scrollTo=Mu_J-VuMDapv
---

## (4) Future Improvements  
🔹 Test deep learning methods    
---

## (5) Contact  
📧 Email: **silasaverybrown@gmail.com**  
💡 LinkedIn: [Silas Brown](https://www.linkedin.com/in/silas-brown/)  

