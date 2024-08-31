# Titanic-Survival-Prediction
This project is focused on predicting the survival of passengers on the Titanic using machine learning. The dataset used is the well-known Titanic dataset, which includes information on the passengers, such as their age, sex, ticket class, and whether they survived the disaster.

Table of Contents
Project Overview
Dataset
Project Structure
Installation
Usage
Features
Visualization
Contributing
License
Project Overview
This project involves the following key steps:

Data collection and preprocessing.
Exploratory data analysis (EDA).
Building a logistic regression model to predict survival.
Evaluating the model's performance.
Dataset
The dataset used in this project is the Titanic dataset, which can be found in the train.csv file. It contains the following features:

PassengerId: Unique ID of the passenger.
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
Name: Name of the passenger.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard the Titanic.
Parch: Number of parents/children aboard the Titanic.
Ticket: Ticket number.
Fare: Passenger fare.
Cabin: Cabin number (with many missing values).
Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Survived: Survival status (0 = No, 1 = Yes).
Project Structure
titanic_survival_prediction/
│
├── train.csv                      # The dataset used for training
├── titanic_survival_prediction.ipynb  # Jupyter Notebook with the code
├── README.md                      # Project documentation
Installation
Clone the repository:
git clone https://github.com/yourusername/titanic_survival_prediction.git
Navigate to the project directory:
cd titanic_survival_prediction
Install the required dependencies:
pip install -r requirements.txt
Usage
To run the project and see the results:

Open the titanic_survival_prediction.ipynb Jupyter Notebook.
Run all the cells to execute the data analysis, model training, and evaluation steps.
Alternatively, you can run the notebook directly in a Jupyter environment or Google Colab.

Features
Data Cleaning: Handling missing values and removing unnecessary columns.
Exploratory Data Analysis: Understanding the distribution of data and key insights.
Model Training: Logistic regression model to predict survival.
Visualization: Data visualization using Seaborn and Matplotlib.
Visualization
Several visualizations are included in the notebook to help understand the distribution of data and the relationships between different features:

Count plots of survival based on gender and class.
Distribution plots for numerical features like age and fare.
Contributing
Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

