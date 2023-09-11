# Skin-Cancer-CNN-Detection
Building and Optimizing Melanoma Skin Detection Problem through Image Identification and Classification using CNN

# Team Members: Kunal Garg, Unnati Garg and Sayantan Singh

# Project Name: Melanoma Skin Cancer Detection using CNN Model
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

Melanoma is a type of cancer that can be deadly if not detected early as it accounts for 75% of skin cancer deaths. This project provides an AI solution to dermatologists to evaluate the images and alert the patients of potential risks.

We have used portal provided 2357 images consisting of 9 diseases viz. Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign, keratosis, Seborrheic keratosis, Squamous cell carcinoma and Vascular lesion. We took the following steps to solve the problem:
> Read the data and understood the class imbalance
> Created a baseline model that Overfitted
> Augemented images to few degrees and zoomed it to check if Overfitting reduced. It did.
> Augmented images by inserting 500 images in each class and hence balanced the class imbalance
> The above step not only reduced the overfitting, it also increased the accuracy manifold

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis: Baseline model is ~60% in terms of accuracy due to class imbalance causing high overfitting
- Conclusion 2 from the analysis: After first Augmentation, the accuracy reduced but overfitting reduced as well drastically 
- Conclusion 3 from the analysis: Hence we understood the Augmentation strategy had to be changed to provide better results which we got after using Augmentor library
- Conclusion 4 from the analysis: The final model can now predict the disease class with ~83% accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used (Major Libraries used)
tensorflow, keras
numpy, pandas,
os, pathlib, PIL
google colab, drive
matplotlib, sns

## Datasets stored in folder: https://drive.google.com/drive/folders/1FXJWW7evLDTlAgT06278gEITCQI6EuoJ?usp=drive_link
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was a team effort of Kunal Garg, Unnati Garg and Sayantan Singh who contributed to many model changes and iterations to get the most optimal accuracy out. It was also guided by the notebook provided Mr. Sayan Dey, Upgrad Instructor that led us to the steps to follow and achieve the best results.

## Contact
Created by [@kunal-garg-ds] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
