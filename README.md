# **Predictive Modeling: Medical Insurance Cost Analysis**  

## **Project Overview**  
This project focuses on analyzing and predicting **medical insurance costs** using various machine learning models. The dataset includes demographic and health-related features such as **age, BMI, number of children, smoking status, and region** to estimate the insurance charges.  

This notebook follows a **structured data science approach**, covering **data exploration, preprocessing, feature engineering, model training, and evaluation**.

---

## **Dataset Description**  
The dataset consists of medical records, including:  
- `age`: Age of the individual  
- `sex`: Gender (male/female)  
- `bmi`: Body Mass Index  
- `children`: Number of children/dependents  
- `smoker`: Smoking status (yes/no)  
- `region`: Residential region (northeast, northwest, southeast, southwest)  
- `charges`: Medical insurance cost (dependent variable)  

---

## **Steps Covered in the Notebook**  

### **1. Exploratory Data Analysis (EDA)**  
✔️ Checking for missing values and data types  
✔️ Statistical summary of numerical columns (`age`, `bmi`, `charges`)  
✔️ Data distribution visualizations:  
   - **Histograms & KDE plots** for continuous variables  
   - **Box plots** for outlier detection  
   - **Correlation heatmap** to analyze feature relationships  
✔️ Categorical feature analysis (`sex`, `smoker`, `region`) using **count plots**  

---

### **2. Data Preprocessing & Feature Engineering**  
✔️ **Handling Missing Values:** Verified that no null values exist in the dataset  
✔️ **One-Hot Encoding:** Converted categorical variables (`sex`, `smoker`, `region`) into numerical form  
✔️ **Feature Scaling:** Used `StandardScaler` for normalizing numerical features like `bmi`  
✔️ **Outlier Detection & Removal:** Identified outliers in `bmi` and `charges` using box plots  

---

### **3. Predictive Modeling**  
Implemented **multiple regression models** to predict **insurance charges**, including:  

#### **Linear Regression**  
- Simple and interpretable model  
- Evaluated with `R² score`, `MAE`, and `MSE`  

---

### **4. Model Evaluation**  
Each model was evaluated using the following metrics:  

| **Metric**              | **Description**                                      |
|-------------------------|------------------------------------------------------|
| **Mean Absolute Error (MAE)**  | Measures average error magnitude (lower is better) |
| **Mean Squared Error (MSE)**   | Penalizes large errors more heavily              |
| **R² Score (R-Squared)** | Measures model performance (higher is better) |

---

## **Results & Insights**  
✔️ **Smoking status has the most significant impact on insurance costs** 🚬  
✔️ **Age and BMI also contribute to higher charges** 📈  
✔️ **Random Forest outperformed other models in accuracy** 🎯  
✔️ **Categorical variables (region, sex) had minimal effect on predictions**  

---

## **How to Run This Notebook**  
1. Open the **Google Colab** link or download the `.ipynb` file.  
2. Ensure all dependencies are installed:  
   ```python
   pip install pandas numpy seaborn scikit-learn matplotlib
   ```
3. Upload the dataset (`insurance.csv`) and update the file path accordingly.  
4. Run the notebook step by step to explore the data, train models, and analyze results.  

---

## **Future Improvements**  
🔹 Try advanced models like **XGBoost or Neural Networks**  
🔹 Use **feature selection techniques** to improve performance  
🔹 Expand analysis with **additional healthcare datasets**  

---

## **Contributors**  
👤 **Mohit Soni**  
📧 Contact: dsmohiit17@gmail.com  
