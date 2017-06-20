# Feature Selection and Classification on a Large Synthetic Dataset

For this project, I used a synthetic dataset that was created based on UCI's Madelon dataset (https://archive.ics.uci.edu/ml/datasets/Madelon). Madelon is a a two-class classification problem that is multivariate and highly non-linear. Of the 500 features, 20 are real features, and 480 are noise features. The dataset I worked with was a much larger version of Madelon. It has 1.1 billion data points – 5,000 features and 220,000 rows - and only 50 features are real, with the rest noise. 

My approach for this project was to a) use statistical techniques to reduce the number of features in the dataset and b) build a predictive model based on this smaller subset of features. I built model pipelines using GridSearch, RandomForestClassifier, SelectKBest, and Logistic Regression to get the best accuracy score I could.

