# JUSAN BANK DATATHON, TEAM EVEREST
This is the repository of EVEREST's team for the Datathon case by Jusan Bank.

# Exploratory Data Analysis
The `data-preprocessing.ipynb` notebook contains all code that has been used to clean, preprocess, and prettify the original dataset. It does not contain any models that have been used to predict customers' labels.

# Models
Different models have been used for the classification problem presented by Jusan Bank. All of them are stored in the `jusan-model.ipynb` notebook. The best performed model was `XGBoost Classifier` with its f1-score on Kaggle of `0.73`. The XGBoost Classifier model automatically (internally) handles missing values and scaling and normalization of the dataset.
