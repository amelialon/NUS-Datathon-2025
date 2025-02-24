# NUS Datathon 2025 - Company Classification Project

## 📜 Project Overview
Participated in the **NUS Datathon 2025**, a 6-day data science competition focused on developing a machine learning model to predict company classifications (Domestic vs. Global) based on operational, financial, and structural characteristics.

## 🎯 Objectives
- Predict whether a company is classified as Domestic or Global based on the given dataset.
- Implement efficient data-cleaning, visualization, and modeling techniques to achieve high accuracy.

## 🛠️ Approach
### 1. Data Preprocessing
- Handled missing values using appropriate imputation techniques:
  - Dropped missing values for historical facts like `Year Found`.
  - Used KNN imputation for `Employees (Global Ultimate Total)` based on related variables.
  - Applied median imputation for `Employees (Domestic Ultimate Total)`.
  - Imputed missing `Latitude` and `Longitude` using industry-based mean coordinates.
- Identified and treated outliers to ensure data consistency.

### 2. Exploratory Data Analysis (EDA)
- Visualized feature distributions and relationships using `matplotlib` and `seaborn`.
- Identified key features contributing to company classification.

### 3. Model Development
- Trained a **Random Forest Classifier** to predict company classification.
- Evaluated model performance using accuracy, precision, recall, and F1-score.

## 🧰 Technologies Used
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Imbalanced-learn
- **Environment:** Jupyter Notebook, Google Colab

## 📊 Results
- Achieved high classification accuracy using the Random Forest model.
- Identified key predictors for company classification, enhancing interpretability.

## 🚀 How to Run
1. **Clone this repository:**
```bash
git clone https://github.com/amelialon/NUS-Datathon-2025.git
```

2. **Install required packages:**
```bash
pip install -r requirements.txt
```

3. **Open the Jupyter notebook:**
```bash
jupyter notebook NUS_Datathon_CAT_B_18.ipynb
```

## 🙌 Acknowledgements
Thanks to the **NUS Statistics and Data Science (SDS) Club** for organizing the datathon and providing a challenging yet insightful learning experience.
Thanks to my collaborators Kuah Si Ying & Vivien Chin for working together with me for this project.
