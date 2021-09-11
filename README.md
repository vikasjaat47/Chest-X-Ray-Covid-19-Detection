# Chest-X-Ray Covid-19 Detection using CNN & Transfer Learning
The new coronavirus (COVID-19), declared by the World Health Organization as a pandemic, has infected more than 1 million people and killed more than 50 thousand.
An infection caused by COVID-19 can develop into pneumonia, which can be detected by a chest X-ray exam and should be treated appropriately.

In this work, we propose an automatic detection method for COVID-19 infection based on chest X-ray images. Dataset is collected from kaggle platform.
The Dataset contain :
1. 536 X-ray images of patients diagnosed with coronavirus.
2. 668 X-ray images of healthy patients.
3. 619 X-ray images of patients diagnosed with viral.

Here we apply two model :
1. CNN Model 
   - Accuracy : 95%
   
[evalution_with_cnn]()

[confusion_marix_with_cnn](https://github.com/Sonukumari97/Chest-X-Ray-Covid-19-Detection/blob/main/Output/Confusion_Matrix_CNN.png)

2. Transfer Learning Approch using MobileNet algorithem with pre-trained Imagenet weights
 (convolutional neural networks (CNNs) trained on ImageNet, and adapt them to behave as feature extractors for the X-ray images)
   - Accuracy : 97%
   
[evalution_with_Transfer_learning]()

[confusion_matrix_with_Transfer_Learning]()
