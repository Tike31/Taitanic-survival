##Titanic Survival Prediction Project

##Overview

This project leverages machine learning to predict the survival of passengers on the Titanic. Using the famous Titanic dataset, we apply various machine learning algorithms to understand which factors contributed most to passenger survival.

##Table of Contents

 Installation
 Usage
 Dataset
 Features
 Modeling
 Results
 Contributing

Installation
 Clone the repository:
 bash
 Copy code
 git clone https://github.com/Tike31/titanic-survival-prediction.git

Navigate to the project directory:
 bash
 Copy code
 cd titanic-survival-prediction
 Install the required dependencies:
 bash
 Copy code
 pip install -r requirements.txt
 Usage
 Run the Jupyter Notebook to explore and train the models:
 bash
 Copy code
 jupyter notebook titanic_survival_prediction.ipynb
 Alternatively, you can execute the script directly:
 bash
 Copy code
 python main.py
##Dataset
 The dataset used in this project is the Titanic dataset, which can be downloaded from Kaggle. Ensure that the dataset files (train.csv and test.csv) are placed in the data/ directory.

##Features
 PassengerId: Unique ID for each passenger
 Survived: Survival status (0 = No, 1 = Yes)
 Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
 Name: Passenger name
 Sex: Passenger sex
 Age: Passenger age
 SibSp: Number of siblings/spouses aboard the Titanic
 Parch: Number of parents/children aboard the Titanic
 Ticket: Ticket number
 Fare: Passenger fare
 Cabin: Cabin number
 Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

##Modeling
We explore and compare several machine learning algorithms including:

 Logistic Regression
 Decision Trees
 Random Forest
 Support Vector Machine
 K-Nearest Neighbors
 Each model is evaluated using cross-validation and performance metrics such as accuracy, precision, recall, and F1-score.

##Results
 The final model achieves an accuracy of XX% on the test set. The most significant features contributing to survival prediction are:

 Sex
 Age
 Pclass
 Fare
 Embarked
 Contributing
 Contributions are welcome! Please fork this repository and submit a pull request.

##Fork the repository
 Create your feature branch (git checkout -b feature/AmazingFeature)
 Commit your changes (git commit -m 'Add some AmazingFeature')
 Push to the branch (git push origin feature/AmazingFeature)
 Open a pull request
