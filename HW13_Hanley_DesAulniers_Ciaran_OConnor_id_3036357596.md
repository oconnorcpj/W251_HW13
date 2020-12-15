# Homework 13: Deep Learning SDK (the unofficial one, by Dustin Franklin)
## Tutors, Darragh Hanely and Brad DesAulniers
## Student Ciaran O'Connor, id = 303635759
## Group Tuesday 2-3:30pm Pacific Time
## Submission, answers to homework

#### SUBMISSION

#### 1.  Please report the time it took you to train the model along with the final accuracy top1/top5 that you were able to achieve.

ResNet 18, 7 hours (rounded) to compute 100 epochs at a rate of 1 epoch approximately every 250 seconds.    
ResNet 50, 10 hours (rounded) to compute 100 epochs at a rate of 1 epoch approximately every 700 seconds.

ResNet 18
Exemplar accuracy @ 35 epochs, ResNet 18, accuracy = 79.12%.  

#### __100 Epochs with Wide ResNet 50__ ####

Epoch: [99][1300/1307]  Time  1.029 ( 1.031)  Data  0.000 ( 0.041)  Loss 1.3425e+00 (1.3050e+00)  Acc@1  62.50 ( 58.82)  Acc@5 100.00 ( 88.89)    
Test: [140/142]  Time  0.313 ( 0.328)  Loss 2.3759e+00 (1.5421e+00)  Acc@1   0.00 ( 51.95)  Acc@5  75.00 ( 84.13)
 * Acc@1 51.982 Acc@5 84.229    

#### __100 Epochs with ResNet 18__ ####

Epoch: [99][1300/1307]  Time  0.186 ( 0.191)  Data  0.000 ( 0.010)  Loss 8.8987e-01 (1.1410e+00)  Acc@1  62.50 ( 63.81)  Acc@5  87.50 ( 91.59)
Epoch:
 
Test: [140/142]  Time  0.095 ( 0.100)  Loss 3.3343e+00 (1.4574e+00)  Acc@1   0.00 ( 57.62)  Acc@5 100.00 ( 86.17)
 * Acc@1 57.709 Acc@5 86.256

Exemplar accuracy @ 35 epochs, ResNet 50, accuracy = 76.65%.

#### 2. Did you get better results with Wide ResNet50 or ResNet18?

ResNet 18 reports the better accuracy, with an accuracy of 86.26% after 100 epochs.

 #### 3. What training parameters you adjusted? Why?

 Epochs to train and retrain the models over the data, to improve accuracy.  All I had time for with the extensive run time and the difficulty of getting the docker build and methods to bed-in on the Xavier architecture in the first place.

#### FIN
