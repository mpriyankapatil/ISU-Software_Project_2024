TITLE: 
DETECTION OF PHISHING WEBSITE USING MACHINE LEARNING MODEL BASED ON URL ANALYSIS.

GENERAL DESCRIPTION:
This project aims to develop a machine learning model to effectively detect phishing websites through URL analysis. Utilizing the Gradient Boosting Classifier, the project will focus on differentiating between legitimate and phishing URLs by analyzing their distinct characteristics. This includes examining the linguistic and aesthetic features of URLs commonly employed in phishing attacks. The project will leverage a dataset comprising both phishing and legitimate URLs to train and test the model, ensuring a robust and accurate classification system.


FEATURES:
Uses 30 different features extracted from URLs, including SSL final State, URL Anchor, Prefix Suffix, etc.
Analyzes and visualizes data to understand feature importance and distributions.


MODELS EVALUATED:
Logistic Regression
K-Nearest Neighbors
Support Vector Machine
Naive Bayes
Decision Tree
Random Forest
Gradient Boosting Classifier
Multi-layer Perceptron


INSTALLATION:
Clone this repository to your local machine:
git clone https://github.com/mpriyankapatil/ISU-Software_Project_2024.git

INSTALL REQUIRED PACKAGES:      
pip install -r requirements.txt


USAGE:
Run the Flask app:
python app.py
Navigate to http://localhost:5000 in your web browser to interact with the application.

DATA:
The dataset used for this project contains over 11,000 labeled examples of phishing and legitimate URLs, sourced from Kaggle.

RESULTS:
The Gradient Boosting Classifier and Random Forest models showed the most promising results, achieving accuracies above 95% after cross-validation.

FUTURE WORK:
Integrate more sophisticated feature engineering techniques.
Explore deep learning models for potentially better performance.
Develop a real-time phishing detection browser extension.

CONTRIBUTING:
Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.


CONTACT:
For any queries, please reach out to ppatil2@sycamores.indstate.edu

