# Melanoma_Detection

This is a CNN based multiclass classification model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contacts)

## General Information

The Train and Test dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the **International Skin Imaging Collaboration (ISIC)**. All images were sorted according to the classification taken with **ISIC**, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Technologies Used

- Google Colaboratory
- Deep Learning
- Machine Learning
- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Augmentor
  
## Conclusions

- The accuracy on the training data was improved by using the Augmentor library.
- However, the model still exhibits signs of overfitting.
  
To address the overfitting issue, potential solutions include:

- Adding more layers or neurons to the model.
- Incorporating dropout layers to mitigate overfitting.
- Furthermore, the model's performance can be further enhanced by tuning the hyperparameters, which involves optimizing the values of parameters such as learning rate, batch size, and regularization strength.

## Acknowledgements

- Upgrad
- IIIT Bangalore

## Contact

Created by 
- [Fawaz Khan](https://github.com/khanfawaz)  
- [Chiranjibi Priyadarshi](https://github.com/chiranjib129)
- [Jai Patil](https://github.com/NotTheBinaryBandit)

Feel free to contact us!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
