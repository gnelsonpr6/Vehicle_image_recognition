# Capstone

# Summary
  I started off this project with the goal of classifying cars by make, based on a pre-configured dataset from Stanford University's AI website: (https://ai.stanford.edu/~jkrause/cars/car_dataset.html). I made use of TensorFlow's Image Data Generator to transform the images into matrices of pixel data, and from there created a convolutional neural network to classify unseen validation images to different makes of car. I was able to utilize pre-trained models like EfficientNetB0 that were trained on the 'Imagenet' dataset to achieve an accuracy score of ~45% on testing data. This low of an accuracy score is due to the severity of class imbalance with 48 total classes and the absence of a larger training dataset. (I will be cutting this down to 5-7 this weekend and retraining before submission, just really wanted to try and get 60-70+ with the 48 classes but couldn't get there)

Things I plan on tackling this weekend before finishing up: 
  1. Reassign classes to more generic values, 5-10 classes max, rerun model.
  2. Confusion Matrices/Analysis
  3. Following Deep Learning book to plot some of the layer interpretations of images
  4. Write code in pytorch time permitting by monday

Because the data files were too large to host on github, I have uploaded them to google drive and they are accessible here:
https://drive.google.com/drive/folders/1PWeqPVxf_QM2AWAfxnwGs0tCudwQi87F?usp=sharing
