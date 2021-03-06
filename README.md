# Flight Price Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Technologies Used](#technologies-used)
  * [Directory Tree](#directory-tree)


## Demo
Link: [https://flight-fare--predict.herokuapp.com//](https://flight-fare--predict.herokuapp.com//)

## Overview
This is a Flask web app which predicts price of Flight ticket.

## Installation
The Code is written in Python.If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Technologies Used

[<img target="_blank" src="https://unixcop.com/wp-content/uploads/2021/03/Flask.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://www.projectdatascience.com/wp-content/uploads/2020/11/Python-Jupyter-Sklearn-images-transparent-background-white-letters-1024x803.png" width=200>](https://scikit-learn.org/stable/) 

## Directory Tree
```
├── Images
│   ├── Flowchart.png
│   ├── Screenshots(1-6)
├── static 
│   ├── css
│   ├── photo.jpg
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```
