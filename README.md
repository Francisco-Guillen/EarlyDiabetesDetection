# Early Diabetes Detection
This project consists of an interactive web application for early diabetes detection. It utilizes a logistic regression model to predict the probability of diabetes based on user-provided symptoms.

## Prerequisites
- Numpy
- Pandas
- Scikit-learn
- Xgboost
- Matplotlib
- Seaborn
- Joblib
- Shiny

## How to run
1. Clone this repository.
2.  Install dependencies: pip install -r requirements.txt.
3.  Download the dataset from [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/529/early+stage+diabetes+risk+prediction+dataset).
4.  Execute the cells of Early_Diabetes_Detection.ipynb sequentially to reproduce the analysis and train the model.
5.  Run the application: shiny run --reload app.py
6.  Access the application in your web browser at: http://127.0.0.1:8000

## User Interface
The application interface consists of a series of input controls, where the user can provide information related to symptoms associated with diabetes, such as polyuria, polydipsia, age, gender, among others.
After providing the data, the user can click the "Predict" button to obtain the probability of diabetes calculated by the model.

<p align="center">
<img src="https://github.com/Francisco-Guillen/EarlyDiabetesDetection/assets/83434031/22519591-2b30-4f96-9201-11cb1b4d2c5a")
">
<br>
  Figure 1: Web Application Example
</p>   

## Refferences
- Early Stage Diabetes Risk Prediction. (2020). UCI Machine Learning Repository. [https://doi.org/10.24432/C5VG8H](https://doi.org/10.24432/C5VG8H)
- [Diabetes Prediction Using Machine Learning](https://www.youtube.com/watch?v=tK8PGomidp8&t=324s)
- [Early Diabetes Detection Web App Using Shiny for Python](https://www.youtube.com/watch?v=oTc1yVZlrIU&t=1265s)
