# Classification-of-Healthy-and-Unhealthy-Patients-from-Image-Dataset-
Red, green, and blue(RGB) values were obtained using the image dataset of blood samples and then classified into healthy or unhealthy with the help of machine learning.
# Data
Data used were in the form of images of blood samples which were taken by the mobile camera of a resolution of 14px through which RGB values were extracted. Besides this, the data included information about patients.
# Methodology
After preprocessing the data, four different models were used for classification.  
<pre>
Models used: K Nearest Neighbors(KNN)  
             Naive Bayes(NB)  
             Support Vector Machines(SVM)  
             Classification and Regression Trees(CART)  
             </pre>  
###   Using Kalman Filter
Project also studies about the Kalman filter and make use of it.The Kalman filter is a mathematical algorithm that helps in predicting the state of a system based on noisy measurements. In this case, the system is the RGB values of a blood sample, and the noisy measurements are the errors that can occur during the measurement process. The Kalman filter uses a set of equations to estimate the state of the system based on the measurements.So when we applied this modified Kalman Filter the accuracy of model came out to be 100% and we also got the hold on the ranges for RGB values for healthy and unhealthy patients for the given data set.
# Results
When only RGB values were considered then the accuracy of the models were between 55-60%. Considering RGB values with the information of patients the accuracy increased to 86-97%.  
Out of the four models, CART performed the best by giving an accuracy of 97.14%.
# Conclusion
The use of machine learning is also been seen in Ayurvedic practice which enhances the understanding of the diagnosis and the treatment. This project also shows the importance of the images and information of patients for classifying healthy or unhealthy patients.
