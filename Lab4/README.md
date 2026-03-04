# Lab 4: Data Quality Assessment & Preprocessing

### Objective
To apply practical data preprocessing and quality assessment techniques to the Mobile Price Classification dataset, preparing it for future machine learning models.

### Techniques Applied
* **Data Quality Assessment:** Verified that all dataset columns are numeric and correctly formatted.
* **Missing Value Handling:** Simulated missing data and applied **Mean** and **Median Imputation** strategies to resolve them.
* **Outlier Detection & Handling:** Used Boxplots and the **Interquartile Range (IQR)** method to detect outliers in the `fc` (Front Camera) feature, applying both removal and capping strategies.
* **Feature Scaling:** Applied **Min-Max Normalization** and **Z-Score Standardization** to bring features like `ram` and `battery_power` onto a common scale.
* **Dimensionality Reduction (PCA):** Analyzed feature correlation and applied **Principal Component Analysis (PCA)** to visualize the data distribution of uncorrelated features in a lower-dimensional space.

### Files Included
1. `4- Data Quality Assessment & Preprocessing.ipynb` - The Jupyter Notebook containing all preprocessing steps.
2. `mobile_data.csv` - The dataset used for preprocessing.
