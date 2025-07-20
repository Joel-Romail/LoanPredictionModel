"Explainable Machine Learning for Credit Risk Assessment using SHAP: A Human-Centered Decision Support Tool"

Developed a machine learning model to predict credit risk (good vs. bad credit) using the German Credit dataset ( https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data), 
and apply SHAP (SHapley Additive Explanations) to explain the model's decisions at both global and individual levels. 
The system will simulate a real-world AI-assisted credit approval scenario where model transparency is critical for fairness, accountability, and trustworthiness.

Trained a tabular classification model (XGBoost or RandomForest) on financial and demographic data.

Used SHAP (TreeExplainer) to generate global and local explanations.

Interpreted why a loan is accepted or denied using plots and natural language explanations.

Handled typical errors and preprocessing issues (e.g., categorical encodings, missing values, SHAP errors).
