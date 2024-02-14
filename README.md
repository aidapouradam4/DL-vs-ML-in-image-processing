# DL-vs-ML-in-image-processing
A comprehensive project focusing on image classification using both Deep Learning (DL) and Machine Learning (ML) techniques. The project encompassed multiple tasks including data exploration, preprocessing, model development, tuning, and performance evaluation for both DL and ML approaches using the CIFAR-10 dataset.

Deep Learning Approach:

* Utilized a VGG-based model architecture for DL, achieving top performance in the ILSVRC 2014 competition.
![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/5a57724c-c949-4d38-99a6-fb915941b1fa)

* Conducted data exploration and preprocessing on the CIFAR-10 dataset consisting of 60,000 32x32 color images in 10 classes.
* Applied stratified k-fold cross-validation to maintain balanced class distributions.
* Developed a base VGG model and optimized hyperparameters to mitigate overfitting.
<img width="605" alt="5" src="https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/95af7cc2-4705-41e2-854f-c2002edf335c">

* Achieved a test accuracy of 80% after model tuning, outperforming ML approaches.
![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/b5a0db5c-fba7-4e68-bb10-21812a04abcc)


Machine Learning Approach:

* Employed feature extraction techniques including Histogram of Oriented Gradients (HoG), Gabor, and Color Histogram for ML.
![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/e96c7493-83a6-4295-92b9-3fd7d58f2900)

* Utilized ML algorithms such as Random Forest Classifier, Support Vector Classifier, and Decision Tree.
![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/3dc81cb1-2827-4e6f-9552-fb2177e4eb01)

* Conducted hyperparameter tuning using grid search for Random Forest Classifier.
* Achieved an accuracy of 53.24% for ML compared to 80% for DL.
![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/5a9476f7-f4c4-474a-9a4f-d33b87af19d5)

  
Comparison and Conclusions:

* Compared DL and ML approaches in terms of accuracy, feature learning, interpretability, and efficiency.
![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/68968b22-0ff0-4446-a3ab-b9cb3f946621)
DL Highest Accuracy for each class label:
1st: Frog
2nd: Automobile
3rd: Ship

![image](https://github.com/aidapouradam4/DL-vs-ML-in-image-processing/assets/103252922/7b4d39e0-58d2-49b2-bec8-20423cb5b32c)
ML Highest Accuracy for each class label:
1st: Frog
2nd: Automobile
3rd: Truck



* Identified DL as superior in terms of accuracy and automatic feature learning, while ML algorithms offered interpretability and efficiency advantages.
* Provided insights for choosing between DL and ML approaches based on specific project requirements and considerations.
