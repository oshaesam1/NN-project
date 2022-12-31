# NN-project

Given the dataset of Sign up 'Turkey Ankara Ayranci Anadolu High School's Sign
Language Digits' , (https://github.com/ardamavi/Sign-Language-Digits-Dataset )

### Dataset Preview:

|<img src="Examples/example_0.JPG">|<img src="Examples/example_1.JPG">|<img src="Examples/example_2.JPG">|<img src="Examples/example_3.JPG">|<img src="Examples/example_4.JPG">|
|:-:|:-:|:-:|:-:|:-:|
|0|1|2|3|4|
|<img src="Examples/example_5.JPG">|<img src="Examples/example_6.JPG">|<img src="Examples/example_7.JPG">|<img src="Examples/example_8.JPG">|<img src="Examples/example_9.JPG">|
|5|6|7|8|9|

### Details of project:

- Training using normalized RGB image and  gray images

- Spliting  data to 2 parts:
  - Training (80%) (Applying cross validation during training).
  - Testing(20%).

- Building 2 different Neural Network architectures that can detect the digit of a
given image(change number of hidden layer, number of neurons in each
hidden layer).

- Building a convolutional neural network model that can detect the digit of a
given image(change number of conv layer , pooling layers,...).

- Comparing NN performance against SVM classifier 
