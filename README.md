# Random Forest Model Project

## Overview
This project demonstrates the implementation of a Random Forest Classifier to predict income levels based on demographic and employment data.

### Problem Statement
The goal of the project is to classify whether an individual's income exceeds $50K/year based on census data.

### Dataset
The dataset used for this project contains various attributes such as age, work class, education, occupation, etc., to predict income levels.

- **Dataset Source**: `income_evaluation.csv` (You must upload it to your Google Drive before running the notebook).

---

## Setup and Installation

### Using Google Colab
1. Open the provided notebook file (`RF_Model.ipynb`) in Google Colab.
2. Upload your dataset (`income_evaluation.csv`) to Google Drive.
3. Replace the dataset path in the notebook with the path to your dataset in Google Drive:
   ```python
   df = pd.read_csv('/content/drive/My Drive/your_dataset_path/income_evaluation.csv')
