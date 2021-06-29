# Real-Time-Face-Recognition-System
This is a real time face recognition system made using keras and opencv. The Project comprises of the following steps-
1. Creating environment that can be done using- 
    i. in anaconda prompt write:-  conda create -n yourenvname python=x.x anaconda
    ii. install opencv by -  pip install opencv-python

2. Collection of images for dataset-
    i. run 1.py in your anaconda environment that will start the webcam and instantly click 20 images of your face crop them and save them in images folder.
    ii. create sperate folders of train and test and inisde them seprate folders of images per pperson.
    
3. Training the model -
    This model is made using VGG16 and we have used haar frontal face features to extract and train the dataset.
    i. run Face_Recognition.py - make necessary changes this file will run for a few minutes based on the system you are using we've run it for 3 epoches you
    can increase or decrease the no of epoches as per your requriment.
    ii. save the model.
    
4. Testing the Model - 
    i. open facefrontend.py
    ii. load the harcascade classifier.
    iii. load the model we created in the previous step.
    iv. run facefrontend.py 
    
The model's Ready.

This is a generalised model this can be trained using different transfer learning techniques like VGG19 or resnet only few changes are required. 

