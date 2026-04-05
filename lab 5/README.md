Objective
To build a baseline classification model to predict the price_range of mobile phones and evaluate how Feature Engineering (creating new metrics and transforming existing ones) affects model performance and feature importance.

Techniques Applied
Feature Engineering (Hardware-Based): Combined raw dimensions like screen height and width to create a more powerful Screen Area metric.

Performance-Based Metrics: Engineered a RAM per Core feature to capture the hardware balance between memory and processing power.

Optional Domain Features: Created a Total Camera Megapixels feature by combining front and primary camera specifications.

Discretization (Binning): Transformed the continuous battery_power variable into a categorical Battery Tier (Low, Medium, High, Very High) to help the model capture non-linear trends.

Pipeline Construction: Utilized ColumnTransformer and OneHotEncoder within a Scikit-Learn Pipeline to automate the transformation of categorical engineered features.

Baseline Modeling: Trained a Random Forest Classifier and analyzed its built-in Feature Importance to identify the primary drivers of mobile phone pricing.

Feature Selection: Applied SelectFromModel with a median threshold to reduce model complexity by pruning low-impact features.

Files Included
ARTI308 Lab5.ipynb - The Jupyter Notebook containing the full feature engineering and classification workflow.

mobile_data.csv - The mobile specifications dataset used for training and evaluation.
