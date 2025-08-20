This project focuses on analyzing a lead dataset to predict the probability of conversion (lead score). The workflow followed a structured approach:

Steps Taken:

Data Cleaning → handled missing values, removed duplicates, dropped irrelevant features.
Feature Engineering → one-hot encoding for categorical data, scaling for numerical features.
Modeling → applied Logistic Regression, Random Forest, and SVM with hyperparameter tuning (GridSearchCV).
Evaluation → assessed models with accuracy, precision, and recall.
Feature Importance → Random Forest used to identify top factors driving lead conversion.
Visualization → conversion funnel and key feature impact illustrated with plots.

Key Insights:

Data quality strongly influenced model performance.
Logistic Regression provided interpretability, Random Forest highlighted feature importance, and SVM delivered robust classification.
Certain categorical and numerical features had outsized influence on lead conversion.

Lessons Learned:

Proper data preprocessing is critical.
Model choice and tuning impact both performance and interpretability.
Actionable insights (feature importance + funnel visualization) make the analysis useful for stakeholders.
