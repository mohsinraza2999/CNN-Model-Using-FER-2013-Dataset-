# CNN-Model-Using-FER-2013-Dataset-
This project report focuses on facial expression recognition (FER) using the FER2013 dataset, 
which contains 35,887 grayscale images across seven basic emotion categories. Various studies,
including those using VGG and ResNet architectures, reported accuracies ranging from 63.5% to 71.8%.
The proposed model utilizes a convolutional neural network (CNN) with four convolutional layers, batch normalization, 
and dropout for regularization, achieving a training accuracy of 60%. Challenges include class imbalance and potential overfitting.
Suggested improvements involve transfer learning, hyperparameter tuning, ensemble methods, and exploring alternative architectures to
enhance the performance the model in emotion classification to use in real world applications.
First of all we write a programe to read all the images and append the images and labels in a list
and save them in '.mat' format and use them in for the trianing the CNN model we build.
For the model expression the labels are
"0" "angry"
"1" "disgust"
"2" "fear"
"3" "happy"
"4" "sad"
"5" "surprise"
"6" "neutral"
