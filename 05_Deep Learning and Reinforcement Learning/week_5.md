# WEEK 5 QUIZ

## Q1. (True/False) In Keras, the Dropout layer has an argument called rate, which is a probability that represents how often we want to invoke the layer in the training.
`False`

## Q2. What is a benefit of applying transfer learning to neural networks? 
`Save early layers for generalization before re-training later layers for specific applications. `

## Q3. By setting ` layer.trainable = False` for certain layers in a neural network, we____ 
`freeze the layers such that their weights don’t update during training. `

## Q4. Which option correctly orders the steps of implementing transfer learning? 

 1. Freeze the early layers of the pre-trained model. 

2. Improve the model by fine-tuning. 

3. Train the model with a new output layer in place. 

4. Select a pre-trained model as the base of our training.  


# ANSWER ➡️ `4, 1, 3, 2`

## Q5. Given a 100x100 pixels RGB image, there are _____ features. 

`30000`
 There is one feature per pixel of each channel, so 100*100*3=30000. 


## Q6. Before a CNN is ready for classifying images, what layer must we add as the last? 

`Dense layer with the number of units corresponding to the number of classes `

## Q7. In a CNN, the depth of a layer corresponds to the number of: 
`filters applied`
