Using R Studio to
explores the use of ML algorithms — Decision Tree, KNN, and Linear Regression to classify websites as malicious or benign. All models are implemented using R’s caret package, which provides a unified framework for model training, tuning, and evaluation. 
The dataset includes features such as URL structure, server metadata, and TCP/IP behaviors. The classification models are trained with a 9:1 train-test split and evaluated using accuracy, recall, and F1-score. 
The target variable is TYPE, where 1 denotes a malicious website and 0 indicates a benign one. Data preprocessing was performed using R, primarily with the caret package. Missing values were identified and handled through omission or imputation, and categorical variables such as CHARSET, SERVER, and WHOIS_COUNTRY were converted into factor types.
Using the caret package in R, the dataset is then split into training (90%) and testing (10%) sets. Three machine learning models—Decision Tree, KNN, and Linear Regression—are trained on the training data. 






