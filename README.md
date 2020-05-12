# Data-mining-Term-Project

Board Game Review Classifier

Muhammad Arham

1001686912

Term Project, Data Mining, Spring 2020

In this project, we will be working with Board Game reviews dataset, we have acquired from kaggle. In this dataset we have been provided with three files. Our major concern is with the board game review file, which contains user comments and ratings for a game. Our goal is, given the board game review, we have to predict what rating out of 10 it will have.

**Run the notebook, and follow the instructions
Instructions for Deployment:

1. use pickle to dump your model to a 'model.pkl' file
2. similarly use pickle to dump your vectorizer to a 'vectorizer.pkl' file
3. create a new dir named 'Webapp'
4. create two folders: static & template
5. create two html files in the template folders, the home page and the result page
6. in home directory create app.py, requirements.txt, Procfile
7. requirments.txt contains all the imports and libraries required for the project
8. procfile contians the line "web: gunicorn app:app", which tells what the name of the flask app is
9. app.py contains all model and vectorizer dump loaded, taking in the input and sending the output to the results page
10. create a new app in heroku and connect your heroku with your github repository where you have the above mentioned files
11. click deploy branch, after which it will provide you with a url where we can access the model

NOTE: my model and vectorizer dumps were bigger than the github upload file limit. Hence i couldnot deploy my model to heroku

Video Demonstration of my model: https://youtu.be/zVb06ZQbg0c
