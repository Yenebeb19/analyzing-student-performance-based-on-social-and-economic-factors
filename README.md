# analyzing-student-performance-based-on-social-and-economic-factors
This project analyzes how social and economic factors like parental education, test preparation, and lunch type affect student performance. Machine learning models predict scores, identify key influences, and provide insights for improving academic outcomes.
Project Overview:

This project analyzes how social and economic factors influence student academic performance. Using a dataset containing student scores and demographic information, we explore key factors, build predictive models, and provide actionable insights to improve academic outcomes.
Objectives

Understand patterns in student performance data.

Identify social and economic factors affecting scores.

Build predictive machine learning models.

Compare and evaluate multiple models.

Provide actionable insights for educators and policymakers.
Dataset:

The dataset includes student exam scores and social/economic features such as:

Gender

Parental education levels

Lunch type

Test preparation course

Other demographic and socioeconomic factors

Target variable: Student performance score (e.g., math score, reading score, or overall score).
Project Steps:

Install packages & import libraries – Setup Google Colab environment.

Upload & load dataset – Import CSV dataset into Colab.

Data loading/inspection – Check dataset structure, types, and missing values.

Exploratory Data Analysis (EDA) – Summarize distributions and relationships.

Visualize data – Explore patterns and correlations.

Data preprocessing – Handle missing values, encode categorical variables, scale features.

Prepare data for modeling – Split into features and target, train/validation sets.

Create multiple models – Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost.

Evaluate models – Compare using R² and Mean Squared Error (MSE).

Select best model – Detailed evaluation and residual analysis.

Cross-validation – Validate top models for reliability.

Predict on test data – Generate predictions using the best model.

Feature importance – Identify key factors influencing performance (tree-based models).

Complete summary – Final comparison of models, metrics, and sample predictions.

Save cleaned dataset – Save the fully preprocessed dataset for future use.

Models Used:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

XGBoost Regressor

Tree-based models were used to visualize feature importance and identify the most influential factors.

Results

Key factors impacting student performance: parental education, test preparation course, lunch type.

Best performing model: [Insert Best Model Name] with validation R² = [Insert Score].

Residual analysis confirms accurate prediction patterns.

Feature importance highlights which variables have the most impact on student scores.

Conclusion:

This project demonstrates how social and economic factors affect student performance and how machine learning can predict outcomes. Insights from feature importance and model evaluation can help educators and policymakers improve student results with targeted interventions.

License:

This project is licensed under the MIT License.
