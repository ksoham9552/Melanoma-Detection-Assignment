# Project Name
> Multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* General Info
	Steps followed as 
	Data Reading/Data Understanding → 
	Dataset Creation
	Dataset visualisation 
	Model Building & training
	Model Building & training on the augmented data
	Class distribution check	
	Handling class imbalances
	Model Building & training on the rectified class imbalance data 
* Tools use:	
* Conculsions:	
* Acknowledgements



## General Information
	Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. Hence it will be useful to build a CNN based model which can accurately detect melanoma



## Conclusions
3 models built. 
	1. First model as raw model to get idea with validation accuracy ~52% but overfitting was observed
	2. 2nd model built with augmentation to leaverage the data and droput startegy used. Overfitting reduced, but overall 	accuracy did not improved.
	3. 3rd model used, class rebalance technique with augmentor liabrary with 500 image samples for each class. This model 	also involve batch normalization. The validation accuracy increased to ~80% with slight overfitting

## Technologies Used
- Google Colab- with GPU environment, Google Drive for data storage
	Features involved : Tensorflow, Image Augmentor


## Acknowledgements
- This project was inspired by UpGrad & BoomBikes data 


## Contact
Created by [@ksoham9552] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->