# Melanoma Skin Cancer Detection
> The project involves building a custom convolutional neural network (CNN) model to accurately detect melanoma, a type of skin cancer responsible for 75% of skin cancer-related deaths. The goal is to create a solution that can evaluate images of skin lesions and alert dermatologists to the presence of melanoma, potentially reducing the manual effort involved in early diagnosis. The dataset consists of 2357 images across nine different types of skin conditions, including melanoma and benign lesions, requiring a robust model to distinguish between these classes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background of the Project: The project focuses on creating a custom CNN model to detect melanoma, a life-threatening skin cancer. Melanoma detection can greatly improve patient outcomes if identified early. The model uses image data to help automate the diagnostic process, reducing manual efforts.
- Business Problem: The project aims to solve the problem of early melanoma detection by providing a model that can accurately identify various skin conditions, including melanoma. This solution can enhance diagnostic efficiency and reduce the burden on healthcare professionals.
- Dataset: The dataset includes 2,357 images of malignant and benign oncological diseases from the ISIC archive. It covers 9 skin disease classes, such as melanoma, basal cell carcinoma, and actinic keratosis, with a class imbalance across the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas version: 2.2.0
- Matplotlib version: 3.8.3
- Tensorflow version: 2.17.0
- Augmentor version: 0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- Started with a base model with 3 convolution layers but large difference between training & validation accuracy indicated overfitting.
- After introducing augmentation, dropouts and L2 Regularization, we are able to get rid of overfitting to a large extent and achieve a reasonably good accuracy level.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@zeebee48] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->