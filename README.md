# Classification-using-ResNet18
<br>
The data is 24345 color images of faces. In almost every image there is a singal person with or without face mask.
The images describe people of a variety of ages, genders and angels. 
The images are split into two - train.tar and test.tar.
<br>
The name of every image file is 'XXXXX_Y.jpg' where XXXXX is a uniqe ID of the image and Y is the label.
The label 0 represents a person that isn't wearing the mask properly and the label 1 represents a person that wearing a mask properly.
<br>
The task is to build a binary classifier so that given a face image of a person, decide whether the person in the image
is wearing a mask in a propere way or not.
<br>
The NN is ResNet18 using Adam optimizer. 
The Train.py contains calculations of the following rates for the train and test as a function of ephocs - F1, CE loss.
There is also a ROC-AUC in visualizations.py. 
