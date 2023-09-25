# matplotlib_challenge

This challenge is to analyze hypothetical pharmaceutical data from a company that ran an animal trial for potential treatments for squamous cell carcinoma (SCC). The goal is to generate various tables and figures as well as a top-level summary based on the results

Repository contains one folder called 'Pymaceuticals' which contains two items:
  - a subfolder named 'data' which has the raw data from the study to be analyzed
  - a Jupyter Notebook file (ipynb) called 'pymaceuticals_final' which is used for the actual analysis and plot generation 

## References Used:

(1) Check for duplicate values using 'dupliacted' method in pandas: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html

(2) Use 'isin' method to filer the dataframe using loc based on a list of values instead of just one: https://www.geeksforgeeks.org/python-pandas-dataframe-isin/

(3) Use 'quantile' function in pandas to pull the Q1 and Q3 values directly from a series: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.quantile.html

(4) matplotlib documentation on boxplots to help format them: https://matplotlib.org/stable/gallery/statistics/boxplot_demo.html