# Predictive-Modelling-for-Early-Detection-of-Alzheimer-Disease 🧠

![Python](https://img.shields.io/badge/Python-3.12-blue) 


This repository presents the development and evaluation of predictive models for the early detection of Alzheimer's Disease (AD) using non-imaging clinical data from the Open Access Series of Imaging Studies (OASIS-1 and OASIS-2) datasets. 

## Features ✨
- 🧹 **Data Cleaning and Preprocessing**
- 📊 **Exploratory Data Analysis (EDA)**
- 🤖 **Machine learning model training**
- 🔍 **Feature Importance Analysis**
- 🧠💡 **Explainable AI**
- 📈 **Performance Metrics**
- 📚 **Documentation and user guide**

  ## Models Evaluated

Several machine learning models, including Logistic Regression, Decision Trees, Random Forests, and XGBoost, were trained and evaluated using accuracy, precision, and interpretability metrics such as confusion matrices, ROC curves and SHAP values. Notably, the Random Forest and XGBoost models achieved high performance, with accuracy around 95.90% and AUC-ROC scores of 0.98.

Key clinical indicators, such as the Clinical Dementia Rating (CDR) and Mini-Mental State Examination (MMSE) scores, were identified as critical predictors, reinforcing their established roles in dementia assessment. This study demonstrates that models relying solely on clinical data can match or exceed the performance of neuroimaging-based models, offering healthcare professionals a valuable tool for enhancing early AD detection strategies. 

## Setup Instructions

Follow these steps to set up and run the project on your local machine.

### Prerequisites

- Python 3.x
- pip
- git

### 1. Clone the Repository
Clone the repository to get a copy on your local machine:
  ```bash
  git clone https://github.com/yourusername/Predictive-Modelling-for-Early-Detection-of-Alzheimer's-Disease.git
```

### 2. Navigate to the Project Directory
Change into the project directory:
```bash
cd Predictive-Modelling-for-Early-Detection-of-Alzheimer's-Disease
   ```

### 3. Create and Activate the Virtual Environment
Set up a virtual environment to manage the dependencies for the project:
- **For Windows**:
```bash
python -m venv venv
venv/Scripts/activate
```
- **For macOS and Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Required Packages
Install all the necessary packages using pip:
```bash
pip install -r requirements.txt
```

### 5. Start the Jupyter Notebook Server
Launch Jupyter Notebook:
```bash
jupyter notebook
```
### 6. Navigate to and Run the Notebook
From the Jupyter dashboard, navigate to the directory containing the notebook file (e.g., Oasis Random Forest.ipynb) and open it. Execute the cells by clicking on each and pressing Shift + Enter, or use the toolbar options like "Run All" to execute all cells in sequence.

### 7. Deactivate the Virtual Environment
Once you are done, you can deactivate the virtual environment:
```bash
deactivate
````

### Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your improvements.

### License
This project is licensed under the MIT License - see the LICENSE file for details.


This integrated README structure provides a full overview of the project from high-level features and model evaluations to detailed setup instructions, all in a single document. 
