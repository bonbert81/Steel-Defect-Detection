# Image Semantic Segmentation : Steel Defects Detection
  
  ## Demo
Link: [https://www.youtube.com/watch?v=QUOWaZT4XEk&feature=youtu.be](https://www.youtube.com/watch?v=QUOWaZT4XEk&feature=youtu.be)

![Making-of Animation](https://github.com/luckyRajputana/Steel-Defect-Detection/blob/master/streamlit-SteelDefectDetection-2020-08-16-21-08-26.webm.gif "Making-of Animation")

## Overview
This is a simple image semantic segmentation problem streamlit app trained on the top of Tensorflow API. The trained models i.e binary model,multilabel model, 4 image segmentation models combinally takes an image (Defected Steel Image) as an input and predict the class of defect from defect1, defect2, defect3, defect4 
with defected area pixels highlighted.

## Motivation
While working for one IT company for a manufacturing client, there they were using compuer vision cameras to catch the steel images and they have their algorithm installed to 
find the defected images but that was not based on machine learning or deep learning, so i thought why can't i create one solution to keep in my mind about the industry business problem.


## Technical Aspect
This project is divided into two part:
1. Training a deep learning model using Tensorflow2.0 using gradient tape.
2. Building and hosting a Streamlit web app on Heroku.
    - A user can choose image from a device or capture it using a pre-built camera.
    - Used __Amazon S3 Bucket__ to store the uploaded image and predictions.
    - After uploading the image, the predictions are displayed on a __Bar Chart__.
    
    
## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://keras.io/img/logo.png" width=200>](https://keras.io/) [<img target="_blank" src="https://miro.medium.com/max/1094/1*-QTg-_71YF0SVshMEaKZ_g.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://www.kindpng.com/picc/b/301/3012484.png" width=200>](https://aws.amazon.com/s3/) 

[<img target="_blank" src="https://res-3.cloudinary.com/crunchbase-production/image/upload/c_lpad,h_170,w_170,f_auto,b_white,q_auto:eco/mjnw24k71dpqmcqg6mno" width=270>](https://www.streamlit.io/)

## Team
[![Lucky Chauhan](https://avatars3.githubusercontent.com/u/46166986?s=460&u=111d083d8da11ea9c84cfd3c26db45749cbc918c&v=4)](https://rohitswami.com/) |
-|
[Lucky Chauhan](https://luckyportfolio.herokuapp.com/portfolio/) |)

## Credits
- [Google Images Download](https://github.com/hardikvasa/google-images-download) - This project wouldn't have been possible without this tool. It saved my enormous amount of time while collecting the data. A huge shout-out to its creator [Hardik Vasa](https://github.com/hardikvasa).

