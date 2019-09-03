#Dog Breed


Blog Post Link: 
Motivation
The project is aimed at developing an algorithm to identify the breed of a dog. Moreover, if the input image is a human one, the algorithm should rightly identify it so, and also spit out the closest resembling dog breed. Towards this end, various deep learning architectures along with other models are explored and fine-tuned.

The origin of the image classification problem using Deep Learning, in general, links back to the ImageNet Large Scale Visual Recognition Challenge. Hence, the ImageNet challenge serves as the main inspiration for the project. Also, this project was originally developed by Udacity as one of its various options for a Data Scientist Capstone Project. The goal of this exercise is to solve the problem by building a dog breed classification model.

The data sets used in the project are:

Images of different breeds of dogs (133 of them).
Image of human faces.
The instructions to download the images are provided below.

Requirements
Python 3.5 or higher
OpenCV
Matplotlib
Numpy
Scipy
Tqdm
Keras
Scikit-learn
Pillow
Tensorflow
Skimage
IPython Kernel
Note: Most of the requirements can be downloaded from Anaconda

Repository Break-down
images: a folder which contains the various images used in the ipython notebook
dog_breed_classifier.ipynb: the jupyter notebook where the model is built
dog_breed_classifier.html: the html version of the jupyter notebook
extract_bottleneck_features.py: a python helper function to extract bottleneck features
Note: OpenCV's pre-trained models for face detectors, images of dogs and humans, and deep learning architectures along with their bottleneck features are deliberately not included in the repository due to size constraints. For the same reason, trained model weights are also avoided in the repository. You can download the same from the below given links:

OpenCV haarcascade. Download the relevant models and place it in the repo, at the location path/to/repo/haarcascades/haarcascade_frontalface_alt.xml

Dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

Human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

VGG-16 bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

[VGG-19 bottleneck features(https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG19Data.npz) for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

ResNet-50 bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

Inception bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

Xception bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

Results Summary
The summary of the accuracy value used as an evaluation metric for the project for various architectures is given below:

Architecture	Trainable Parameters	Train Accuracy	Valid Accuracy	Test Accuracy
Custom	24,831,909	97.6%	5.03%	4.19%
VGG16	68,229	63.58%	49.7%	49.76%
VGG19	68,229	61.74%	48.14%	50.0%
ResNet-50	272,517	99.82%	82.75%	79.9%
Inception	272,517	98.88%	86.23%	77.75%
Xception	272,517	97.98%	84.91%	83.25%
