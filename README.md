# BackPropagation and Neural Network Architecture Basics

## Part 1

The excel sheet contains all the necessary steps to calculate the gradients using chain-rule to apply back propagation in Neural Network. 
> For, calculating the gradients for Loss w.r. t weights of network, we use partial differential equations (PDE) and chain rule.<br>

Following is the snapshot of excel sheet describing the process of BackPropagation in Neural Network:

![backprop](BackProp.png)

### Following are the charts for Loss when we used different Learning Rate (LR):

LR = 0.1           |  LR = 0.2
:-------------------------:|:-------------------------:
![LR = 0.1](LossGraphs/LR_1.png)  |  ![LR = 0.2](LossGraphs/LR_2.png)

LR = 0.5           |  LR = 0.8
:-------------------------:|:-------------------------:
![LR = 0.1](LossGraphs/LR_5.png)  |  ![LR = 0.2](LossGraphs/LR_8.png)

LR = 1.0          |  LR = 2.0
:-------------------------:|:-------------------------:
![LR = 0.1](LossGraphs/LR_10.png)  |  ![LR = 0.2](LossGraphs/LR_20.png)


From the above graphs, it can be seen as we increase the learning rate, the rate of decreasing loss is increased with respect to gradient updates. The model is converging faster when learning rate is relatively high when compared to lower learning rates.

## Part 2

I have achieved the accuracy of 99.35 with parameter count  equal to 19958. Following, I have explained the model architecture and more details: