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
│   └── Data_Appendix.pdf
│
├── SCRIPTS/
│   ├── Data Cleaning.ipynb
│   ├── EDA_unemployment.ipynb
│   ├── EDA_wealth_differences.ipynb
│   └── EDA_wealth_differences.ipynb
│
└── OUTPUT/
    ├── Unemployment_20_24.png
    ├── Unemployment_by_Age_Group.png
    ├── Unemployment_Correlations_by_Age_Group.png
    ├── Unemployment_Descriptive_Stats.png
    ├── Unemployment_Histograms.png
    ├── Wealth_Distribution_Over_Time.png
    ├── Wealth_Difference_Descriptive_Stats.png
    ├── Wealth_Distribution_Bottom_50.png
    ├── Wealth_Distribution_Correlations.png
    ├── Wealth_Distribution_Top_0_1.png
    ├── Wealth_Distribution_Top_1_0.png
    └── Wealth_Distribution_Top_10.png
```
## Section 3: Instructions for reproducing results
This section will cover the order in which code files may be executed or created if remaking from scratch. The organization of this repository will not be included in this section, as the layout is already described in detail in Section 2 above. Specific code chunks should be referenced for a detailed understanding of model creation and execution. All code contains some combination of in-line comments and headers.

### To Reproduce Results:
1. Download repository on a local/cloud machine and ensure all data files are copied correctly.
2. If the processed data is downloaded proceed to step 3. If not, run `Data Cleaning.ipynb` and check that the file names and relative path match your instance of the repository. This is also where separate data files with different unemployment/wealth data could be susbstituted into the analysis. If this is the case, more code alterations may be required to create a conforming dataset (ex. changing existing column names).
3. Run the `analysis.ipynb` file to create and run the models.

### To Recreate Code and Model:
TO DO (also update tree, etc.)




## References 
[1] “Wealth inequality in America just hit its widest gap in more than 3 decades,” CBS News, https://www.cbsnews.com/news/us-wealth-gap-widest-in-three-decades-federal-reserve/ (accessed Feb. 25, 2026).   
[2] C. Rugaber, “Here’s why everyone’s talking about a ‘K-shaped’ economy,” AP News, https://apnews.com/article/kshaped-economy-spending-income-inequality-dfa59144ecb2e1b674242666e28ff556 (accessed Feb. 25, 2026).  
[3]  “Pearsonr,” SciPy v1.17.0 Manual, https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.pearsonr.html (accessed Feb. 25, 2026).  
[4] GeeksforGeeks, “How to calculate rolling correlation in python?,” GeeksforGeeks, https://www.geeksforgeeks.org/python/how-to-calculate-rolling-correlation-in-python/ (accessed Feb. 25, 2026).  
[5] A. Hayes, “Master Arima: Your guide to time series forecasting,” Investopedia, https://www.investopedia.com/terms/a/autoregressive-integrated-moving-average-arima.asp (accessed Feb. 25, 2026).  
[6] “Unemployment rate - 20 yrs. & over,” FRED, https://fred.stlouisfed.org/series/LNS14000024 (accessed Mar. 16, 2026).  
[7] “Release Tables: Levels of Wealth by Wealth Percentile Groups,” FRED, https://fred.stlouisfed.org/release/tables?eid=813668&rid=453 (accessed Mar. 16, 2026).   
