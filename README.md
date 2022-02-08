# Weapon-Detection-System

This project uses the Roboflow YOLOv5 Google Colab notebook which can be found in the Roboflow Model Zoo. 

# Dataset

The dataset was downloaded from Google's Open Image Dataset (https://storage.googleapis.com/openimages/web/visualizer/index.html?set=train&type=detection&c=%2Fm%2F083kb) using the OIDv4 toolkit and consisted of around 1500 annoated images. This tutorial: https://www.youtube.com/watch?v=_4A9inxGqRM by The AI Guy can be followed in order to download the dataset and convert the annotations into YOLO format.

These images were uploaded to Roboflow and were further pre-processed and augmented. The Roboflow project was then exported as code in order to get the API link and code block which is to be added in the YOLOv5 Colab notebook.

After uploading the data, the model is trained until required loss is achieved by setting the number of epochs. The weights are then downloaded and can be tested in the notebook itself as well as locally on your local machine.
