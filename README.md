# Wine-Quality-prediction

Wine Quality Prediction
This project aims to predict the quality of wine based on several physicochemical features. The dataset used for this project contains various features of wine, and the quality is predicted using machine learning algorithms such as Support Vector Machine (SVM) and Random Forest.

Table of Contents
Project Overview
Dataset
Installation
Usage
Models Used
Results
Contributing
License
Project Overview
Wine quality is rated on a scale of 0 to 10, where 0 is the lowest quality and 10 is the highest. The goal of this project is to build a classification model that can predict whether a wine is of good quality based on its physicochemical properties.

Features
Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Quality (Target variable)
Dataset
The dataset used for this project is the Wine Quality dataset from the UCI Machine Learning Repository, which contains data for both red and white wines. The dataset includes 11 features related to the chemical properties of wine, along with the target variable 'quality'.

Wine Quality Dataset (UCI)
Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/Adityagnss/Wine-Quality-prediction.git
Navigate to the project directory:
bash
Copy code
cd Wine-Quality-prediction
Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Usage
After setting up the environment, you can run the notebook to train and evaluate the model:

bash
Copy code
jupyter notebook
Open the Wine_Quality_Prediction.ipynb file in Jupyter and follow the steps to explore the data, preprocess it, and train the model.

Key files in the project:
Wine_Quality_Prediction.ipynb: The Jupyter Notebook containing the entire analysis, from data preprocessing to model training and evaluation.
requirements.txt: Contains the list of Python libraries required to run the project.
Models Used
This project employs the following machine learning models for wine quality prediction:

Support Vector Machine (SVM): A linear classifier to separate wine qualities based on features.
Random Forest: An ensemble learning method based on decision trees, which improves accuracy by averaging multiple decision trees.
Results
The performance of the models is evaluated based on accuracy, precision, recall, and F1-score. Below are the results of the models used:

Model	Accuracy	Precision	Recall	F1 Score
SVM (Linear Kernel)	XX%	XX	XX	XX
Random Forest (n=100)	XX%	XX	XX	XX
Note: Replace the "XX" with actual results obtained after running the models.

Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
