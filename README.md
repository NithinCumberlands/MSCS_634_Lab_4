# MSCS_634_Lab_4

Lab Overview:
In this lab, I explored various regression techniques using the Diabetes dataset from sklearn.datasets. The primary objective was to develop models that predict disease progression based on medical features and assess how regularization techniques can minimize overfitting and enhance model performance.

Files Included:
Lab4_Regression_and_Regularization.ipynb: This Jupyter Notebook contains all the code, model implementations, visualizations, and evaluation metrics.

README.md: This file provides an overview of the lab's objectives, insights, challenges, and results.

Objectives:
The main goals for this lab were to:

Implement and compare several regression techniques, including:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression (Degree 2)

Ridge Regression

Lasso Regression

Evaluate the models using the following metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R²)

Visualize predictions and residuals to gather further insights.

Understand how regularization can help manage model complexity and prevent overfitting.

Key Insights:
Multiple Regression performed better than Simple Linear Regression by utilizing all available features.

Polynomial Regression (degree 2) improved accuracy but had potential overfitting concerns, which were addressed in the README.

Ridge and Lasso Regression both proved effective in tackling overfitting. Ridge helped in reducing model variance, while Lasso performed feature selection by shrinking some coefficients to zero.

Regularization was key to enhancing the model's generalization capabilities.

Challenges Faced:
Determining the optimal degree for Polynomial Regression without causing overfitting was challenging.

Tuning and comparing different alpha values for Ridge and Lasso required careful experimentation.

Visualizing the performance of high-dimensional regressions was difficult, so I relied on residual plots and performance metrics for a better understanding.

Technologies Used:
Python 3

Jupyter Notebook

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

How to Run:
Clone or download this repository.

Open the file Lab4_Regression_and_Regularization.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.

Run the cells sequentially to reproduce the results and visualizations.
