# AI-Final-Project-for-classifying
Dataset provided by TA is a csv file with lots of image line data. In order to classifier it we need to first convert it to a draw image. The method we are using here is simply drawing on a blank image, with white as the background(value = 1) and black as the content(value = 0).
	
About classifier, cause we are dealing with image, the first model came to our mind is CNN (Convolutional Neural Network). CNN has the property of that it can detect local feature , and the target data we wish to classify here, which are bunch of images, can benefits from such good property of it.

About Generator, the model we’re applying here is DCGAN(stands for Deep Convolutional Generative Adversarial Network), and the model is listed below, and Discriminator is a CNN network customized for this Generator:


