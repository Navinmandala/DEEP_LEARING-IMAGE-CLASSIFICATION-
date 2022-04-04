# DEEP_LEARING-IMAGE-CLASSIFICATION-
Image Classification using Convolutional Neural Networks ( Humans and Pets )
I AM USING CONVOLUTIONAL NEURAL NETWORKS TO PREDICT THE IMAGE BWTWEEN HUMANS AND PETS
I got the data sets of humans faces from kaggle and pets image files i gathered from google
As the images are not pixelized before and it is raw data images I am Using CNN
The basic CNN structure is as follows: Convolution -> Pooling -> Convolution -> Pooling -> Fully Connected Layer -> Output
I converted the image from 'RGB' to 'GreyScale' to reduce complexity 
And the image shape to 80X80 , it's enough to classify the image so I reduce dimensions of the image
I Normalized the data from ('0 to 255') to ('0 to 1')
I Shuffled the data so it can classify correctly
I built my model using CNN and activation functions ('Relu','Sigmoid') 
And optimizer ='sgd',loss='Binary_crossentropy', and epochs=20
And CNN performed Test loss: 0.11898893117904663
                  Test Accuracy: 0.9682875275611877
