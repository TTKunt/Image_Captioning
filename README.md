# Image Captioning

## Dataset
We use the Flickr8k dataset. Flickr8K contains 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events. The dataset can be downloaded by requesting using this form https://forms.illinois.edu/sec/1713398.


## Show and tell
Show and tell is a simple neural image caption generator. It comprises of a CNN and an RNN to generate captions for images.
We use 3 different architectures for the CNN.
1. Inception Net V3
2. VGG 16
3. VGG 19

### Results
![image](https://user-images.githubusercontent.com/26028320/69885314-627ae300-1291-11ea-97da-5efe72db11f5.png)

## Show, attend and tell


## References
1. Show, attend and tell paper: https://arxiv.org/pdf/1502.03044.pdf
2. Show and tell paper: https://arxiv.org/pdf/1411.4555.pdf
3. Tensorflow tutorial for show, attend and tell: https://www.tensorflow.org/tutorials/text/image_captioning
4. https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/
5. https://cv-tricks.com/artificial-intelligence/show-attend-tell-image-captioning-explained/
6. https://github.com/cosimoiaia/KERAS-Show-and-Tell/blob/master/Keras_Show_and_Tell.ipynb
