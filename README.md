# Dog Identification App

## Project Description
This project serves as my capstone project for Udacity's Data Scientist Nanodegree Program, The project aims to classify images of dogs according to their breed using state-of-the-art CNN models. If a human is detected, It will provide an estimate of the dog breed that is most resembling.
 
Finally, A web app was developed to allow users to upload new images as input to detect the corresponding dog breed.

For better understanding of the project, please read [Dog_App] (https://github.com/mbahaay/Dog-Identification-App/blob/main/Dog_App.ipynb)

## Installation
Python 3.6 or above should be used, you’ll need to use Jupyter Notebook and install the following libraries:

1.	numpy
2. sklearn
3. glob
4. random
5. keras
6. tensorflow
7. OpenCV
8. dash
9. matplotlib
10. base64
11. os

## File Descriptions

- Dog_App.ipynb<br> # Trains the dog breed identification model, contains a description of the used architecture, discussion about the results, and possible points for future improvement.

- app.ipynb<br> # Develops web app using dash plotly.

- saved_models<br> # the saved models that attain the best validation loss.

- haarcascades<br> # saved haarcascades detector.

- bottleneck_features<br> # saved bottleneck features from pre-trained CNN models.

- extract_bottleneck_features.py<br> # script to extract the bottleneck features from the pre-trained CNN models.

- Dash<br> #  css assets for the Dash app.

- README.md<br>

## Instructions to run the web app

1. Please run the 'app.ipynb' file using Jupyter Notebook.

2. Point your browser to http://127.0.0.1:8050/

## Screenshots of the Web App

![Screenshot 1](https://github.com/mbahaay/Dog-Identification-App/Screenshots/App_Sample.png)

## Acknowledgements

1. Thanks to [Udacity](https://www.udacity.com/) for this Data Scientist Nanodegree Program.

