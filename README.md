
# Building Heating Load Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
</p>

## About the Project

This project investigates the relationship between the physical characteristics of buildings and their heating energy requirements through **Simple Linear Regression**.

The main objective is to develop a statistical model capable of estimating the heating load of buildings based on their total height, exploring the application of statistical methods and supervised machine learning.

## Dataset

The project uses the **Energy Efficiency Dataset**, available through the UCI Machine Learning Repository.

Dataset characteristics:

- **768 observations**
- **10 variables**
- **8 input variables**
- **2 output variables**

Dataset source: [UCI Machine Learning Repository – Energy Efficiency](https://archive.ics.uci.edu/dataset/242/energy+efficiency)

## Variables Selected

The analysis focuses on two variables:

| Variable | Description | Role |
|---|---|---|
| X5 | Overall Height | Independent Variable (X) |
| Y1 | Heating Load | Dependent Variable (Y) |

## Methodology

The project follows these main steps:

1. **Data Exploration:** Understanding the dataset and its variables.
2. **Data Preparation:** Selecting the variables required for the analysis.
3. **Train-Test Split:** Dividing the dataset into training (80%) and testing (20%) sets.
4. **Model Implementation:** Applying Simple Linear Regression using Scikit-learn.
5. **Model Evaluation:** Comparing actual and predicted values using evaluation metrics.

## Technologies and Tools

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Results and Analysis

This section presents the results obtained from the regression model, including:

- Estimated regression equation.
- Scatter plot and regression line.
- Comparison between actual and predicted values.
- Model evaluation using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

*Results and visualizations will be added after the model implementation.*

## Repository Structure

```text
building-heating-load-prediction/
│
├── data/
│   └── energy_efficiency.csv
│
├── notebooks/
│   ├── exploratory_data_analysis.ipynb
│   └── simple_linear_regression.ipynb
│
├── images/
│   └── results/
│
├── results/
│
├── README.md
└── requirements.txt
```

## Authors

This project was developed collaboratively as part of the Probability and Statistics course.

<!-- Add the contributors' GitHub profiles here -->

- [Estefane Tainá Pallaro](https://github.com/estefanepallaro)
- [Gustavo Augusto Guimarães de Azevedo](https://github.com/gustavoguimaraes1)
- [Helena Vinhote Dias](https://github.com/HelenaVinhote)

## Academic Context

Developed as an academic project for the Probability and Statistics course, exploring the application of linear regression in building energy efficiency analysis.
