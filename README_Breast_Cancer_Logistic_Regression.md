# Breast Cancer Classification using Logistic Regression

## Project Overview
This university coursework project trains a Logistic Regression model on the `breast_cancer.csv` dataset and demonstrates predictions through Gradio and Flask interfaces.

## Dataset Labels
- `Class = 2`: Benign (mapped to 0 for model training)
- `Class = 4`: Malignant (mapped to 1 for model training)

## Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Logistic Regression
- Gradio
- Flask
- pyngrok (for exposing the Flask app from Google Colab)

## Files
- `Breast_Cancer_Logistic_Regression_Gradio_Flask.ipynb`: step-by-step notebook
- `breast_cancer.csv`: dataset
- `breast_cancer_logistic_regression.py`: Python script version of the model and interfaces
- `README.md`: project documentation

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the libraries in the first code cell.
3. Upload `breast_cancer.csv` when prompted.
4. Run the notebook cells in order.
5. The Gradio interface will provide a share link. The Flask section uses an ngrok token to create a public link in Colab.

## Model Evaluation
The notebook reports accuracy, ROC-AUC, a classification report, and a confusion matrix on a held-out test set.

## Disclaimer
This project is for educational purposes only. It is not a medical diagnostic tool and must not be used to make healthcare decisions.
