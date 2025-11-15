# GL_PGP-DSBA_Machine-Learning-2
This project builds a machine-learning model to predict visa certification outcomes using applicant and employer attributes. It analyzes education, experience, wages, and region factors, applies sampling and tuning techniques, and identifies key approval drivers to help automate and improve visa decision-making.

# Project Summary
This project aims to support the U.S. visa certification process by developing a machine-learning solution that predicts whether an application will be certified or denied. The dataset includes over 25,000 records containing applicant qualifications, employer details, wages, and job characteristics. After extensive data cleaning and feature engineering—such as standardizing wages, deriving company age and size, and encoding categorical variables—the dataset is analyzed to uncover trends affecting visa outcomes.

Multiple models are built across original, oversampled, and undersampled datasets, including Decision Trees, Bagging, Random Forests, AdaBoost, and Gradient Boosting. Performance is evaluated using F1-score, which best balances precision and recall in this imbalanced classification task. AdaBoost and Gradient Boost emerge as the strongest performers with minimal overfitting. Hyperparameter tuning is applied to the top three models, followed by a stacked ensemble for further improvement.

The final model selected is the tuned AdaBoost classifier, achieving high recall (~87%) and balanced precision (~78%), enabling accurate identification of both approved and denied applications. Feature importance analysis reveals education level, prior job experience, hourly wage, region of employment, and wage unit as the strongest drivers of visa decisions.

Based on these insights, the project provides actionable recommendations for employers—including prioritizing skilled candidates, offering competitive wages, and strengthening role justification—to improve visa approval likelihood.
