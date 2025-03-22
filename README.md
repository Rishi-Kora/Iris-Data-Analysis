# Iris-Data-Analysis
This project aims to build a machine learning model for classifying Iris flowers into their respective species (Setosa, Versicolor, or Virginica) based on their sepal and petal measurements. The project utilizes the famous Iris dataset, a classic dataset in machine learning and statistics.<br>

Methodology:<br>

1. Data Loading and Preprocessing: The Iris dataset is loaded, and data preprocessing steps are performed, including handling missing values (if any), removing duplicates, and converting categorical species labels into numerical values using Label Encoding.<br>

2. Exploratory Data Analysis: Data exploration techniques such as descriptive statistics, correlation analysis, pair plots, box plots, and violin plots are used to visualize the data and gain insights into feature relationships and distributions.<br>

3. Feature Engineering: The project uses all four features (sepal length, sepal width, petal length, petal width) as input for the model. Data scaling is applied using StandardScaler to standardize the features.<br>

4. Model Selection: The project employs the K-Nearest Neighbors (KNN) algorithm as the classification model. The KNN algorithm is a simple and effective method for this type of classification task.<br>

5. Model Training and Evaluation: The KNN model is trained on a portion of the data and evaluated on a separate test set. Metrics such as accuracy, classification report, and confusion matrix are used to assess the model's performance.<br>

6. Outlier Removal: Outliers are identified and removed using z-score analysis to improve model accuracy.<br>

Dataset Link: https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data
Feel free to download the code and data.
