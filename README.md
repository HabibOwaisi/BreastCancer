# Breast Cancer Prediction :microscope:

## Project Overview :page_facing_up:
This project aims to build and compare various machine-learning models to predict breast cancer from diagnostic data. Utilizing Python and several machine learning libraries, we've implemented models like Decision Trees, k-Nearest Neighbors (kNN), and Gaussian Naive Bayes to classify tumours as benign or malignant based on features extracted from images.

## Dataset :floppy_disk:
The dataset used in this project comes from the Wisconsin Breast Cancer Database (WBCD). It includes features like the mean radius of the tumour, texture, perimeter, area, smoothness, and more.

## Models and Techniques :bar_chart:
- **Decision Tree Classifier**: Utilized with both Gini Index and Entropy.
- **k-Nearest Neighbors**: Applied with hyperparameter tuning to find the optimal number of neighbors.
- **Gaussian Naive Bayes**: Implemented for its simplicity and effectiveness in classification tasks.
- **Support Vector Machines (SVM)**: Explored with different kernels and used GridSearchCV for parameter tuning.
- **Principal Component Analysis (PCA)**: Performed dimensionality reduction to improve model efficiency.

## Model Evaluation and Visualization :chart_with_upwards_trend:
- **ROC Curves**: Compared the Receiver Operating Characteristic curves to evaluate model performance.
- **Learning Curves**: Generated to understand the training process and identify any overfitting or underfitting.
- **Confusion Matrices**: Provided detailed breakdowns of model predictions to evaluate true positives, false positives, true negatives, and false negatives.

## Model Interpretability :mag:
- **SHAP Values**: Used to interpret the impact of features on model predictions.
- **LIME**: Implemented to provide local interpretable model-agnostic explanations.

## Libraries Used :books:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `shap`
- `lime`

## Installation and Usage :wrench:
Clone the repository and install the required libraries to get started with the project:
```bash
git clone https://github.com/<HabibOwaisi>/<BreastCancer>.git
cd <BreastCancer>
pip install -r requirements.txt

Contributing :handshake:
Contributions, issues, and feature requests are welcome! Feel free to check issues page.

License :scroll:
Distributed under the MIT License. See LICENSE for more information.

Contact :phone:
Your Name – @HabibOwaisi – owaisihabib300@gmail.com
Project Link: https://github.com/<HabibOwaisi>/<BreastCancer>
