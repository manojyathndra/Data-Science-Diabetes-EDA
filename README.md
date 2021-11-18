The goal of this project is to understand the logic and methods of exploratory data analysis (EDA).
The mode of analysis concerned with discovery, exploration, and empirically detecting phenomena in
data. EDA has become the default pre-modeling step for every Machine Learning project engagement.
Exploratory Data Analysis (EDA) is a way to investigate datasets and find preliminary information, insights,
or uncover underlying patterns in the data. Instead of making assumptions, data can be processed in a
systematic method to gain insights and make informed decisions.
Investigate the data by utilizing NumPy, Pandas, any graph library (MatPlotlib, Seaborn, Plotly), and
Python’s Statsmodel modules.
The analysis of the data should be focus on predicting the progression of a disease (diabetes in our case).
Get the data from Stanford U’s Machine Learning Repository:
https://web.stanford.edu/~hastie/Papers/LARS/diabetes.data

For some background information on the data, see this seminal paper:
Bradley Efron, Trevor Hastie, Iain Johnstone and Robert Tibshirani (2004) "Least Angle Regression," Annals
of Statistics (with discussion), 407-499.
https://projecteuclid.org/euclid.aos/1083178935
Load the dataset by using NumPy’s genfromtxt function (you are allowed to use others…)
https://numpy.org/devdocs/user/basics.io.genfromtxt.html
NOTE: You do NOT build/select a model, you only perform deep-dive analysis on the data.
Write Python scripts in order to complete the following tasks along with their output. All work should be
done and submitted in a single Jupyter Notebook.
1- Prep the data in order to be ready to be fed to a model.
Look for missing, null, NaN records.
Find outliers.
Transform data – all entries should be numeric.
2- List all types of data, numeric, categorical,…
3- Perform EDA on data.
Present dependencies and correlations among the various features in the data.
List the most variables (Feature Importance) that will affect the target label.
4- State limitations/issues (if any) with the given dataset.
