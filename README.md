This project was made as a college project and for that reason it's all written in my maternal language (Croatian). So here's a short explanation what it's all about:

As a topic, I chose to compare multiple classifiers (neural networks) trained on a dataset of images of traffic speed signs.

I decided to make a comparison of the efficiency of multiple models of convolutional neural networks, creating at least one custom network and comparing it with at least one established well-known type of convolutional network (e.g., ResNet, VGG16...).

In the end, I created three custom neural network models for the mentioned dataset, and among the known networks, I used a model inspired by the VGG16 network.

Project is divided as follows:

- Izgled testnog i trening foldera nakon sređivanja.jpg --> how training and test is divided in classes (folders containing different groups of images of speed traffic signs)

- Izgled datoteke sa datasetom.jpg --> how folder containing test and image folders looks like

- Link za Youtube video.txt --> .txt file containing private link for ~30 min video of me explaining the whole project while going through its code (in Croatian)

- Projekt_Đurašinović_Luka.ipnyb --> entire code of project with documentation and comments written below/above each section of code (in Croatian)

- testni_folder_prije_sredivanja.jpg --> image of test folder and how it looked like before I erased all unnecessary images*

- trening_folder_prije_sredivanja.jpg --> image of training folder and how it looked like before I erased all unnecessary traffic sign folders*

*The dataset was created by reducing a larger dataset obtained from Kaggle (see "Credits"), as the original dataset contained all types of signs, while in my case, only speed signs were needed.

Feel free to download the entire project, and it should work without any issues. The only thing you'll need to change within the code is to adapt the paths to the desired training and testing directories (since I uploaded all the images to Google Drive and read them from there).


CREDITS:
Daniil Deltsov
https://www.kaggle.com/datasets/daniildeltsov/traffic-signs-gtsrb-plus-162-custom-classes
