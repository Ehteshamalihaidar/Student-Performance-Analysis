# 🎓 Student Performance Classification and Prediction

## 📌 Problem Domain

This project aims to build an efficient predictive model to classify the final grade of students based on a variety of influencing parameters. It also includes statistical validation using the Chi-square test to examine the relationship between categorical variables and students' academic performance.

## 🎯 Objectives

- Predict students' academic performance (final grade) using prior scores and demographic features.
- Analyze the impact of categorical features such as:
  - Romantic Status
  - Alcohol Consumption
  - Parents' Education Level
  - Frequency of Going Out
  - Desire for Higher Education
  - Living Area
- Use the Chi-square test for significance testing between categorical variables and grades.
- Apply multiple classification models and compare their performance:
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Classifier (SVC)
  - Logistic Regression Classifier

## 🗂️ Dataset

The project uses two datasets:
- `student-mat.csv` (Mathematics performance)
- `student-por.csv` (Portuguese language performance)

These datasets contain information about students’ academic, personal, and social factors.

## 📊 Features Considered

- Demographic: `age`, `address`, `famsize`, `Pstatus`
- Social: `romantic`, `goout`, `internet`
- Academic Support: `schoolsup`, `famsup`, `paid`
- Parental Education: `Medu`, `Fedu`
- Grades: `G1`, `G2`, `G3` (used to calculate performance)
- Alcohol Consumption: `Dalc`, `Walc`

## 🧪 Methodology

1. **Data Preprocessing**:
   - Merge datasets and clean missing/duplicate values
   - Encode categorical variables
   - Categorize final grade into `Poor`, `Fair`, and `Good`

2. **Exploratory Data Analysis (EDA)**:
   - Visualize feature distributions and correlations
   - Generate count plots and heatmaps

3. **Statistical Testing**:
   - Apply Chi-square test for independence between features and final grade

4. **Model Training**:
   - Train multiple classification models
   - Evaluate models using Accuracy, Precision, Recall, and F1-score

5. **Model Comparison**:
   - Summarize all model results for comparison

## 🧰 Technologies Used

- Python (Google Colab)
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for ML models and evaluation)
- Statsmodels (for Chi-square tests)

## 📈 Expected Outcome

- A comparative performance chart of classifiers on student grade prediction.
- Insights into which features most influence student outcomes.
- Statistical understanding of associations between socio-demographic factors and grades.

## 🚀 How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
