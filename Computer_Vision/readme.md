# Computer Vision

## Classification:

Image classifier to recognize different species of flowers. We can imagine using something like this in a phone app that tells you the name of the flower your camera is looking at. In practice we'd train this classifier, then export it for use in our application. We'll be using this [dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) of 102 flower categories, you can see a few examples below.

<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/flower.png" height=250 width=500><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/train.png" height=250 width=500>

#### Prediction model of single image: 
<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/one_pred.png" height=250 width=500><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/one_pred2.png" height=250 width=500>

## Neural Style Transfer:
In neural style transfer, we have a content image and a style image, and we combine these two images in such a way that the combined image preserves the content of the content image while maintaining the style of the style image. An example style image and content image are as follows:

<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/archive/try7.jpg" height=200 width=250><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/archive/anom.jpg" height=200 width=250>

#### Output:
<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/style_transfer/genU2.png" height=250 width=500>
<p> From the preceding picture, we can see that the image is a combination of content and style images. </p>

## Image Generating with GANs:
To understand GANs, we need to understand two terms: generator and discriminator. First, we should have a reasonable sample of images of an object. A generative network (generator) learns representation from a sample of images and then generates images similar to the sample of images. A discriminator network (discriminator) is one that looks at the image generated (by the generator network) and the original sample of images and classifies images as original ones or generated (fake) ones.

To generate realistic image using deep convolutional GANs to generate more realistic images. In adiition, conditional DCGAN for generate specific class of image. 

<img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/CDGAN.png" title='DCGANs' height=500, width=350>

<!-- <img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/condi_dcgan.png" height=500, width=300> -->
