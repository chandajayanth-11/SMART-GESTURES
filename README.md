# SMART-GESTURES 
Sign language conversion faces challenges due to the lack of portable solutions. We're using machine learning and deep learning to improve this. Sign language helps individuals with hearing and speech disabilities communicate better, but it can be confusing for those unfamiliar with it. To bridge this gap, we're introducing American Sign Language recognition with deep learning techniques.

# OBJECTIVE: 
The primary objective of this project is to build a Real-Time Gesture Recognition 
Model. This model can be proposed as a baseline model for sign interpreter, 
which automatically converts sign language into written output to make 
communication for dumb people easy. 

**Sign Images**:  Hand gesture images are collected from surrounding environment. 
These are the different hand gesture sign images collected for training the CNN 
model for the recognition for signs. 

**Gray Scaling**: Gray-scaling is the process of converting a continuous-tone image 
to an image that a computer can be able to manipulate. While gray scaling is an 
improvement over monochrome. Here the collected data undergoes color 
conversion where the image is converted into grayscale. The data collected 
earlier split into training and testing data. 

**Training Data**: For evaluating models, separating data into training and testing 
sets is an important part. Typically, when you separate a data set into a training 
set and testing set, most of the data is used for training, and smaller portion of the 
data is used for testing. This data is used to fit and tune your models. For images 
of training data collection consists of 300 images of each hand gesture. This 
phase trained the model by extracting the features present in given training 
dataset. 

**Testing Data**: A subset to test the trained model. A testing data is a dataset that 
is independent of the training dataset and follows the same probability 
distribution as the training dataset. Also, a set of observations used to evaluate 
the performance of some model using performance metric. And is important that 
no observations from the training set are included in the test set. These are put 
aside as “unseen” data to evaluate your models. For images of testing data 
collection consists of 250 images of each hand gesture. 

**Neural Network**: Neural Network is a human brain algorithm that is designed to 
recognize pattern in numerical datasets. Image, text audio, video, etc., are the 
examples of real-world data; that needs to transform into numerical vectors to use 
neural networks. This network is composed of different layers and a layer is 
made of multiple nodes. The mapping of the input to the output is performed by 
some activation function. The goal of neural network is to approximate some 
function ‘f’. 

**Convolutional Neural Network**: Convolutional Neural Network (CNN) is a 
class of deep, feed-forward artificial neural networks that has been successfully 
applied to analyzing visual imagery. CNN use variation of multilayer 
perceptron’s designed to require minimal processing. CNNs has the ability to be 
able to detect abstract and complex features that makes them so attractive in 
image recognition problem. 

Complete file: https://drive.google.com/drive/folders/1ZdHY5AcIhR9IQYHEKjOCrjrfcZFhrKw9?usp=sharing
