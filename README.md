# SARIMA Precipitation Predictions for Charlottesville, VA


## contents:

This GitHub repository was put together by Philip Yao, Chris Kim, and Jessica Li. It contains source data, code, and output charts to analyze precipitation time series data for Charlottesville, VA.

### Section 1: Software and Platforms

- software: VS Code, Python Version 3.12.4

- add-on packages: numpy, pandas, matplotlib, seaborn, sklearn, statsmodels

- platform: mac
  

### Section 2: Documentation Hierarchy

- ds4002-project-2: Root Directory, Contains the following folders and files:

- ds4002-project-2/DATA: 
contains original dataset, cleaned dataset, and appendix

- ds4002-project-2/SCRIPTS: 
contains code used to clean and analyze precipitation data

- ds4002-project-2/OUTPUT: 
contains EDA plots and forecast outputs

### Section 3: Instructions for Reproducability

- Install VS Code and Python Version 3.12.4

- Clone the git repository if working on google colab

- In the terminal, pip install numpy, pandas, matplotlib, seaborn, sklearn, statsmodels; these are the necessary packages to perform the analysis

- If you are running on an m1 mac, you need to first install anaconda and conda, and then run this in the terminal: conda install conda-forge::statsmodels

- Install the jupyter extension in VSCode

- Run the code-2.ipynb file to perform the time series analysis

### References:

[1] N. US Department of Commerce, “Climate,” www.weather.gov. https://www.weather.gov/wrh/Climate?wfo=lwx
