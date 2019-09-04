Libraries Used : Pandas, Numpy, Scikit Learn, Scipy, ResNet, VGG, CNN, Keras, Tensorflow.

link to the post : 

Motivation for the Project : As this is a Capstone project in Udacity Data Scientist Nanodegree Program, the Dog breed classifier is very interesting as it uses all the bells and whistles of neural networks with CNN and also tranfer learning with ResNet.

Files in the Repo :  https://www.linkedin.com/pulse/identifying-dog-breeds-using-cnn-mac-mohan


Readme.md         - Meta data (summary ) of the code that is available in the repo.
dog_app.ipynb    - Python Notebook for the Solution, to create the model and test the same on dog breed images.

Summary of the Results : The model gave a pretty good accuracy of above 79.9% and after hyper parameter tuning it was acceptable and eventually tranfer learning with RESNET made the solution better than expected.

Acknowledgements : To all my mentors and guides. Inspiration given by my family and colleagues.

Code Details : Code detects dogs from other images, and  pretrained model like RESNET-50 with imagenet weights are used initially to create the detector. Once done, the vanilla CNN is created and fed with 4D tensors, for training. Once trained  the test accuracy is also validated. Transfer learning is done with RESNET and gets a test accuracy of 79.90 %.
 
