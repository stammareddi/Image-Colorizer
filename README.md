# Image-Colorizer


Given a grayscale image, the AI agent will produce a colorized version of the image. Each pixel in the image has 3 values for red,green,blue ranging from 0-255. To get an accurate understanding of how the image is, it breaks each rgb value into a 3d matrix. Then the k-mean algorithm was applied  which is an unsupervised learning algorithm. To improve on this, the neural network program preprocesses the data and determines the input vector.Then it will go through a defined number of hidden layers and nodes. Each node uses the sigmoid activation function to determine the output vector for each given layer. 
