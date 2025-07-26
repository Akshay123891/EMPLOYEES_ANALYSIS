
# Employee Performance and Retention Analysis

This project analyzes employee performance and attrition trends using data science techniques such as Exploratory Data Analysis (EDA), Machine Learning, and Deep Learning.

---

## Objective

To develop a model that can:
- Predict employee attrition (whether an employee will leave).
- Predict employee performance score.
- Provide insights and recommendations to help improve employee retention and performance.

---

## Dataset

The dataset (`Employee_data.csv`) should contain the following columns:
- Employee ID
- Name
- Age
- Department
- Salary
- Years at Company
- Performance Score
- Attrition (Yes/No)

---

## Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `scipy`
- `tensorflow` / `keras` (optional for deep learning)

---

## Project Workflow

### Phase 1 – Exploratory Data Analysis
- Data Cleaning and Preprocessing
- Descriptive Statistics
- Pairplot and Correlation Heatmap
- Boxplots for outlier detection

### Phase 2 – Statistical Analysis
- Conditional Probabilities (Bayes’ Theorem)
- Hypothesis Testing (ANOVA)

### Phase 3 – Machine Learning Models
- Attrition Prediction: Random Forest Classifier
- Performance Prediction: Linear Regression

### Phase 4 – Deep Learning Models (Optional)
- Neural Network for Regression and Classification

### Phase 5 – Reporting and Visualization
- Feature Importance Analysis
- Department-wise attrition rates
- Performance trends over years
- Salary vs Performance scatter plot

---

##  Model Evaluation

### Classification (Attrition)
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix

### Regression (Performance Score)
- R² Score
- Mean Squared Error (MSE)
- Predicted vs Actual Scatter Plot

---

## Visualizations

- Line Plot: Performance over Years at Company
- Bar Chart: Department-wise Attrition
- Scatter Plot: Salary vs Performance
- Heatmap: Feature Correlations

---

## Insights & Recommendations

- Identify key features influencing attrition and performance.
- Highlight departments with higher attrition.
- Recommend employee engagement and retention strategies.

---

## Files in Repository

| File                             | Description |
|----------------------------------|-------------|
| `EMPLOYEES_ANALYSIS.ipynb`       | Main analysis notebook |
| `Employee_data.csv`              | Employee dataset (user-provided) |
| `README.md`                      | Project documentation |

---

## How to Run

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/employee-performance-analysis.git
cd employee-performance-analysis
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the notebook
```bash
jupyter notebook EMPLOYEES_ANALYSIS.ipynb
```

---

## Author

Akshay Kumar  
palakshay9389@gmail.com

---

## License

This project is licensed under the [MIT License](LICENSE).
