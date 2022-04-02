# Computer Vision

## Classification:

Image classifier to recognize different species of flowers. We can imagine using something like this in a phone app that tells you the name of the flower your camera is looking at. In practice we'd train this classifier, then export it for use in our application. We'll be using this [dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) of 102 flower categories, you can see a few examples below.

<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/flower.png" height=250 width=500><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/train.png" height=250 width=500>

#### Prediction model of single image: 
<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/one_pred.png" height=250 width=500><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/one_pred2.png" height=250 width=500>

Download train model please click [here](https://nr9tzjm73q.clg07azjl.paperspacegradient.com/files/classifier.pt_xsrf=2%7C9b1bc175%7C394b5fd95d39391d3d0578d5a1ff130c%7C1648898218)

## Neural Style Transfer:
In neural style transfer, we have a content image and a style image, and we combine these two images in such a way that the combined image preserves the content of the content image while maintaining the style of the style image. An example style image and content image are as follows:

<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/archive/try7.jpg" height=250 width=250><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/archive/anom.jpg" height=250 width=250>

#### Output:
<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/style_transfer/genU2.png" height=250 width=500>
<p> From the preceding picture, we can see that the image is a combination of content and style images. </p>

## Image Generating with GANs:
To understand GANs, we need to understand two terms: generator and discriminator. First, we should have a reasonable sample of images of an object. A generative network (generator) learns representation from a sample of images and then generates images similar to the sample of images. A discriminator network (discriminator) is one that looks at the image generated (by the generator network) and the original sample of images and classifies images as original ones or generated (fake) ones.

To generate realistic image using deep convolutional GANs to generate more realistic images. In adiition, conditional DCGAN for generate specific class of image. 
#### DCGAN and Conditional DCGAN:
<img title = "DCGAN"  src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/CDGAN.png" title='DCGANs' height=500, width=400><img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/condi_dcgan.png" height=500, width=400>

## Advanced GANs:
#### Pix2Pix GAN:
Imagine a scenario where we have pairs of images that are related to each other (for example, an image of edges of an object as input and an actual image of the object as output). The challenge given is that we want to generate an image given the input image of the edges of an object. In a traditional setting, this would have been a simple mapping of input to output and hence a supervised learning problem. However, imagine that you are working with a creative team that is trying to come up with a
fresh look for products. In such a scenario, supervised learning does not help as much – as it learns only from history. A GAN comes in handy here because it will ensure that the generated image looks realistic enough and leaves room for experimentation (as we are interested in checking whether the generated image seems like one of the classes of interest or not).

<img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/shoes1.png" height=300, width=600>

#### Cycle GAN:
CycleGAN to convert the image of an appleinto the image of an orange and vice versa. The Cycle in CycleGAN refers to the fact that we are translating (converting) an image from one class to another and back to the original class.

<img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/cycle.png" height=300, width=600>


#### Customize StyleGAN:
Leveraging StyleGAN on custom images. 
Let's first understand a few historical developments prior to the invention of StyleGAN. As we know, generating fake faces from the previous chapter involved the usage of GANs. The biggest problem that research faced was that the images that could be generated were small (typically 64 x 64). And any effort to generate images
of a larger size caused the generators or discriminators to fall into local minima that would stop training and generate gibberish. One of the major leaps in generating high-quality images involved a research paper called ProGAN (short for Progressive GAN), which involved a clever trick.

<img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/orignal.png" height=250, width=300><img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/syth.png" height=250, width=300>

#### Transfer high level of features and Transfer granular features::
<img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/high_level.png" height=250, width=250><img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/hgih2.png" height=250, width=250>

#### Transfer general image features:
<img src="https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/high2.png" height=300, width=300>


