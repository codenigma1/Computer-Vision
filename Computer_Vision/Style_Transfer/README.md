
# Neural Style Transfer

Based on the paper by Gatys et al., the model generated an artifact in the form of synthesized images for this project. The model takes two photos (content and style images), then passes both to the VGG19 convolutional neural network, which generates the synthetic image in the meantime. The model extracts the feel from the style image and generates an output depending on the appearance of the other content image. Using a pre-determined procedure, the arbitrary style effectively transfers a multiplication of content image features and a transformation matrix derived from features, viz Gram Matrix. I also measured the content representation by iteratively calculating the mean square error between the content image and the synthesized image and decreasing the loss to maximize the result.

## Content Image                 |                    Style Image
<img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/archive/try7.jpg" height=250><img src = "https://github.com/codenigma1/Deep-Learning/blob/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/archive/anom.jpg" height=250>

## Results

<img src = "https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/anom.png" height=250>
<img src="https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/tushar.png" height=250>
<img src="https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/author.png" height=250>

## Style Image
<img src = "https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/painting.jpg" height=250>

![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/better_nst.png)

![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/generated_image_11.png)

## Style Image
<img src = "https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/style_img.jpg" height=250>

![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/sample.png)

## Style Image
<img src = "https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/the_shipwreck_of_the_minotaur.jpg" height=250>


![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/generated_image_12.png)



![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Style_Transfer/assets/generated.png)


## Code Reference

| References             | link                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Book | [Amazon](https://www.amazon.in/Modern-Computer-Vision-PyTorch-applications-ebook/dp/B08KG9X776) |
| Coursera | [Deep Learning course by Andrew NG](https://www.coursera.org/specializations/deep-learning)|
| Udacity | [Udacity Deep Learning in PyTorch](https://www.udacity.com/) |



