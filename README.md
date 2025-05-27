# About

This project explores the application of K-Nearest Neighbors (KNN) for both classification and regression tasks using two real-world datasets:

- Medical Appointment No-Show Dataset (Classification)
Predicts whether a patient will attend their scheduled medical appointment using demographic and health-related features. This helps understand patterns behind appointment absenteeism in healthcare.

- Concrete Compressive Strength Dataset (Regression)
Predicts the compressive strength of concrete (in megapascals) based on its ingredients and age. This supports decision-making in civil engineering by modeling the highly nonlinear relationship between materials and strength.

### 🏥 Dataset 1 – Medical Appointments (No-Show)
- **Goal:** Predict whether a patient will attend their scheduled medical appointment.
- **Approach:** Classification using K-Nearest Neighbors (KNN)

#### Project overview:
- Label encoding for categorical values
- Feature selection and preprocessing
- Split into train-test sets
- KNN classifier (default `k=5`)
- Model evaluation using accuracy score
- Suggestions for model improvements (e.g., scaling and hyperparameter tuning)

---

### Dataset 2 – Concrete Compressive Strength
- **Goal:** Predict the compressive strength of concrete (in MPa) based on its ingredients and age.
- **Approach:** Regression using both Linear Regression and KNN (optional extension)

#### Highlights:
- Exploratory data handling using Pandas
- Simple linear regression model
- Scatter plot visualization of actual vs predicted values
- Discussion on underfitting and outliers
- Suggestions for stronger models like Random Forest for non-linear patterns
