Code files:
-Exploratory data analysis:
  -EDA.ipynb
-Classification models:
  -LogisticReg.ipynb
  -XGBoost.ipynb
-Clustering model:
  -Clustering.ipynb

Data files:
-Original data files:
  -census-bureau.columns
  -census-bureau.data
-Generated data files: 
  -pre_split_data.pkl

EDA.ipynb requires the two original data files.
Running the entire EDA.ipynb would generate the generated data file -- pre_split_data.pkl
All three other notebooks (LogisticReg.ipynb, XGBoost.ipynb, Clustering.ipynb) require the generated data file.
