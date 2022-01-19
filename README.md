![Heading Image - ProjectBeta](https://github.com/AlphaLaser/ExML-Finals-ProjectBeta/blob/825931aceeda0722319b53d459bd65511422c630/Images/pb.png)

<br>

# Table of contents

- Dataset
  - Introduction
  - Creation
- Model
  - Introduction
  - Strategy
  - Architecture
  - Scores

<br>

# Dataset

- <b>Intro</b> : We have used cv2 and time python libraries to obtain our dataset. We downloaded the videos for the images from youtube and then set the path to obtain images.
- <b>Creation</b> : After setting the path, we set the frame = cap.read() and also set the path for converting the images into .png files. We set it to get images every 4 sec in the video till it got 1k images from that particular video. Every video was at least an hour long so as to obtain as many images as possible. Hence we got a perfect dataset for the task.

# Model

- <b>Intro</b> : To create and train the model, we have used numpy, pandas, os, glob, sklearn, tensorflow and tensorflow.keras python libraries. We have used preprocessing and train_test_split from sklearn and used ImageDataGenerator from tensorflow. We set the path to the dataset and put the size.
- <b>Strategy</b> : We created 3 empty lists namely train_images, train_labels and encode_labels. We trained the data using ImageDataGenerator and resized the images to make it work. We used tensorflow.keras to create the model.
