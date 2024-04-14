Name of the Project: Breast Cancer Detection

Tools Used: (Mention the tools used in this project)
● NumPy, Pandas, sklearn machine learning library

Working Procedure:
- Importing essential libraries: The project starts by importing the necessary libraries such as
pandas and numpy.
- Importing Dataset: The dataset used in this project has been obtained from UCL Machine
Learning Repository
- Cleaning the Dataset: The dataset is cleaned by splitting it into training and testing set. We
substitute the missing values by replacing them with the mean of the column data. This
ensures that it is ready for model training.
- Model Training using K-Nearest Neighbors: The KNN algorithm is used in training the
dataset. The sklearn library provides the packages required for importing the
KNeighborsClassifier package used in implementation.
- Model Training using Logistic Regression and Naïve Bayes: The Logistic Regression
algorithm and the Naïve Bayes algorithm is used by importing the LogisticRegression
package and the GaussianNB package respectively.
- Accuracy Score Evaluation: The predicted outputs from the machine learning models are
compared with the actual outputs from the testing set to calculate the accuracy score.
- 10Fold Cross Validation Score: Performed to assess the performance of the model more
accurately. The dataset is split into 10 equal parts and the model is trained and tested 10
time, providing a robust estimate of the model’s performance.
