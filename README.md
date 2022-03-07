# Card Detection using Detectorn2 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Model perfomance](#model-perfomance)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)




[![](https://i.imgur.com/AML6dS0.jpg)](https://fuel-efficiency-prediction557.herokuapp.com/)
[![](https://i.imgur.com/nqq2s7R.jpg)](https://fuel-efficiency-prediction557.herokuapp.com/)


## Overview
This is a Flask web app which detects playing cards in an image and its type.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning and Deep Learning models to get most out of it. I came to know mathematics behind Object detection. Finally it is important to work on application (real world application) to actually make a difference.

## Model perfomance
[![](https://i.imgur.com/kAl4Dj4.jpg)]

######'AP': 78.96951049434418, 
######'AP50': 83.33333333333334, 
######'AP75': 83.33333333333334, 
######'APm': 78.53960396039604, 
######'APl': 79.08863275331461, 
######'AP-jack': 95.35140855560782, 
######'AP-king': 90.03201819942032, 
######'AP-nine': 96.97337569507918, 
######'AP-queen': 95.59219897112729, 
######'AP-ten': 95.86806154483044, 


## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── .circleci 
│      ├── config.yml
├── com_ineuron_utils 
│      ├── __init__.py
       ├── utils.py
├── tests 
│      ├── __init__.py
       ├── test_script.py       
├── templates
│      ├── index.html
├── Procfile
├── README.md
├── main.py
├── config.yml
├── Dockerfile
├── faster_rcnn_R_50_FPN_3x.yaml
├── ObjectDetector.py
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://curiousily.com/static/dff66fd0972574ae284f7df9533d369f/3e3fe/detectron2-logo.png" width=280>](https://detectron2.readthedocs.io/en/latest/)  



