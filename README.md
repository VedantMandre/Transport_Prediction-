# Vehicle Transport Mode Prediction
Introduction
This project aims to predict whether a person will use public or private transport based on their demographic and employment data. The dataset contains information on age, gender, education, work experience, salary, distance from work, and license ownership for 444 individuals.

# Data Exploration
The data was explored using Pandas, Numpy, Matplotlib and Seaborn. Key findings:

Gender is imbalanced with ~70% male and 30% female
Most individuals use public transport
Age and work experience are highly correlated with salary
Engineers tend to have higher salaries

#Model Building
The following models were trained and evaluated:

Logistic Regression
Linear Discriminant Analysis
Decision Tree
Naive Bayes
K-Nearest Neighbors
Random Forest
Gradient Boosting
Metrics calculated:

Accuracy
Precision
Recall
F1 Score
AUC-ROC
Results
Random Forest performed best with a test AUC of 0.84. The top models were:

Random Forest
Gradient Boosting
Decision Tree
Conclusion
This analysis shows that demographic and employment variables can predict with good accuracy whether someone will use public or private transport. Random Forest was the best performing model.
