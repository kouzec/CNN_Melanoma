# Melanoma Detecion
>Multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma.
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma and Vascular lesion.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- There are 9 classes. But the data (no of images) is not evenly distributed across the classes. Some classes are having more images and some are having very less. Classes melanoma and pigmented benign keratosis are having highest number of images while class seborrheic keratosis has least. The model has peformed satisfactorily with the train and validation sets. But the accuracy is poor with the test data. However due to computing resource constraint, the model is not being further refined now.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Keras from Tensorflow
- Since the data is unevenly distrubuted Augmentor is used

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is part of an assignment for the PG Diploma Course on AIML by IIITB/UpGrad

## Contact
Created by [kouzec@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
