
#Face_Detector_using_Matlab
In this project we detect real-time faces using AlexNet Convolutional Neural Network in Deep Learning. 

STEP 1------------
I haven't included the DataSet because of privacy reasons but surely do check out the Data_Collection script. It has a code that can capture 150 images using the webcam. In my dataset, I have taken my face and Actress Mayim Bialik's face as the training and testing Dataset.

STEP 2------------
The file train.m contains the training script for building a model.I have taken 20 epochs but you can customise that according to your needs. 
![training](https://user-images.githubusercontent.com/51987596/131334371-c5a9c778-c7c1-49d6-b314-47c4ca0845d2.png)

STEP 3------------
The file test.m contains the testing script for testing the model that we have just built. For testing, the model opens the webcam and detects the face in real-time. In the first image we can see that it is detecting Mayim Bialik's image via my phone correctly. 
![test1](https://user-images.githubusercontent.com/51987596/131335221-cc903478-6567-49c1-8165-0bd4f460d2cc.png)

When a face is not found by the program, it returns "No face Detected". We can see so in the second screenshot.
![test2](https://user-images.githubusercontent.com/51987596/131335325-059c2815-32a0-431f-bce5-052da4bfcef3.png)
