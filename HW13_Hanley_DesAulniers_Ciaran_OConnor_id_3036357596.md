# Homework 13: Deep Learning SDK (the unofficial one, by Dustin Franklin)
## Tutors, Darragh Hanely and Brad DesAulniers
## Student Ciaran O'Connor, id = 303635759
## Group Tuesday 2-3:30pm Pacific Time
## Submission, answers to homework

#### SUBMISSION

#### 1.  Please report the time it took you to train the model along with the final accuracy top1/top5 that you were able to achieve.

ResNet 18, 7 hours (rounded) to compute 100 epochs at a rate of 1 epoch approximately every 250 seconds.    
ResNet 50, 10 hours (rounded) to compute 100 epochs at a rate of 1 epoch approximately every 700 seconds.

Exemplar accuracy @ 35 epochs, ResNet 18, accuracy = 79.12%.    
Exemplar accuracy @ 35 epochs, ResNet 50, accuracy = 76.65%.

The best models for each are included in the GitHub repository as model_best_pth.tar in the respective ResNet 18 and 50 directories.  The stdout output from the train.py script is also provided for each model in those dire 

#### 2. Did you get better results with Wide ResNet50 or ResNet18?

ResNet 18 reports the better accuracy, with an accuracy of 79.12% after 35 epochs.

 #### 3. What training parameters you adjusted? Why?

 Epochs to train and retrain the models over the data, to improve accuracy.  All I had time for with the extensive run time and the difficulty of getting the docker build and methods to bed-in on the Xavier architecture in the first place.

#### FIN
