# Identification of Hand-Written Digit Using CNN
As we know a human eye can recognize any hand written digit written by human. But, how can we teach a computer to do the same. With the help of Convolution Neural Network, we teach a computer to recognize hand-written digit. 
## Dataset
A famous dataset is used to train the model , i.e MNIST dataset.
## Methodology
We used our own model to train the dataset. The model is based on CNN. The input images are entered through the input layer and passed to next layer. For the next two layers, there are 1 convolution and maxpooling layer each. After these, they are flatten and passed to a dense layer. The resultant is passed into a 10 neurons dense layer with activation function ‘SoftMax’.  
## Result
We obtain an accuracy of 99.14% on the validation set. 
## Next Step
We are trying to used more diverse data to make the model more robust.    
