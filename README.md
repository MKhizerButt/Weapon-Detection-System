# Weapon-Detection-System

This project uses the Roboflow YOLOv5 Google Colab notebook which can be found in the Roboflow Model Zoo. 

# Dataset

Downlaod the dataset from Google's Open Image Dataset (https://storage.googleapis.com/openimages/web/visualizer/index.html?set=train&type=detection&c=%2Fm%2F083kb) using the OIDv4 toolkit which consists of around 1500 annoated images. 

This tutorial: https://www.youtube.com/watch?v=_4A9inxGqRM by The AI Guy can be followed in order to download the dataset and convert the annotations into YOLO format.

Upload the images to Roboflow for pre-processing and augmentions of the dataset. Export the project from the Roboflow wesbsite to the google colab notebook using the API. Add the API to the Roboflow code block which is present in the YOLOv5 Colab notebook.

Upload the data, and train the model until required loss is achieved by setting the number of epochs. Download the weights and export them to your google drive. The weights can now be tested in the notebook itself as well as locally on your local machine.

# Test Batch Images

![test](https://user-images.githubusercontent.com/66839830/155007068-65975efa-9e8b-4857-8c65-db659536ab05.jpeg)
