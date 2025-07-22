# Terrestrial Vehicle Detection and Classification in Satellite Images

This project was developed for the *Cognitive Computing Systems* course as part of my academic work as a master's degree student in Computer Engineering.

The work focuses on using a YOLOv11-based model to detect and classify terrestrial vehicles from high-resolution satellite images.

The code was developed and tested on Jupyter Lab.

# The dataset
The dataset contains 1920 satellite images that were taken from the much bigger dataset called xView. The classes in this dataset are Vehicle, Ship and Airplane.

# Step by step guide to run the project on any machine

  - Download the dataset from https://universe.roboflow.com/master-thesis-it8vi/xview-master-thesis/dataset/8, the version is "2023-04-27 7:38am"
  - Extract the content in the chosen directory (for example, J: on a windows machine)
  - In J:, create a folder for the project (for example, xView). Extract the content of the dataset in the created folder.
  - Delete the readme files.
  - Create two folders "images" and "labels", go to the folders train>images and val>images and move all the images to "images". Do the same for the labels.
  - Edit the data.yaml file in data1.yaml and add, at the end, "weights: [4.0, 4.0, 1.0]"
  - Start the project through Jupyter Lab.
  - For a matter of size, the folders train22 and predict have been omitted. They will be created by running the code (train22 from the training block and predict from the inference block).

