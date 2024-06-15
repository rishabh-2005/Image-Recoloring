# Image-Recoloring
This repository implements an image-to-image translation task using U-Net and convolutional autoencoders. The project converts grayscale images to color images through deep learning techniques, trained on a dataset for effective colorization. It showcases the application of neural networks in image enhancement tasks.

# Note :
This project is limited mainly to landscape greyscale images , due to the dataset containing mostly nature related images . The model does a good job at coloring the sky , water , ice , and mountains.
You can use it for greenery as well , but the predicted contrast would be very low ( you can still tell it's green though ).
Ofcourse , the model doesn't work for buildings , towers , indoor things etc. since the database doesn't contain such images , and training the model for that purpose would require huge amounts of data and computational power.
