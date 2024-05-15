This project was made as a college project and for that reason it's all written in my maternal language (Croatian). So here's a short explanation what it's all about:

As a topic, I chose to compare multiple classifiers (neural networks) trained on a dataset of images of traffic speed signs.

I chose speed limit signs because during the time of selecting the topic, I was just finishing driving school, so the whole theme was very familiar, interesting, and relevant to me.

Initially, I had the idea to compare, for example, K-NN classifiers and convolutional networks, but as I repeated and learned more theory, I realized that classifying images with linear classifiers, NN classifiers, K-NN classifiers, as well as simple neural networks (without convolutional layers), simply lagged significantly behind training and testing within convolutional neural networks. Therefore, in the end, I decided to make a comparison of the efficiency of multiple models of convolutional neural networks, creating at least one custom network and comparing it with at least one established well-known type of convolutional network (e.g., ResNet, VGG16...).

In the end, I created three custom neural network models for the mentioned dataset, and among the known networks, I used a model inspired by the VGG16 network.


The dataset was created by reducing a larger dataset obtained from Kaggle (see "Credits"), as the original dataset contained all types of signs, while in my case, only speed signs were needed.

Feel free to download the entire project, and it should work without any issues. The only thing you'll need to change within the code is to adapt the paths to the desired training and testing directories (since I uploaded all the images to Google Drive and read them from there).


CREDITS:
Daniil Deltsov
https://www.kaggle.com/datasets/daniildeltsov/traffic-signs-gtsrb-plus-162-custom-classes
