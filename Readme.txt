--------------------------
Analysis of Neural Network
--------------------------
------------------------------------------------------------------------------
How many neurons and layers did you select for your neural network model? Why?
------------------------------------------------------------------------------
2 Layers
First Layer => 36 Neurons
Second Layer => 18 Neurons


-------------
Justification
-------------
This decision was made after I experimented with higher number of neurons.
I realized that as I increased the number of neurons, the accuracy of the 
neural network model diminished.  In addition, dropping the number of neurons 
below 36 and 18 for the first and second layers, respectively, adversely 
affected model accuracy.

I also added a third layer but this had little effect on the model accuracy.


----------------------------------------------------------------------------
Were you able to achieve the target model performance? What steps did you 
take to try and increase model performance?
----------------------------------------------------------------------------
Model Accuracy => 73 percent
Loss => 0.55

No, I was unable to attain the model accuracy of 75 percent. 

Initially I used 'relu' but switched to 'sigmoid' for both layers as well
as the output and this measure resulted in an improved model accuracy.

I experimented with increasing the epochs but this had a negative effect on
accuracy.  Adding layers and neurons had no positive effect as well. I also
switched the loss function from 'binary_crossentropy' to 'mean_squared-error'
and 'mean_absolute_error' and both changes yielded no improvement.

Based on this evaluation, I believe the steps that I can take to improve the 
model include:

1) Experimenting with different optimizers
2) Work on additional preprocessing of the dataset. Probably some other 
   variables need to be binned into different categories.

-----------------------------------------------------------------------------
If you were to implement a different model to solve this classification problem, 
which would you choose? Why?
-----------------------------------------------------------------------------

Honestly, I need to fully explore more on each model to fully understand the 
appropiate situations to use them.  But probably, I might try a 'tanh' or 
'leaky relu'.

-----------------------------------------------------------------------------