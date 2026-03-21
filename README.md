# DS4002_Project1
## Section 1: Software and platform section
- Type of Software: Integrated Development Environment (IDE) / Interactive Computing Platform / Web-based notebook environment
- Packages installed: numpy, pandas, matplotlib, seaborn, os, statsmodel, scikitlearn
- Platform: Cloud-based (SaaS)

## Section 2: A Map of your documentation
```

DS4002_Project2/
│
├── README.md
├── LICENSE.md
│
├── DATA/
│   ├── net worth by quarter.csv
│   ├── net_worth_cleaned.csv
│   ├── README_net_worth.txt
│   ├── README_unemployment.txt
│   ├── unemployment by month.csv
│   ├── unemployment_cleaned.csv
│   └── Project 2 - Data Appendix.pdf
│
├── SCRIPTS/
│   ├── Data Cleaning.ipynb
│   ├── EDA_unemployment.ipynb
│   ├── EDA_wealth_differences.ipynb
│   ├── Predictive Analysis.ipynb
│   └── Unemployment_and_Net_Worth_Correlation.ipynb
│
└── OUTPUT/
    ├── ARIMA_percent_error_prediction.png
    ├── ARIMA_predicted_vs_actual.png
    ├── net_worth_over_time.png
    ├── normalized_unemployment_net_worth.png
    ├── regression_predicted_vs_actual.png
    ├── rolling_correlation.png
    ├── unemployment_20-24.png
    ├── unemployment_histograms.png
    └── unemployment_over_time.png

```
## Section 3: Instructions for reproducing results
This section will cover the order in which code files may be executed or created if remaking from scratch. The organization of this repository will not be included in this section, as the layout is already described in detail in Section 2 above. Specific code chunks should be referenced for a detailed understanding of model creation and execution. All code contains some combination of in-line comments and headers.

### To Reproduce Results:
1. Download repository on a local/cloud machine and ensure all data files are copied correctly.
2. If the processed data is downloaded proceed to step 3. If not, run `Data Cleaning.ipynb` and check that the file names and relative path match your instance of the repository. This is also where separate data files with different unemployment/wealth data could be susbstituted into the analysis. If this is the case, more code alterations may be required to create a conforming dataset (ex. changing existing column names).
3. Run the `Unemployment_and_Net_Worth_Correlation.ipynb` file to start the analysis, and `Predictive Analysis.ipynb` to create the predictive models. 

### To Recreate Code and Model:
1. Start with a 2 datasets containing unemployment data and net worth data. The speicficity of the data and time period is up to the project.
2. Perform any EDA deemed necessary, although this group's EDA may be used in substitution for your own.
3. Recreate the data preprocessing script, focusing on removing NAs, renaming columns, adjusting time ranges, and ensuring an equal time interval (ex. quarters).
4. Save the cleaned and processed dataframes as .csv files in the "Data" folder.
5. Create an analysis script and import all relevant packages.
6. Examine correlations between your data sets. Perform a rolling pearson correlation by following our code. Make sure to pick an appropriate window size based on what trends you want to examine and the size of your dataset.
7. Create a prediction script and import all relevant packages. 
8. Perform a linear regression, seeing if unemployment data can predict net worth changes. Observe statistics (RMSE, R squared, etc.) and create graphs for visual analysis.
9. Peform an ARIMA prediction, seeing if unemployment data can predict net worth changes. Observe statistics (RMSE, % error, etc.) and create graphs for visual analysis.
10. Finally, compare the performance of the models. Additional validation can be done by trying different train/test boundaries and ARIMA inputs, as well as training/testing/applying the model to larger datasets.


## References 
[1] “Wealth inequality in America just hit its widest gap in more than 3 decades,” CBS News, https://www.cbsnews.com/news/us-wealth-gap-widest-in-three-decades-federal-reserve/ (accessed Feb. 25, 2026).   
[2] C. Rugaber, “Here’s why everyone’s talking about a ‘K-shaped’ economy,” AP News, https://apnews.com/article/kshaped-economy-spending-income-inequality-dfa59144ecb2e1b674242666e28ff556 (accessed Feb. 25, 2026).  
[3]  “Pearsonr,” SciPy v1.17.0 Manual, https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.pearsonr.html (accessed Feb. 25, 2026).  
[4] GeeksforGeeks, “How to calculate rolling correlation in python?,” GeeksforGeeks, https://www.geeksforgeeks.org/python/how-to-calculate-rolling-correlation-in-python/ (accessed Feb. 25, 2026).  
[5] A. Hayes, “Master Arima: Your guide to time series forecasting,” Investopedia, https://www.investopedia.com/terms/a/autoregressive-integrated-moving-average-arima.asp (accessed Feb. 25, 2026).  
[6] “Unemployment rate - 20 yrs. & over,” FRED, https://fred.stlouisfed.org/series/LNS14000024 (accessed Mar. 16, 2026).  
[7] “Release Tables: Levels of Wealth by Wealth Percentile Groups,” FRED, https://fred.stlouisfed.org/release/tables?eid=813668&rid=453 (accessed Mar. 16, 2026).   
