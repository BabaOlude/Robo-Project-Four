Robo Project Four

Deep Learning Project
In this project I will demonstrate the use of a fully convolutional neural network. The FCNN will be used to identify and follow a character in the simulation environment. The identified person in this assignment is known as a hero. There are many other characters in the simulation which serve the purpose of making the project more challenging because the goal is to follow the hero.


Rubric Components

Code

   Architecture
   
   The fully convolutional neural network that I used for this project was specifically useful because I needed to define the shape as well as   the location of the target object “hero”. The fully connected layers include encoders. My project uses the encoders to perform semantic segmentation to identify parts of images. Along with the encoders, decoders were used. Essentially encoders enlarge images and decoders shrink images. One of the keys to using an FCN is the understanding that the size of the convolutions can make the computation time take a long time if you don’t put a cap on it.
   
   Neural Network 
       Epoch
       Learning Rate
       Batch Size
       
       1x1 convolutions
       fully connected layer
       
   Encoding/Decoding Images
   


What Worked

What Didn't Work

Future Improvements

    NN Limitations
