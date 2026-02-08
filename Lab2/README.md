# Lab 2: Problem Formulation & Methodology

### 📱 Dataset Selection
* **Dataset Name:** Mobile Price Classification
* **Source:** Kaggle
* **File:** `mobile_data.csv`

### 📝 Problem Statement
**Goal:** To build a classification model that predicts the price range of a mobile phone based on its internal specifications (RAM, Battery, Camera, etc.).

* **Input Features:** 20 features (e.g., `ram`, `battery_power`, `px_height`, `px_width`)
* **Target Variable:** `price_range` (0 = Low Cost, 1 = Medium Cost, 2 = High Cost, 3 = Very High Cost)
* **Problem Type:** Multi-class Classification

### 📂 Files Included
1. **`Lab2_Final.ipynb`**: The Jupyter Notebook containing data loading, inspection (`df.info()`), and problem definition.
2. **`mobile_data.csv`**: The raw dataset used for training.
3. **`methodology.png`**: A flowchart illustrating the proposed ML pipeline.

### 🚀 Methodology Workflow
![Methodology Diagram](methodology.png)
