
# Classification Application: Oxford 102 Flowers Dataset

With CUDA toolkits Kaggle notebook, I used transfer learning to train a network on 🚀NVIDIA TESLA P100 GPUs🚀. I discovered that the main classification challenges 🧐 : include changes in illumination, inter-class similarity, and diverse background in the image 🧐. To do this, I used image transformation to normalise the image and data augmentation to boost the training data. To increase performance, I employed image segmentation techniques to eliminate the backdrop of the image and highlight the subject, as well as learning rate annealing. After that, I applied the ReLU activation function and updated the Resenet50's classifier architecture to include three fully-connected layers. On the validation set, this method had a classification accuracy of 95%, and on the test set, it had a classification accuracy of 95%


## Accuracy

![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/train.png)


## Visualize the Sample Test Result

![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/Classification/assets/download.png)
## Usage/Examples

```python
# We are taking img_path

>>> display_result('flower_data/train/1/image_06744.jpg', model, category=1)
```
![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/one_pred.png)


```python
>>> display_result('flower_data/train/102/image_08007.jpg', model, category=102)

```
![App Screenshot](https://raw.githubusercontent.com/codenigma1/Deep-Learning/master/Computer_Vision/AutoEncoder_and_Image_Mainpulation/results/one_pred2.png)



🏁🏁🏁🏁🏁🏁🏁🏁🏁🏁🏁㊗️ 🏁🏁🏁🏁🏁🏁🏁🏁🏁
