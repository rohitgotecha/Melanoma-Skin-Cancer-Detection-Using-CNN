# Melanoma Skin Cancer Detection Using CNN
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project focuses on building a deep learning-based solution to detect melanoma, a dangerous form of skin cancer. Dermatologists use visual examination to detect such conditions, but this process can be automated using image classification models.

The business problem addressed is to reduce the manual effort involved in diagnosing melanoma and other skin diseases by providing an automated solution that assists dermatologists in analyzing medical images.

The dataset used in this project consists of 2357 images of different oncological diseases, including both benign and malignant conditions. The dataset was provided by the International Skin Imaging Collaboration (ISIC).

The images represent the following 9 disease classes:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- A custom CNN model was built from scratch without using any pre-trained architectures.
- Initial results showed signs of overfitting/underfitting, highlighting the need for proper data augmentation.
- The class distribution was imbalanced, with some diseases like melanoma and nevus dominating the dataset, while others had fewer examples.
- Data augmentation techniques and balancing strategies were used to address both underfitting and class imbalance, leading to improved model performance.
- The final model trained on augmented and class-balanced data showed better generalization, but further optimization could still improve its accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.10.12
- [Matplotlib](https://matplotlib.org/) - version 3.7.1
- [Numpy](https://numpy.org/) - version 1.26.4
- [Keras](https://keras.io/) - version 3.4.1
- [Augmentor](https://augmentor.readthedocs.io/) - version 0.2.12
- [Tensorflow](https://www.tensorflow.org/) - version 2.17.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the need for automated melanoma detection in dermatology.
- The dataset was provided by the International Skin Imaging Collaboration (ISIC).
- The project was based on custom CNN development without using transfer learning models.


## Contact
Created by [@rohitgotecha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
