# Vehicle Image Recognition

# Summary
  My goal for this project was to classify cars by make, model, and year based on a pre-configured dataset from Stanford University's AI website: (https://ai.stanford.edu/~jkrause/cars/car_dataset.html). The data comes pre-set with labels and bounding boxes for all images. Through the use of TensorFlow's Image Data Generator to transform the images into matrices of pixel data, I created a convolutional neural network to classify unseen validation images to different makes of car. From a combination of all data found on the site, I had a total of ~16,000 images, split into a 90/10 training/testing ratio, I was able to utilize pre-trained models like the EfficientNet series of models trained on the 'Imagenet' dataset to achieve an accuracy score of ~85% on testing data with 196 total classes of cars.


Repo Directory Contents:

  
1) image_prep

   1.1 image_file_prep.ipynb - preparing images and bounding boxes for modeling


2) modeling

   2.1 efficientnetb0.ipynb - efficientnetb0 modeling \
   2.2 efficientnetb1.ipynb - efficientnetb1 modeling \
   2.3 efficientnetb2.ipynb - efficientnetb2 modeling \
   2.4 inceptionv3.ipynb - inceptionv3 modeling \
   2.5 simple_custom_model.ipynb - sample model, early trial run
 
The presentation associated with this project cant be found here:                                        
https://docs.google.com/presentation/d/1E5p1trAnLmF0-o-N6YTQ0ROYW2ADP0io0OZ03yYTFZE/edit?usp=sharing

Because the data files were too large to host on github, I have uploaded them to google drive and they are accessible here:
https://drive.google.com/drive/folders/1PWeqPVxf_QM2AWAfxnwGs0tCudwQi87F?usp=sharing

Sources used during the creation of this project:

- https://towardsdatascience.com/a-concise-history-of-neural-networks-2070655d3fec
- https://ai.stanford.edu/~jkrause/cars/car_dataset.html
- https://towardsdatascience.com/complete-architectural-details-of-all-efficientnet-models-5fd5b736142
- http://image-net.org/about

