Data Analysis and AI Fundamentals — Final Assessment
Three Jupyter notebooks covering introductory data analysis and machine learning.
Notebooks
1. Question 1 — Population Analysis: 2022 population distribution; historical population trends (2000–2020); 2020 GDP/population correlation (0.58 in the analysis).
2. Question 2 — Titanic Classification: Logistic Regression (77.09% accuracy) and Random Forest (83.24% accuracy), with confusion matrices and classification reports.
3. Question 3 — Customer Clustering: Data exploration, standardization, Elbow Method and four K-Means customer segments.
Required data files
Place these CSV files in the same directory as the notebooks:
- POP.csv
- Titanic.csv
- Mall_Customers.csv
- The World Bank population CSV with a name beginning API_SP.POP.TOTL and ending .csv
- The World Bank GDP CSV with a name beginning API_NY.GDP.MKTP.CD and ending .csv
The original POP.csv was supplemented with historical World Bank population and GDP datasets because it did not contain the requested time series or GDP figures.

Sources: World Bank population and World Bank GDP.
Running the notebooks
Install Python packages pandas, numpy, matplotlib, seaborn, scikit-learn, and jupyter. Open each notebook in Jupyter and select Restart & Run All. Keep the CSV files beside the notebooks so relative file paths work.
Notes
Notebook outputs were retained from the original analysis. The World Bank file-loading cells in Question 1 were adapted to portable relative paths; rerun Question 1 with the CSV files present to regenerate those cells' outputs.
