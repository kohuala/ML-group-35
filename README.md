# Automatic License Plate Recognition and Registration System

* NOTE: we will complete this page and upload the ppt tonight, please visit later. Thanks.

Machine Learning Project by Group35:
* Huihua Guan
* Yi (Roy) Luo

## Files include
* project.ipynb - main program
* group35.pptx - presentation ppt(more illustrations there, such as review of past techniques)
* train.zip - training images(please unzip before run the program)
* list.csv - parked car list
* /models/svc/pkl - saved model(you can create one by running the program)
* /cars - test images

## Project Aim

We would like to make the parking easier by automatically detecting the license plates instead of distributing physical tickets when cars enter or exit the parking lot.

## Technology Overview

* First Step: We used SVM to train the model
* Second Step: We used connected region method to extract and segment the LP
* Third Step: We used the trained model to recognize characters
* Fourth Step: We registered or delisted the estimated LP into a csv file

## Evaluation

* going to be updated

## Reference
* http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/
* https://blog.devcenter.co/developing-a-license-plate-recognition-system-with-machine-learning-in-python-787833569ccd
* https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721
* https://github.com/andela-foladeji/License-Plate-Recognition-Nigerian-vehicles

