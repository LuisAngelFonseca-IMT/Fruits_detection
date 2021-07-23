# Fruits detection
This repository present a fruit detection model using a neural network. The aim is to build small scale dataset of two fruits, apples and pineapples, then using a third software to apply data augmentation and finally using transfer learning to implement a object detection algorithm in a Jetson Nano.
## Create our dataset
- Let's found al least 30 images for each class. 30 apples and 30 pineaple
- It's important to found images from diferents perspectives and with others object to have a rich dataset.
![Fruits_search](images/fruits_search.png)
- I save the images with numbers, example 001, 002 and 003
## Label our images 
- Download the Vott repository [here](https://github.com/microsoft/VoTT)
- In the github repository there are all the instruction to use the application
- Start a new project and start labeling images.
- [Here](https://blog.roboflow.com/tips-for-how-to-label-images/) are some tips to correctly label our images
![Labeled Images](images/labeled_images.png)
## Data augmentation
- Sign in with your acccount in [roboflow](https://roboflow.com/)
- Upload your dataset to your new project in roboflow
- Apply data augmentation techniques
- Create your dataset
- Download the new dataset in Pascal voc format
## Train the mobilenet ssd neural network
- Fisrt download this [file](https://drive.google.com/u/0/uc?id=1rKiFl4WwzcbQ4Qbs_y4MbU9IGI3dfzLS&export=download) and install the requirements file
- In the data folder you will move the dataset from roboflow
- Unzip the your data, it should look like this.
![Folder](images/folder.png)
