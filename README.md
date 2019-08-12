# Disaster Response Pipeline Project
Data Science udacity project

The Project is divided in the following :

1- Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure

2- Machine Learning Pipeline to train a model able to classify text message in categories

3- Web App to show model results in real time.

## Getting Started

1- Run the following commands in the project's root directory to set up your database and model.

* To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
* To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

2- Run the following command in the app's directory to run your web app. python run.py

3- Go to http://0.0.0.0:3001/

### Installing

Clone this GIT repository:

git clone https://github.com/SaudAlmajed/Disaster-Response-Pipelines.git



## Built With
- Python 3.5+ (I used Python 3.7)
- Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
- Natural Language Process Libraries: NLTK
- SQLlite Database Libraqries: SQLalchemy
- Web App and Data Visualization: Flask, Plotly


## Acknowledgments

Udacity for providing such a complete Data Science Nanodegree Program

