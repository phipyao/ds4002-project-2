SARIMA Precipitation Predictions for Charlottesville, VA
contents:
This GitHub repository was put together by Philip Yao, Chris Kim, and Jessica Li. It contains source data, code, and output charts to analyze precipitation time series data for Charlottesville, VA.

Section 1: Software and Platforms
software: VS Code, Python Version 3.12.4

add-on packages: numpy, pandas, matplotlib, seaborn, sklearn, statsmodels

platform: mac

Section 2: Documentation Hierarchy
ds4002-project-2: Root Directory, Contains the following folders and files:

ds4002-project-2/DATA: 

cleaned precipitaiton data.csv          cville monthly precip total v2.csv      cville_monthly_precip_total.csv

ds4002-project-2/SCRIPTS: 

code.ipynb                              code-2.ipynb

ds4002-project-2/OUTPUT: 

Annual Precipitation by Year.png                Precipitation Month.png                         SARIMA Plot Diagnostics.png
Autocorrelation.png                             SARIMA Model Evaluation.png                     Seasonality Checker.png
Density and Residuals.png                       SARIMA Model Forecast.png                       Total Precipitation by Month from 1901.png
Partial Autocorrelation.png                     SARIMA Model Future Forecast Only.png

Section 3: Instructions for Reproducability
Install VS Code and Python Version 3.12.4

Clone the git repository

In the terminal, pip install numpy, pandas, matplotlib, seaborn, sklearn, statsmodels

If you are running on an m1 mac, you need to first install anaconda and conda, and then run this code: conda install conda-forge::statsmodels

Install the jupyter extension in VSCode

Run the code.ipynb file

References:
[1] “Email Spam Detection 98% Accuracy,” kaggle.com. https://www.kaggle.com/code/mfaisalqure
