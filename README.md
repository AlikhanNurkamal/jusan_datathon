# JUSAN BANK DATATHON, TEAM EVEREST
This is the repository of EVEREST's team for the Datathon case by Jusan Bank.

# Overall
The main model code is in the `jusan-model.ipynb` notebook, so only it matters during the testing process.

# Exploratory Data Analysis
The `data-preprocessing.ipynb` notebook contains all code that has been used to clean, preprocess, and prettify the original dataset. It does not contain any models that have been used to predict customers' labels.

EDA included:
* Working with NaN values
* Handling outlier values
* Augmenting new columns for better classification
* Excluding logically incorrect rows
* Data normalization

After the proper EDA analysis, several models, such as Logistic Regression, Decision Tree, Random Forest, XGBoost, Support Vector Machines Classifier, etc. have been used to observe their accuracy of working with the clean dataset. Moreover, some oversampling and undersampling techniques (`SMOTE`, `ADASYN`, `RandomUnderSampling`) have been used in order to handle the problem of imbalanced dataset. With all that work, all models performed poorly, so we decided to exclude them from the notebooks. After that we moved on to Tree-based boosting models that handle all of the above-mentioned problems (imbalanced dataset, scaling, missing values) internally.

# Models
Different models have been used for the classification problem presented by Jusan Bank. Some of them are stored in the `jusan-model.ipynb` notebook. The best performed model was `XGBoost Classifier` with its f1-score on Kaggle of `0.73`. The XGBoost Classifier model automatically (internally) handles missing values, scaling, and normalization of the dataset.

# Credits
We express our appreciation to GDSC NU Community for organizing such an interesting Datathon and thank Jusan Bank for such an exciting case. The competition can be found <a href="https://www.kaggle.com/competitions/gdsc-nu-datathon-jusan-bank-case-competition">here</a>.
