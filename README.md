# Heart Disease Predictor

### Overview
This project aims to build a predictive model for heart disease detection using a dataset containing various health and demographic features. The goal is to identify individuals at risk of heart disease through effective preprocessing, exploratory analysis, and machine learning techniques.

### Table of Contents
1. **Importing Libraries + Loading Data**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**
4. **Model Selection**
5. **Model Training and Evaluation**
6. **Conclusion**

### Key Highlights
- **Dataset**: Features include `Stroke`, `DiffWalking`, `AgeCategory`, and `Diabetic`, which were observed to have a significant correlation with heart disease.
- **Imbalanced Data**: The dataset was highly imbalanced, necessitating preprocessing techniques to handle bias.
- **Feature Selection**: Certain features like `Sex` and `Race` were found to have weak correlations and may be dropped in future iterations.
- **Mental Health Analysis**: Analyzed the relationship between mental health and heart disease, noting that individuals reporting better mental health had a lower proportion of heart disease cases.

### Methodology
1. **Data Preprocessing**:
   - Addressed class imbalance and removed weakly correlated features.
   - Applied normalization and scaling to ensure consistent data input.

2. **Exploratory Data Analysis**:
   - Identified impactful features and their relationships with the target variable.
   - Visualized data distributions to uncover trends and imbalances.

3. **Model Selection and Training**:
   - Tested various machine learning models to find the most effective classifier.
   - Evaluated models based on accuracy, precision, recall, and F1-score.

4. **Evaluation**:
   - Compared model performance and selected the best-performing algorithm for deployment.

### Results
- The trained model demonstrates high accuracy in predicting heart disease.
- Insights from the analysis provide actionable guidelines for further improvement in feature engineering and preprocessing.

### How to Run
1. Clone the repository.
2. Install dependencies using `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook heart-disease-predictor-model-detailed.ipynb
   ```

### Future Work
- Improve feature engineering to enhance prediction accuracy.
- Test additional algorithms and deep learning techniques.
- Integrate real-time prediction capabilities in a web-based or mobile application.

### Acknowledgments
Special thanks to Kaggle for providing the dataset and fostering research in heart disease prediction.
