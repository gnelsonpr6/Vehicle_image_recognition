# Vehicle Image Recognition

## Summary
 
The goal for this project was to classify cars by make, model, and year based on a pre-configured dataset from Stanford University's AI website: (https://ai.stanford.edu/~jkrause/cars/car_dataset.html). The data comes pre-set with labels and bounding boxes for all images. The images were reshaped down to the bounding box dimensions and saved as the original image. Through the use of TensorFlow's Image Data Generator to transform the images into matrices of pixel data, a convolutional neural network was used to classify unseen validation images to different makes of car. From a combination of all data found on the site, there were a total of 16,185 images, split into a 90/10, training/testing ratio. Pre-trained models like the EfficientNet series and InceptionV3, previously trained on the 'Imagenet' dataset, were used to achieve a final accuracy of ~85%.


## Results

Using EfficientNetB1's model formatting with a portion of the layers keeping the pretrained weights learned on the ImageNet dataset, an accuracy of ~85% was achieved for predicting the year, make, and model of a particular car based on an image unseen by the CNN model. Below is a summary of the results and model:


![image](https://user-images.githubusercontent.com/42257654/112686101-b6202100-8e32-11eb-8a32-e6f91d309fb9.png)


![image](https://user-images.githubusercontent.com/42257654/112685958-82dd9200-8e32-11eb-8d61-c461555069dd.png), ![image](https://user-images.githubusercontent.com/42257654/112686052-a4d71480-8e32-11eb-9d77-1ed97efcfbac.png)




### Repo Directory Contents:

  
1) image_prep

   1.1 - image_file_prep.ipynb - preparing images and bounding boxes for modeling


2) modeling

   2.1 - efficientnetb0.ipynb - efficientnetb0 modeling \
   2.2 - efficientnetb1.ipynb - efficientnetb1 modeling \
   2.3 - efficientnetb2.ipynb - efficientnetb2 modeling \
   2.4 - inceptionv3.ipynb - inceptionv3 modeling \
   2.5 - simple_custom_model.ipynb - sample model, early trial run
 
#### The presentation associated with this project cant be found here:                                        
https://docs.google.com/presentation/d/1E5p1trAnLmF0-o-N6YTQ0ROYW2ADP0io0OZ03yYTFZE/edit?usp=sharing

#### Because the data files were too large to host on github, I have uploaded them to google drive and they are accessible here:
https://drive.google.com/drive/folders/1PWeqPVxf_QM2AWAfxnwGs0tCudwQi87F?usp=sharing

#### Sources used during the creation of this project:

- https://towardsdatascience.com/a-concise-history-of-neural-networks-2070655d3fec
- https://ai.stanford.edu/~jkrause/cars/car_dataset.html
- https://towardsdatascience.com/complete-architectural-details-of-all-efficientnet-models-5fd5b736142
- http://image-net.org/about
- https://www.tensorflow.org/api_docs/python/tf/image/

