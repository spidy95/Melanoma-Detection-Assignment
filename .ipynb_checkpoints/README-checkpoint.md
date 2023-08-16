# Melanoma-CNN-Prediction

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#TechnologiesUsed)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
  
- Melanoma, a form of cancer, possesses the potential for fatality unless identified in its early stages. It contributes to 75% of fatalities associated with skin cancer. The development of a solution capable of assessing images and notifying dermatologists regarding melanoma's existence holds the promise of significantly diminishing the manual workload required for diagnosis.

- To construct a CNN-driven model with the capability to precisely identify melanoma.
  
- The dataset comprises 2357 images encompassing both malignant and benign oncological conditions. These images were sourced from the International Skin Imaging Collaboration (ISIC). The sorting of images followed ISIC's classification, and subsets were equally divided, except for melanomas and moles, which exhibit a slight image dominance.


## Conclusions
- Conclusion 1 : A simplified model lacking normalization, dropouts, and featuring a reduced number of convolutional layers achieved an accuracy of 70%. However, the validation accuracy stood at 38%, indicating overfitting.
- Conclusion 2 : Incorporating data augmentation into the model resulted in an accuracy of 42%, which was mirrored in the validation accuracy as well, suggesting a decline in performance.
- Conclusion 3 : Utilizing Augmentor to address data imbalance led to a notable improvement in model performance, achieving an accuracy of 97%, with a corresponding validation accuracy of 88%.


## TechnologiesUsed
- library - TensorFlow v2.13.0
- library - Python 3.11.3
- library - Keras 2.13.1
- library - Matplotlib


## Acknowledgements
Give credit here.
- This project was Inspired by kaggle 
- References : Tensorflow Documentation
- This project was based on Tensorflow Documentation and a sample project Illustration.


## Contact
Created by [Abhishek Tiwari] - feel free to contact me!

<!-- This project is open source and available under the [... License](). -->