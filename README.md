<img width="845" height="552" alt="image" src="https://github.com/user-attachments/assets/8446d498-89ba-4211-a368-f81b1671d966" />

# Employee Attrition Predictor

Predict whether an employee is likely to leave the company based on HR-related features.

## 🚀 Project Goal
The primary goal of this project is to help HR departments proactively identify employees who are at risk of leaving the organization. By leveraging machine learning models, companies can take informed actions to improve employee retention.

## 🛠️ Features Used
- **Monthly Income**
- **Age**
- **Job Satisfaction**
- **Years at Company**
- **OverTime (Yes/No)**

## 📊 Machine Learning Models
- **Logistic Regression**
- **Decision Tree Classifier**

Both models are trained, evaluated, and compared on multiple performance metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Loaded dataset and handled categorical variables (OverTime).
   - Performed feature selection.

2. **Data Splitting**
   - Divided dataset into training and test sets.

3. **Feature Scaling**
   - Applied **StandardScaler** for Logistic Regression to standardize numeric features.
   - Scaling was not applied to Decision Tree as it is scale-invariant.

4. **Model Training**
   - Trained both Logistic Regression and Decision Tree models on the data.

5. **Model Evaluation**
   - Evaluated both models using Accuracy, Precision, Recall, F1-Score.
   - Displayed Confusion Matrices for both models.
   - Results were formatted as percentages for better readability.

6. **Visualization**
   - Created bar charts to compare model performances across different metrics.
   - Applied dark theme and custom color palettes for visualization aesthetics.

## 📈 Model Performance Comparison

| Metric     | Logistic Regression | Decision Tree |
|------------|---------------------|---------------|
| Accuracy   | 37.14%              | 40.00%        |
| Precision  | 37.93%              | 36.36%        |
| Recall     | 73.33%              | 53.33%        |
| F1-Score   | 50.00%              | 43.24%        |



## 📊 Visualization Sample
![Model Performance Comparison](<img width="845" height="552" alt="image" src="https://github.com/user-attachments/assets/7fa45ca3-b1ab-429a-8216-8300ed8d55af" />)

## 📦 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📂 Project Structure
├── README.md
├── dataset.csv
├── Employee Attrition Predictor.ipynb
---

## 🔮 Future Enhancements
- Hyperparameter tuning for improved model performance.
- Incorporate additional features such as Work-Life Balance, Environment Satisfaction, etc.
- Deploy the model as a web application.

## 👨‍💻 Author
- **Adarsh Raj**

---
