# Capstone

# Summary
  I started off this project with the goal of classifying cars by make, based on a pre-configured dataset from Stanford University's AI website: (https://ai.stanford.edu/~jkrause/cars/car_dataset.html). The data comes preconfigured with labels and bounding boxes for all images. I made use of TensorFlow's Image Data Generator to transform the images into matrices of pixel data, then created a convolutional neural network to classify unseen validation images to different makes of car. From a combination of all data found on the site, I had a total of ~16,000 images, split into a 90/10 training/testing ratio, I was able to utilize pre-trained models like the EfficientNet series of models trained on the 'Imagenet' dataset to achieve an accuracy score of ~83% on testing data with 196 total classes of cars.


Because the data files were too large to host on github, I have uploaded them to google drive and they are accessible here:
https://drive.google.com/drive/folders/1PWeqPVxf_QM2AWAfxnwGs0tCudwQi87F?usp=sharing

Sources used during the creation of this project:

- https://towardsdatascience.com/a-concise-history-of-neural-networks-2070655d3fec
- https://ai.stanford.edu/~jkrause/cars/car_dataset.html
- https://towardsdatascience.com/complete-architectural-details-of-all-efficientnet-models-5fd5b736142
- http://image-net.org/about

