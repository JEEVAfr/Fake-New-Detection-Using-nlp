# Fake News Detection
This Python script uses machine learning to detect fake news in text.
## Usage
*Clone the Repository*: Clone the GitHub repository to your local machine using the following command:

git clone https://github.com/JEEVAfr/Fake-New-Detection-Using-nlp.git

## Installation

The required libraries for this project can be installed using pip:

##Dependencies:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

1. Install Dependencies: Make sure you have Python 3.x and the required Python packages installed. You can install the dependencies using pip:

>> pip install pandas numpy scikit-learn matplotlib seaborn

2. Run the Script: Execute the Jupyter file containing the fake news detection script:

>> python Fake News Detection Using NLP.ipynb
## Usage

The main script is a Jupyter notebook. You can run the notebook using Jupyter. Make sure you have the ‘Fake.csv’ and ‘True.csv’ datasets in your working directory.

The notebook includes the following steps:

- Data loading and preprocessing
- Text cleaning and normalization
- Feature extraction with TF-IDF Vectorizer
- Model training (Logistic Regression, Decision Tree Classifier, Gradient Boosting Classifier, Random Forest Classifier)
- Model evaluation
- Manual testing function


Enter News Article for Testing: The script will prompt you to enter a news article. After inputting the text, the program will classify it as "Fake News" or "Real News" based on the trained machine learning model.
## Output:
The program produces an output by classifying the input news article as "Fake News" or "Real News" based on the machine learning model. You will see the classification result in the console or terminal after entering the news article.
