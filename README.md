# CelebRecognition
Deep Neural Network trained from scratch using a restricted database.

Here is an example with a picture of tennis player Serena Williams given to the neural network:
![ec1e928d-7a02-4602-9569-112185f98035](https://user-images.githubusercontent.com/86181145/205505022-dcbe485e-2263-4a3a-abab-94dc6ad4f534.png)

The network then uses the MTCNN neural network to recognize facial features in an image and then zooms onto the face. This allows the network to work on images that all have the same distribution.

Here is the given image transformed by the MTCNN network, which is then passed as parameter to the implemented network:

![5a75806a-e617-4a6d-ba93-dd023ca6653d](https://user-images.githubusercontent.com/86181145/205505418-267d6ef5-0eb0-478b-95e3-2672d3a87d50.png)

Finally, the network returns the predicted class to which it thinks this image belongs to and its confidence in the result:

"Prediction:  Serena_Williams  - 0.99992335"
