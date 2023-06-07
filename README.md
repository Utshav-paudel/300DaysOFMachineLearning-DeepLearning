![machine learning image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5b5aa0e37fc4f1f2904987b7cd6bd018398c9f16/images/ml%20and%20dl.avif)
| Books and Resources | Status of Completion |
| ----- | -----|
| 1. [**Machine Learning Specialization**](https://www.coursera.org/specializations/machine-learning-introduction?page=1) | ✔️ |
| 2.[**Hands-On Machine Learning with Scikit-Learn and TensorFlow**](https://github.com/ageron/handson-ml3)| 🏊 |

| Project Completed |
| ----------------- |
| 1. [**Medical Insurance Price Prediction**](https://github.com/Utshav-paudel/Medical_Insurance_cost-Predictor) |
| 2.[**Iris Flower Classification**](https://github.com/Utshav-paudel/Iris-flower-calssification-webapp) |
# Day1 
### 1. Supervised learning
Learns from being given `right answers`.  
Supervised machine learning is based on the basis of labeled data.First the data is fed to the model with both input and output and later on test data is given to make prediction by model. 
some algorithm used in supervised learning with their uses are :  
* Regression : House price prediction.
* Classification : Breast cancer detection.  
### 2. Unsupervised learning  
Learns by finding pattern in unlabelled data.
Unsupervised learning is different from supervised learning as it is not provided with labelled data.The algorithm work by finding pattern in data.  
some algorithm used in unsupevised learning with it uses are:
* Clustering : Grouping similar data points together e.g: grouping of customer , grouping of news,DNA microarray.
* Anomlay detection: Finding unusal data points e.g: fraud detection , quality check.
* Dimensionality reduction : Compress data using feweer numbers e.g : Image processing.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day2
### Univariate Linear regression  
Univariate linear regression has one dependent variable and one independent variable. With the help of indendent variable also known as input,feature we predict the output. Firstly we provide training set to our model and later on we predict the output using training set.
### Cost function   
A cost function is a measure of how well a machine learning model performs by quantifying the difference between predicted and actual outputs.  
`lower the value of cost function better the model`  
![cost function](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/276707b43ff92bd2f822312e545e90d26c4358c9/images/day2%20costfunction.png)  
* [linear regression model](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/276707b43ff92bd2f822312e545e90d26c4358c9/code/day2%20univariate%20linear%20regression%20model.ipynb)
* [cost function](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/276707b43ff92bd2f822312e545e90d26c4358c9/code/day2%20cost%20function.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day3
### Gradinet descent
![gradient descent img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/1c0e9bd63ea4a5d41d8f417b4da9650b1dc3c567/images/day3%20gradient%20descent.png)  
Gradient descent is an algorithm for finding values of parameters w and b that minimize the cost function J.It is made cleared in below image.  
![gradient descent equation img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/1c0e9bd63ea4a5d41d8f417b4da9650b1dc3c567/images/day3%20gradinet%20descent%20equation.png)
* [gradient descent](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/41535e5806b7fc119dc833a4486e6e7d15e9bfbe/code/day5%20gradient%20descent.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day4
### Learning rate
Learning rate `alpha` in gradient descent should be optimal.
* If learning rate is too small gradient descent may be too slow and take much time.  
* If learning rate is too large gradient descent may overshoot and never reach minimum i.e fail to converge,diverge.  
![learning rate](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/2fd63f02907afd95dfec81f13eb576065a5a0f29/images/day4%20learning%20rate.png)

* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day5
### Multiple linear regression
Multiple linear regression in machine learning model that uses multiple variables called as features to predicts the output.
![multiple linear regression model](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/41535e5806b7fc119dc833a4486e6e7d15e9bfbe/images/day5%20multiple%20linear%20regression.png)
### Vectorization 
In muliple linear regression calculation is done using vectorization as it perform all calculation simultaneously and parallely and speed up the arithmetic operations.
![vectorization img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/41535e5806b7fc119dc833a4486e6e7d15e9bfbe/images/day5%20vectorization.png)
* [vectorization in numpy](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/41535e5806b7fc119dc833a4486e6e7d15e9bfbe/code/day5%20numpy%20vectorization.ipynb)
* [Multiple linear regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/4291831060fcce086ac8677076c92803d42d9fb6/code/day6%20multiple%20linear%20regression.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day6
### Feature scaling 
When you data features has very large range,too small range gradient descent may take large time so data is rescaled to normal similar range called feature scaling.
some popular feature scaling techniques are:  
* mean normalization
* Z score normalization  
![feature scaling type](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/4291831060fcce086ac8677076c92803d42d9fb6/images/day6%20feature%20scaling%20techniques.png)   
Feature scaling visual representation  
![feature scaling representation](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/4291831060fcce086ac8677076c92803d42d9fb6/images/day6%20feature%20scaling%20representation.png)
### Choosing correct learning rate 
First we make sure gradient descent is decreasing over the iteration by looking at learning curve if it is working properly we choose correct learning rate by starting with smaller learning rate and increase it gradually.
* [feature scaling  and learning rate](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a5fad158c61e2bc72d1d088909a9ba4aafd4e92a/code/day6%20feature%20scaling%20and%20choosing%20learning%20rate.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day7
### Feature engineering 
Feature engineering means designing newfeatures by transforming or combining original features which maybe very important in prediciting the output.  
for e.g: we have to predict the price of swimming pool and we have length breadth and height of swimming pool as features now we can used feature engineering to create our new feature which is volume which is very important in predicting the price of swimming pool.
### Polynomial regression
Polynomial Regression is a regression algorithm that models the relationship between a dependent(y) and independent variable(x) as nth degree polynomial. The Polynomial Regression equation is given below:  
y= b0+b1x1+ b2x12+ b2x13+...... bnx1n   
It is used incase of non linear dataset.  
![](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/cbcb932cb36976f30699482499555b839ce77a42/images/day7%20polynomial%20regression.png)
* [featured engineering and polynomial regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e6e8b83dc852a9551557585ee93b65c48832e2df/code/day7%20feature%20engineering%20and%20polynomial%20regression.ipynb)
* [Linear regression using scikit learn](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e6e8b83dc852a9551557585ee93b65c48832e2df/code/day7%20linear%20regression%20using%20scikit%20learn.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day8
### Classification
Classification is a type of supervised learning in machine learning, where the goal is to predict the class label of an input data point.For example, we may want to classify emails as spam or not spam, or classify images as cats or dogs.
### Logistic regression  
Logistic regression is a type of algorithm used for classification problems. It works by estimating the probability of an input data point belonging to a particular class. For example, it may estimate the probability that an email is spam or not spam, or the probability that an image is a cat or a dog.

To estimate these probabilities, logistic regression uses a mathematical function called the logistic function, which maps the input data to the probability space. The logistic regression algorithm then learns the relationships between the input features and the target class by adjusting weights, or coefficients, assigned to each input feature. These weights are adjusted to maximize the probability of the correct classification.

In the end, logistic regression outputs the predicted class for each input data point, based on the estimated probabilities. This can be useful for a wide range of classification tasks, from predicting diseases to detecting fraud.
![logistic reg img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/317f551e71cd3e2deb546e7f37c578639d3c6f27/images/day8%20logistic%20regression.png)
* [classification](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/317f551e71cd3e2deb546e7f37c578639d3c6f27/code/day8%20classification.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day9
### Sigmoid function
The sigmoid function is a mathematical function that maps any input value to a value between 0 and 1. It is commonly used in logistic regression to model the probability of a binary outcome. The sigmoid function has an S-shaped curve and is defined as follows:

σ(z) = 1 / (1 + e^(-z))

where z is the input value to the function. The output of the sigmoid function, σ(z), is a value between 0 and 1, with a midpoint at z=0.

The sigmoid function has several important properties that make it useful in logistic regression. First, it is always positive and ranges between 0 and 1, which makes it suitable for modeling probabilities. Second, it is differentiable, which means that it can be used in optimization algorithms such as gradient descent. Finally, it has a simple derivative that can be expressed in terms of the function itself:

d/dz σ(z) = σ(z) * (1 - σ(z))

This derivative is used in logistic regression to update the model coefficients during the optimization process. 
* [Sigmoid function](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/8030ab207dc51472a4ad8cc13fd211587132a4ee/code/day8%20sigmoid%20function.ipynb)
### Decision boundary
The decision boundary is the line that separates the area where y=0 and where y=1.It is create by our hypothesis function.
In logistic regression, the decision boundary is the line (or hyperplane in higher dimensions) that separates the different classes of the target variable. The decision boundary is determined by the logistic regression model, which uses the input variables to predict the probability of belonging to a certain class.  
![decision boundary image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/55bb303deeace7b4800319a38312bfe0202fc59d/images/day9%20decision%20boundary.png)

* [decision boundary](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/8030ab207dc51472a4ad8cc13fd211587132a4ee/code/day8%20decision%20boundary.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)\
# Day10
### Gradient descent in Logistic regression  
Logistic Regression Ŷi is a nonlinear function(Ŷ=1​/1+ e-z), if we put this in the above MSE equation it will give a non-convex function as shown:  
![loss function image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a3e7cb1c6715f32f4f2744083b8eb6f69374f56c/images/day10%20cost%20function%20in%20logistic%20regression.jpg)
* When we try to optimize values using gradient descent it will create complications to find global minima.

* Another reason is in classification problems, we have target values like 0/1, So (Ŷ-Y)2 will always be in between 0-1 which can make it very difficult to keep track of the errors and it is difficult to store high precision floating numbers.

The cost function used in Logistic Regression is Log Loss.  
![log loss image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a3e7cb1c6715f32f4f2744083b8eb6f69374f56c/images/day10%20logloss.png)  
Cost function for logistic regression  
![cost function image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/c5b6cff9ce3fbe68c4fa6864ecb8787a9eb48516/images/day11cost%20function%20in%20logistic%20regression.png)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day11
### Gradient Descent in logistic regression  
Gradient Descent in Logistic Regression is an iterative optimisation algorithm used to find the local minimum of a function. It works by tweaking parameters w and b iteratively to minimize a cost function by taking steps proportional to the negative of the gradient at the current point.  
Gradient descent in logistic regression looks similar to gradient descent in linear regression but it has different value for function.  
![gradient descent in logistic regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/15bcacd6e5d8f971d54629bbf414fe63aa17b0df/images/day11%20gradient%20descent%20for%20logistic%20regression.png)
* [gradient descent in logistic regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/aecd0846a7e0f80efa23131e0eed695715df4c09/code/day11%20gradient%20descent.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day12
### Underfitting 
It is a situtation when the training set doesnot fit well. It happen when data has high bias.  
### Overfitting  
It is a situation when the training set fit extremely well . It is also known as data with high variance.
### Addressing overfitting 
* Collecting more training example
* Select features include/exclude
* Reduce the size of parameters i.e "Regularization".
* [overfitting](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/82251c369534b9dd1fa500b5e7c39ac8baeb0015/code/day12%20overfitting%20example.ipynb)
### Regularization  
Regularization is a technique to reduce the parameter and prevent overfitting of data. It has a term called lambda whose value if larger result underfitting and smaller result overfitting it also called penalty term.  
![regularization term](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/367b379e09f12e6493fc91b24b7c617399eaacf4/images/day12%20regularization%20image.png)
* [Regularization in linear regression and logistic regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/82bf8ece95114cc3d2b597749553a888514942da/code/day13%20regularization%20in%20linear%20regression%20and%20logistic%20regression.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day13
### Neural network
Neural network is an computer algorithms that try to mimic the brain.neural network is made of a input layer that take input data and hidden layer does all the computation and output layer displays the output.  
![neural network image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/86901d1f2b3b8017f98025ec7f4310ff38d602aa/images/day13%20neural%20network.svg)  
Why neural network ?  
Neural network is necessary because it increase performance of machine learning algorithm compared to traditional algorithm like linear regression and logistic regression because it uses multiple and more algorithm in a neural network to make better prediction and performances.  
![why neural network](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/86901d1f2b3b8017f98025ec7f4310ff38d602aa/images/day14%20why%20neural%20network.png)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day14
### Neural network notation  
In neural network.
* neuron is represneted by subscript.
* neural network layer is represented by superscript.
### Forward propagation in neural network  
Forward propagation refers to storage and calculation of input data which is fed in forward direction through the network to generate an output. Hidden layers in neural network accepts the data from the input layer, process it on the basis of activation function and pass it to the output layer or the successive layers. Data flows in forward direction so as to avoid circular shape flow of data which will not generate an output. The network configuration that helps in forward propagation is known as feed-forward network.  
* [neuron and layer](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/f355d3a41ea555a8183799abadabff766fab088f/code/day14%20neuron%20and%20layer.ipynb)

* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day15
### Neural network implementation in tensorflow
Neural network can be easily implemented in tensorflow as below:  
* [neural network implementation in tensorflow](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/af55e5c1ed24a4083b95a66e16d91e0c52984f69/code/day15%20coffee%20roasting%20in%20tensorflow.ipynb)
![neural network implementation in tf](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/be3f04d372d0afa4f03c25c18cf1a3df2c75d8fa/images/day15%20neural%20network%20implementation%20using%20tensorflow.png)
### AGI  
AI is mainly classified into two type: ANI and AGI
* AGI:An AGI is a hypothetical intelligent agent that can learn to accomplish any intellectual task that human beings or other animals can perform. It is defined as an autonomous system that surpasses human capabilities in the majority of economically valuable tasks

* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day16
### Vectorization in neural network
In neural network vectorization helps to perform calculation simultaneously and save a lot of time. It can implemented as :  
![vectorization in neural network](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a05af1a6599eb33e7aea0dc22857abb590961275/images/day16%20vectorization%20for%20neural%20network.png)
### Neural network implementation in code
![neurall network representation](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a05af1a6599eb33e7aea0dc22857abb590961275/images/day16%20neural%20network%20representation.png)  
![code](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a05af1a6599eb33e7aea0dc22857abb590961275/images/day16%20neural%20network%20code%20for%20above%20representation.png)
* [Neural network to identify handwritten binary](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/13c7fdd68ca420478aedbffee1d1f3ee2dba9bdf/code/day16%20handwritten%20digit%20recognition%20neural%20network.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day17
### Model Training steps  
Model training is simplified in 3 steps :  
1. Specify how to compute output given input x and parameters w,b (define model)  
  * linear regression (y = ax + b) 
  * logistic regression (y = 1/(1 + np.expt(-z)))  
2. Specify loss and cost  
  * Mean square error 
  * Logistic loss (BinaryCrossentropy) (loss = -y*np.log(f_x) - (1-y)*np.log(1-f_x)  
  Note: Cost is the sum of loss for all training examples.  
3. Train on data to minimize cost(Gradient descent)  
  w = w - alpha*dj_w  
  b = b - alpha*dj_b   
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
### Activation function
There are different activation function for different purpose some of the most commonly used are :  
* Linear acitvation function(activation='linear')  
This is used for regression problem where result is negative/positive.
* ReLU (activation = 'ReLU')  
This is used for regression problem where result should be positive always and it is faster as compared to sigmoid function.
* Sigmoid function(activation='sigmoid')   
It is used for classification problems where result must be on/off and it is slowere as compared to ReLU.  
NOTE:`For hidden layer we choose ReLU as activation and for output layer we choose activation according to our problems,because if we choose sigmoid in hidden layer than neural network becomes very slow so it better to choose Relu in hidden layer`  
![activation function](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/87630d03f23299852372e56f49b5c4f5be8789c9/images/dasy17%20activationn%20function.webp)
* [ReLU implementaion](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/87630d03f23299852372e56f49b5c4f5be8789c9/code/day17%20ReLU%20activation.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day18
### Multiclass classification 
Target y can take on more than two possible values. In this case of multiclass classification we use Softmax regression.
### Softmax regression 
Softmax regression is the generalization of logistic regression for multiple classs.   
Its output is calculated as:  
![Softmax regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a8bb8ecf939c1d1b76dc31d62b8367f34ab7e437/images/day18%20softmax%20regression%20.png)

### Cost for softmax regression
Cost for softmax regression is also known as cross-entropy loss. It is obtained as.
![Cost for softmax regression](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/a8bb8ecf939c1d1b76dc31d62b8367f34ab7e437/images/day18%20Crossentropy.png)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day19
### Improved Implementation of softmax/logistic regression in neural network
Our normal implementation of softmax cause some of numerical roundoff error so for the more numerical accurate implementation of softmax regression we use linear activation in output layer and passing `from_logits = True as parameter in loss at model.compile()`.  
You can get more insight by looking at image below:  
![Numerical accurate implementation of softmax](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/78b44e1cbd3aec966e8ec070377f761fc5f80d40/images/day19%20imporved%20implementation%20of%20softmax.png)
* It can be implemented similarly for softmax neural network.
* [Numerically accurate implementation vs normal implementation](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/78b44e1cbd3aec966e8ec070377f761fc5f80d40/code/day19%20softmax%20prefered%20way%20vs%20not%20preferred%20way.ipynb)
### MultiLabel classification
Multilabel classification is a type of classification problem in machine learning where each instance can be assigned to multiple classes or labels simultaneously. In other words, instead of predicting a single class for an instance, the goal is to predict a set of labels that are applicable to that instance.   
Here is difference between multiclass and multilable classfication 
![multi label classification](Multilabel classification is a type of classification problem in machine learning where each instance can be assigned to multiple classes or labels simultaneously. In other words, instead of predicting a single class for an instance, the goal is to predict a set of labels that are applicable to that instance.)
* [Multi class classification](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/78b44e1cbd3aec966e8ec070377f761fc5f80d40/code/day%2019%20multiclass.ipynb)
### Advanced optimization
Adam algorithm is used for advanced optimization in neural network.
* If learning rate is smaller adam algorithm increases it automatically.
* If learning rate is larger then adam algorithm decreases it automatically.
Note : It stands for Adaptive Moment estimation.
It is used as:  
```python
model.compile( optimizer=tf.keras.optimizers.Adam(learning_rate=1e-3), loss = tf.kearas.losses.SparseCategoricalCrossentropy(from_logits=True))
```

### Additional Layer types:
Some of layer types of neural network are : 
* Dense Layer (Fully Connected Layer): A dense layer is a basic layer where each neuron is connected to every neuron in the previous layer. It is characterized by its weight matrix, bias vector, and activation function. Dense layers are commonly used in feedforward neural networks and can learn complex patterns and relationships in the data.

* Convolutional Layer: Convolutional layers are primarily used in convolutional neural networks (CNNs) for analyzing grid-like data, such as images. These layers perform convolutions, applying filters to the input data, and capturing local patterns and features. Convolutional layers are effective in image recognition, object detection, and other computer vision tasks.   
Convaulational neural network are faster in computation and need less training data as compared to Dense Layer.  
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day20
### Back Propagation  
Backpropagation, or backward propagation of errors, is an algorithm used in machine learning to adjust the parameters of a neural network by calculating the gradients of a loss function with respect to the network's weights and biases. It propagates the error from the output layer to the input layer, allowing the network to learn and improve its predictions.
* [Backward propagation](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/32905b341938026ab9db9af034a4e664f664e5c5/code/day20%20backward%20propagation.ipynb)
### Debugging a learing algorithm
When we have large error in prediction we can debugg or learning algorithm as follow:  
* Get more training examples.
* Try smaller set of features.
* Try getting additional features.
* Try adding polynomial features.
* Try decreasing/increasing lamda regularizing parameter
### Evaluating a choosen model: 
You can evaluate a model by splitting data into trian/test and calculating cost for both training set and test set .
### Model selection:
The most effective way of model selection is by
* splitting data into train/cross validation /test set
* Calculating error for cross validation set and selecting model with less cross validation error .
* Calculation error for test data of model with less cross validation error.
* [Model selection using train/cv/test](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/fae56941f9d55feccb10a03ef3fdce4625b56863/code/day20%20train_crossvalidation_test%20split%20for%20model%20selection.ipynb)
### Machine learning diagnostic
A test that you can run to gain insight into what is/isn't working with a learning algorithm to gain guidance into improving its performance .
Ml model can be diagonse by looking at bias and variance:   
When model has high bias and variance it is not doing well.   
![how to diagnose high bias and variance](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/346f73b367af2df6c84ca81a038b66d6ad7d22b0/images/day21%20diagonising%20high%20bias%20and%20variance.png)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day21
### Bias/Variance
* High bias: When model has large difference between baseline performance and Training error then it is called high bias and it also indicates underfitting.
* High variance: When model has large difference between training error and cross validation error then it is called high variance and it also indicates overfitting.
* High bias and variance: When model has large difference between training error , cross validation error and baseline performance then it is called both high bias and high variance.  
![image show bias and variance](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/346f73b367af2df6c84ca81a038b66d6ad7d22b0/images/day21%20bias%20and%20variance.png)
### Choosing regularization parameter
To choose good regularization paramter.
* First,Apply all regularization value and get different cross validation error and the smallest cross validation error indicated a good regularization term.
* NOTE : Right model neither has high variance and neither has high bias
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day22
### Diagonising bias and variance
#### If your algorithm has high bias:
* Try getting additional features.
* Try increase polynomial degree.
* Try decreasing regularization term.
#### If your algorithm has high variance:
* Getting more training examples.
* Trying decreasing set of features.
* Try increasing regularization term.
### Bias and Variance in neural network:
* If your neural network has high bias try increasing size of neural network.
* If your neural network has high variance try increasing training sets.
Note : Most probably larger neural network perform well as long as appropriate regularization term is choosen.
![bias and varince in neural net](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/123ae0650d91421c315b670aed72f4c7ec9c659b/images/day22%20bias%20and%20variance%20in%20neural%20network.png)
* [Diagonising bias and variance](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/123ae0650d91421c315b670aed72f4c7ec9c659b/code/Day22%20diagonising%20bias%20and%20variance.ipynb)
*  📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day23
### Iterative loop of ML Development
Ml development revolve around following steps:
* Choosing architecture(model,data,etc)
* Training model
* Diagnostics(bias,variance and error analysis)
![iterative loop img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/da0508acb47b6af85c845293f74e0dbc47b51ae7/images/day23%20iterative%20loop%20of%20%20ml%20development.png)
### Error analysis
It is the process to isolate,observe and diagnose erroneous ML predictions to understand pockets of high and low performance to the model.
### Adding more data
Adding more data is mostly useful to make better predictions and data can be added by following ways:  
1. Data augmentation: Modifying an existing training example to create new training example. e.g: Data augmentation by adding distortion.  
2. Data synthesis: Using artifical data inputs to create a new training example. It is mostly used for computer vision applications.
### Transfer learning 
Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task.  
It is a popular approach in deep learning where pre-trained models are used as the starting point on computer vision and natural language processing tasks given the vast compute and time resources required to develop neural network models on these problems and from the huge jumps in skill that they provide on related problems.
* Download neural network parameters pretrained on large dataset with same input type (e.g: images,audio,text) as your application (or train your own).
* Further train(fine tune) the network on your own data.
*  📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day24
### Full cycle of machine learning project 
Machine learning project is iterative process which is as below:  
![ml lifecycle](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/dfe65718b2b6c3b14e6fcf8c1e654b64afd4a713/images/day24.png)
### Deployment 
Mlops focuses on making ml model to be used in largescale and deployment is basically done by:
![ml deployment](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/dfe65718b2b6c3b14e6fcf8c1e654b64afd4a713/images/day24%20deployment%20of%20ml%20model.png)

### ethics,bias and faireness of machine learning
While developing machine learning application we have to take care of biasness and negative case like :  
1.Deepfake  
2.Genrating fake content for commercial and political purposes  
3.Ml model biasing in loan provider,job selection.

### Precision/recall
* precision : It tell of all positive prediction how many are actually positve.
* recall : It tell of all real positive cases how many are actually predicted positive.
![precsion recall img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/dfe65718b2b6c3b14e6fcf8c1e654b64afd4a713/images/day24%20precision%20and%20recall.png)
### Trading off precsion and recall 
* When threshold is higher, precision become higher and recall lower down
* When threshold is lower, precision become lower and recall become higher.
NOTE : To select better precsion and recall value we use `F1 score` which is the harmonic mean of precision and recall.  
* [Summary of Advance learning algorithm](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/dfe65718b2b6c3b14e6fcf8c1e654b64afd4a713/code/day24%20summary%20of%20advanced%20learning%20algorithm.ipynb)
*  📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day25
### Decision Tree
A decision tree is a type of supervised machine learning used to categorize or make predictions based on how a previous set of questions were answered. The model is a form of supervised learning, meaning that the model is trained and tested on a set of data that contains the desired categorization. 
![decision tree image](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/c47f3b6ac073db8e2d634ef749042dca8ad9eab2/images/day25%20decision%20tree.png)
### Decision tree learning 
1. How to choose what feature to split at each node ?  
* Maximize purity
2. When to stop splitting 
* When a node is 100% one class
* when splitting of node will exceed a maximum depth
* when imporovements in purity score are below a threshold
* when no. of examples in a node is below a threshold.
*  📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day26
### Measuring purity
In decision tree entropy is the measure of level of impurity and helps to find purity of classes. lower impurity means higher purity.  
![entropy](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e3a817ab172d6abf9c552365c2842ed09621a314/images/day26%20entropy%20as%20impurity.png)
### Information gain
We can calculate the information gain by subtracting the weighted average entropy of the resulting subsets from the entropy of the original node. The formula for information gain is:  
Information Gain = Entropy(node) - Σ((subset_size/total_size) * Entropy(subset))  
* By maximizing information gain, decision trees aim to find the attribute that provides the most useful and informative splits, leading to more accurate classification.
### Decision tree learning
* Start with all examples at the root node
* Calculate information gain for all possible features, and pick the one with the highest information gain
* Split dataset according to selected feature, and create left and right branches of the tree
Keep repeating splitting process until stopping criteria is met:
1. When a node is 100% one class  
2. 2. When splitting a node will result in the tree exceeding a maximum depth  
3. 3. Information gain from additional splits is less than threshold When number of examples in a node is below a threshold  
![dc tree](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e3a817ab172d6abf9c552365c2842ed09621a314/images/day26%20decision%20tree%20splitting.png)
# Recursive splitting
Recursive splitting refers to the iterative process in decision tree construction where a dataset is divided into smaller subsets based on specific conditions. It involves recursively selecting attributes to split on and creating branches that further partition the data until a stopping criterion is met, resulting in a tree-like structure.
*  📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day27
### One hot encoding
If a categorical features can take on k values, create k binary features(0 or 1 values) is call one hot encoding.
### Spitting for continuous variable
For continuous variable we have to choose threshold with higher information gain and split on the basis of that threshold.
### Regression tree
It is a decision based tree used to predict continous variables.
* for selecting best split for regression tree we find variance reduction and the biggest variance reduction is considerd to be the best split.
* Note: Variance reduction = variance of root node - average weighted variance of leaf node
* [Regression tree](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/61a61fb8b16300dbe9cd84a5196a99f0def98ce3/code/day27%20decision%20tree.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day28
### Tree ensemble 
Single decision tree is very sensitive to data so the process of combining many decision tree to build more robust system is called tree ensemble.
the prediciton of tree ensemble is obtained by majority result of tree.
### Random forest algorithm
A random forest algorithm is a machine learning technique that combines the predictions of multiple decision trees to make more accurate and robust predictions. It works by creating an ensemble of decision trees, where each tree is trained on a random subset of the data and uses a random subset of features. The final prediction is then made by averaging or voting the predictions of all the trees in the forest. The random forest algorithm is effective at handling complex datasets, handling missing values, and avoiding overfitting.
* Random forest has two term that explain this algorithm they are Bootstrapping and aggregation and the combination of this is called Bagging
* Boostrap : The selection of subset of training example (sampling with replacement) where the training example can be repeatded is called bootstrap
* Aggregation : The selection of majority of result from ensembles tree is called aggregation.
![](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e9f5ce59b23328fc72b9d06af34e1ba5c1ed6db3/images/day28%20random%20forest.png)
### XG Boost
In XG boost we basically pick the training examples that were misclassified previously instead of training all samples.
It is implemented as :   
![xg boost img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e2d84dfea2fc053bd1c6de84520adbc9713c4a93/images/day28%20Xg%20boost.png)
### When to use decision tree 
* Decision tree works pretty well on structured data but is not recommended for unstructured data like audio,video and images 
* It is faster compared to neural network
* Small decision trees may be human interpretable.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day29
### Unsupervised learning
Machine leanring algorithm that find patterns on unlabelled data.
### K-means Clustering Algorithm
K-means clustering is an unsupervised machine learning algorithm used for partitioning a dataset into K distinct non-overlapping clusters. Each data point in the dataset is assigned to the cluster with the nearest mean (centroid). The algorithm aims to minimize the within-cluster variance, also known as the "inertia."

Here's a step-by-step overview of the k-means clustering algorithm:

* Initialization: Randomly select K data points from the dataset as the initial cluster centroids.

* Assignment: Assign each data point to the nearest centroid. This is done by calculating the Euclidean distance (or other distance metrics) between each data point and each centroid, and assigning the data point to the cluster with the closest centroid.

* Update: Recalculate the centroids of each cluster by taking the mean of all the data points assigned to that cluster.

* Repeat: Repeat steps 2 and 3 until convergence or a maximum number of iterations is reached. Convergence occurs when the centroids no longer move significantly between iterations or when the algorithm reaches the predefined maximum number of iterations.

* Final Clusters: Once convergence is achieved, the algorithm outputs the final cluster assignments, where each data point belongs to one of the K clusters.  
![k means cluster](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/0b42f7fba067ff92974b209532654e381edc8996/images/day29%20k%20means%20clustering.png)
### Cost function for k-means clustering(distortion)
The cost function for k-means clustering is commonly referred to as the "inertia" or "within-cluster sum of squares." It measures the sum of squared distances between each data point and its assigned centroid within each cluster. The goal of k-means clustering is to minimize this cost function.

Mathematically, the cost function (J) for k-means clustering can be defined as:

J = Σᵢ Σⱼ ||xᵢ - μⱼ||²  
* [K-means clustering sample](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/4957fca69c2b4e65b1964620f40eacf8895fb293/code/day29%20k%20means%20clustering.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day30
### Anamoly detection
Anomaly Detection is the technique of identifying rare events or observations which can raise suspicions by being statistically different from the rest of the observations. Such “anomalous” behaviour typically translates to some kind of a problem like a credit card fraud, failing machine in a server, a cyber attack, etc.
* To apply anamoly detection we use gassuian distribution/normal distribution
### Anamoly detection vs Supervised learning
### Anamoly detection
We will use anamoly detection when there are very small number of example that are positive(anamoly) and large number of negative example .Since small number of positive examples it is hard to learn from training examples.e.g: fraud detection
### Supervised learning
We will use supervised learning when large number of positive and negative examples are present. Since there are enough positive examples to train model and predict supervised learning is effective. e.g Email spam detection
* NOTE: Before using anamoly detection we have to make sure our data is normal.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day31
### Recommender system
Recommender systems are a type of machine learning algorithm used to suggest items to users based on their preferences or behavior. These systems are widely used in various applications like e-commerce, movie streaming platforms, music apps, and more.
### 1.Content based Recommendation
In content-based recommender systems, the algorithm recommends items based on the similarity between the content/features of the items and the user's preferences. The similarity is typically computed using techniques such as cosine similarity or Euclidean distance. Here's an overview of the mathematical steps involved:

* a. Feature Representation: Each item and user is represented as a feature vector. Let's denote an item's feature vector as x and a user's preference vector as p. These vectors consist of numerical values that represent the attributes or characteristics of items or users.

* b. Similarity Measure: The similarity between two feature vectors, x and p, can be computed using cosine similarity. The cosine similarity between x and p is defined as:

similarity(x, p) = (x · p) / (||x|| * ||p||)

where (x · p) represents the dot product of vectors x and p, and ||x|| and ||p|| denote their respective Euclidean norms.

* c. Recommendation: To recommend items to a user, the system calculates the similarity between the user's preference vector and the feature vectors of all items. The system then ranks the items based on their similarity scores and recommends the top-rated or most similar items.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
### Collaborative Filtering Recommender Systems:
Collaborative filtering recommender systems make recommendations based on the preferences or behavior of other similar users or items. Let's explore the two main approaches: user-based and item-based collaborative filtering.

* a. User-based Collaborative Filtering:

In user-based collaborative filtering, the algorithm finds similar users based on their past interactions or ratings and recommends items that the similar users have liked. Here are the mathematical steps involved:

i. User Similarity: The similarity between two users, u and v, can be computed using techniques such as cosine similarity or Pearson correlation. The similarity score measures the likeness of their past interactions.

ii. Prediction: To predict a user's preference for a particular item, the system combines the ratings of similar users. The predicted rating, denoted as r_hat(u, i), for user u and item i is calculated as a weighted average of the ratings of similar users:
```python
    r_hat(u, i) = ∑ (sim(u, v) * r(v, i)) / ∑ |sim(u, v)|
#where sim(u, v) represents the similarity between users u and v, r(v, i) denotes the rating of user v for item i, and the summation is performed # over all similar users v.
```
where sim(u, v) represents the similarity between users u and v, r(v, i) denotes the rating of user v for item i, and the summation is performed over all similar users v.
iii. Recommendation: The system recommends items with the highest predicted ratings to the active user.
*  Item-based Collaborative Filtering:

In item-based collaborative filtering, the algorithm identifies similar items based on the past interactions or ratings of users. It then recommends items that are similar to the ones the user has already liked. Here's a summary of the mathematical steps involved:

i. Item Similarity: The similarity between two items, i and j, can be computed using techniques such as cosine similarity or Pearson correlation. The similarity score measures the likeness of user preferences for the items.

ii. Prediction: To predict a user's preference for a particular item, the system considers the user's past ratings for similar items. The predicted rating, denoted as r_hat(u, i), for user u and item i is calculated as a weighted average of the user's ratings for similar items:
```python
  r_hat(u, i) = ∑ (sim(i, j) * r(u, j)) / ∑ |sim(i, j)|

  #where sim(i, j) represents the similarity between items i and j, r(u,

```
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day32
### Normalization
Normalization is a technique often applied as part of data preparation for machine learning. The goal of normalization is to change the values of numeric columns in the dataset to use a common scale, without distorting differences in the ranges of values or losing information.
### Limitation of collabrative filtering
How to 
* rank new items that few user have rated ?
* show something reasonable to new users who have rated few items ?
How to use side information about items or users:
* Item: Genre, movei stars, studion...
* User: Demorgraphics(age,gender,location), epressed prefernces,..
Note: This limitation of collabrative filtering can be addressed by content based filetring
### [Tensorflow implementation of collabrative filtreing](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/e34e047cf5b50496b478695c5aad219690b69b18/code/day32%20collabrative%20filetering%20for%20movie%20recommendation.ipynb)
### Content base recommendation
It uses both content and user data and using neural network create vector for content and vector for user and its dot product give prediction.
### Content base recommendation for large items.
When our website or app has large number of content to recommend like thousands and millon of item it is carried out in two steps:
#### 1.Retrival
From large number of content retrival is carried out for selective content for further ranking. for e.g:  
For movies recommendation:  
1.for 10 movies watched by user retrieve similar movies.  
2.for most viewed 3 genres find top 10 movies.  
3.find top 20 movies in country.  
At last combined retrived item in list and remove duplicated and items already purchased.   
#### 2.Ranking
Apply model to retrived data to find suitable item and display ranked item to user.   
Note: Retriving more items result in better recommendation but takes more time to analyse try it offline and find suitable number of retrival for better and relevant recommendations.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
### Day33
#### [Implementation of content based filering](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/cb9ea35528675120c2c2f1f41bd837002fd5d515/code/day33%20content%20based%20filtering%20for%20movie%20recommendation.ipynb)
### Dimensionality reduction
Dimensionality reduction is a technique used to reduce the number of features in a dataset while retaining as much of the important information as possible. In other words, it is a process of transforming high-dimensional data into a lower-dimensional space that still preserves the essence of the original data
* Feature selection : Feature selection involves selecting a subset of the original features that are most relevant to the problem at hand. The goal is to reduce the dimensionality of the dataset while retaining the most important features. There are several methods for feature selection, including filter methods, wrapper methods, and embedded methods. Filter methods rank the features based on their relevance to the target variable, wrapper methods use the model performance as the criteria for selecting features, and embedded methods combine feature selection with the model training process.

* Feature Extraction: Feature extraction involves creating new features by combining or transforming the original features. The goal is to create a set of features that captures the essence of the original data in a lower-dimensional space. There are several methods for feature extraction, including principal component analysis (PCA), linear discriminant analysis (LDA), and t-distributed stochastic neighbor embedding (t-SNE). PCA is a popular technique that projects the original features onto a lower-dimensional space while preserving as much of the variance as possible.
### Principal Component analysis(PCA)
Principal component analysis, or PCA, is a statistical procedure that allows you to summarize the information content in large data tables by means of a smaller set of “summary indices” that can be more easily visualized and analyzed.
*  It works on the condition that while the data in a higher dimensional space is mapped to data in a lower dimension space, the variance of the data in the lower dimensional space should be maximum.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day34
### Step by step calculation of PCA
PCA is used to reduce higher dimension data to lower dimension without losing it essence. PCA can be calculated in following steps:
* Mean centring data
* Finding covariance matrix 
* Finding eigen value and eigen vector 
* Eigen vector with largest eigen value has highest variance and is ready for selction.
* [PCA](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/19d213dde7bdb7b78360ae2e2688be0499efc076/code/day34%20PCA.ipynb)  
After applying PCA to handwritten digit having 784 features we got optimal solution of pca at around 250 that explains nearly to 90% of variance.   
![optimal solution of PCA](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/19d213dde7bdb7b78360ae2e2688be0499efc076/images/day34%20%20optimal%20features%20of%20pca.png)  
### 2D plot of 784 feautres

|![2d plot of 784 features ](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/19d213dde7bdb7b78360ae2e2688be0499efc076/images/day34%202d%20pca%20plot.png) 
### 3D plot of 784 features
![3d plot of 784 features](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/19d213dde7bdb7b78360ae2e2688be0499efc076/images/day34%203d%20pca%20plot.png)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day35
### Reinforcement Learning
Reinforcement learning is a machine learning training method based on rewarding desired behaviors and/or punishing undesired ones. In general, a reinforcement learning agent is able to perceive and interpret its environment, take actions and learn through trial and error. 
It reward is calculated as:  
![reward png](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/84b741cc0d1d1529090a83d92dc4bf50e8c32cf5/images/day35%20reward%20formula)
### Markov Decision Process(MDP)
It state that future depends on current state .  
![MDP](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/84b741cc0d1d1529090a83d92dc4bf50e8c32cf5/images/day35%20reinforcement%20learning.png)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day36
### State action value function
In state action value function, represented by Q(s,a)   
Q(s,a) = Return , If you 
* start in state s
* take action a(once)
* Then behave optimally after that
Note: Behaving optimally means taking action which bring maximum Q(s,a).  
Implementaion of state action value function:
![State action value function img](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/ab4e0367f6e3b922fa20a01c614a11ded789f6d3/images/day36%20state%20action%20function.png)
### Bellman equation
Bellman equation explain the return in two step first one is immediate reward and second one is reward from behaving optimally starting from state s.  
![](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/ab4e0367f6e3b922fa20a01c614a11ded789f6d3/images/day36%20bellman%20equation.png)
### Random stochastic environment 
Due randomness and uncertainity in enviroment it becomes diffcult for reinforcement learning so to avoid this we caluclate Expected return(i.e average return) in placce of return only .   
It is calculated as : Q*(s, a) = E[R(s, a, s') + γ ∑ P(s'|s, a) max(Q*(s', a'))],   
* where E represent average or Expected return .
* [State action value implementation](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/ab4e0367f6e3b922fa20a01c614a11ded789f6d3/code/day36%20state%20action%20value%20function.ipynb)
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day37
### Discrete state and continous state
* Discrete state : It is a state in reinforcement learning where the number of possible state are distinct and countable. Discrete state spaces are common in many RL problems, such as board games, puzzle-solving, and decision-making tasks with a finite number of states.
* Continuous state : It is a state in reinforcement learning where the number of possible state are in continous range . Continuous state spaces are encountered in various RL applications, including robotics, control systems, and real-world scenarios where states are represented by continuous measurements.
### Differences in Discrete and continous state
Discrete state spaces can often be represented using tabular methods, where the agent maintains a value function or a Q-table to learn and update action values for each state. On the other hand, dealing with continuous state spaces often requires `function approximation` techniques, such as using `neural networks, to approximate the value function or policy`. Continuous state spaces also pose challenges for exploration strategies, as the agent needs to explore a potentially infinite space effectively.
### Exploitation(greedy) VS Exploration
It also know as epsilorn greedy policy
* with probability 0.95, pick the action a that maximizes Q(s,a) - Greedy (Exploitation)
* with porbability 0.05, pick action a randomly. (Exploration)
* This means epsilon = 0.05
* Start with high epsilon and decrease gradually
### Refinement of reinforcement learning by minibatches and softupdate
### Mini batches
When we have large number of training examples our iterative process like gradient descent and other iterative process on reinforcement learning like trainin neural network becomes slower so we divide main training examples to differen subsets called mini batches
### Soft Update
Soft update in reinforcement learning refers to a technique used to refine the learning algorithm by updating the parameters of a target network gradually. This process involves interpolating between the parameters of the target network and the parameters of the online network.
* 📚Resources  
course:[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?page=1)
# Day38
### Building of Books recommender system using Collabrative filtering.
Collaborative filtering recommender systems make recommendations based on the preferences or behavior of other similar users or items.
In this book recommendation system I calculated similarity scores between two users to find the euclidean distance and recommendation was made on the basis on two nearer items and most of the collaborative recommender system work like this. 
#### To avoid cold start in collabrative filtering:
* The movie with more the 50 rating was included.
* The user who have rated more than 200 books was included.
Here is snippet of the project hope you get some insight riding this   
![book recommender system](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/d4e06acc0a1f9da8332d9f3c9769f8a2b1fd1151/images/day38%20movie%20recommender%20system.png)
# Day39
### Califorina Housing Price prediction
Started my project on California housing price and cleared my concepts on data pipeling, Batch learning and Online learning, perfomed the fetching and loading of data with EDA to gain some insight on data.  
**NOTE**
* **Batch learning vs Online learning** : Batch learning is commonly used when the dataset can fit into memory and when the computational resources are sufficient to process the entire dataset at once. It is often used in offline scenarios where there is no need for real-time or incremental learning.  
Online learning is particularly useful when dealing with streaming data or when the dataset is too large to fit into memory. It allows for real-time learning and adaptation as new data arrives. Online learning algorithms often have lower memory requirements and can adapt to concept drift, which is the phenomenon where the underlying data distribution changes over time.
* **Cost for linear regression** : Most of the time cost for linear regression is calculated by Root Mean Square Error(RMSE) but when data has lots of outlier we use Mean Absolute Error (MAE)
![calforinaday1](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/24ea2817f4f7092bfa8ff472f0a2b8000dd8183d/images/day39%20Calfornia-dataloading%20and%20Eda.png)
![Eda result](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5bac9c7462071160bf06432031e4bc21bdf2d304/images/day40%20California%20eda%20resul.png)
* 📚Resources
[**Hands-On Machine Learning with Scikit-Learn and TensorFlow**](https://github.com/ageron/handson-ml3)
# Day40
### California Housing Price Prediction continued..
* Today I Created test data , and splitted data on the basis of train-test-split and also with stratifcation split to remove imbalance in data and create same proportion.   
**Creating test data**
![testdata](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5bac9c7462071160bf06432031e4bc21bdf2d304/images/day40%20california%20creating%20test%20set.png)
**Creating Training and test data with random sampling and stratification sampling**
![stratification](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5bac9c7462071160bf06432031e4bc21bdf2d304/images/day40%20traintest%20vs%20strarification%20split.png)
### Different methods of sampling :
1.Random sampling 
2.Systematic sampling
3.Stratified sampling
* Stratified sampling: Stratified sampling can be useful in train-test split when dealing with imbalanced datasets. In this case, the dataset may have significantly different proportions of classes or subgroups. By using stratified sampling, we can ensure that the training and test sets maintain the same distribution of classes or subgroups as the original dataset. This helps to prevent bias and provides a more accurate evaluation of the model's performance.  
![sampling in train test split](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/9d17986685775af19e615468114ec3f0089fcac4/images/day40%20stratification%20to%20solve%20imbalance%20in%20class.png)
# Day41
### California Housing Price Prediction
* **Visualization with geographical data** : I plotted geographical visual with respect to population density and housing price to gain better understanding of data   
![](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5955221f5ea3581accba7a4207088bed30cd68c9/images/day41%20california%20visualization%20of%20geographical%20data%20indication%20housing%20price%20and%20popn.png)
* **Correlation**: Also plotted scatterplot for coefficient of correlation of median_housing price with respect to different features and found out that it has high correlation with median_income but there was some straight line forming in middle of data which need to be filtered before training for better performance.  
![correlation fig](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5955221f5ea3581accba7a4207088bed30cd68c9/images/day41%20california%20correlation%20of%20median_house_price%20with%20features.png)
Here is code hope you gain some insight from it :   
![visualization](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/5955221f5ea3581accba7a4207088bed30cd68c9/images/day41%20california%20housing%20code.png)
![correlation code](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/06802a4eb2c9cd3d53efbc6443c0ad1133d8852a/images/day41%20california%20checking%20for%20correlation.png)
* 📚Resources
[**Hands-On Machine Learning with Scikit-Learn and TensorFlow**](https://github.com/ageron/handson-ml3)
# Day42
### California Housing Price Prediction
### Expermenting with attribute combinations 
* I created some new combination of feature like room per house , bedroom ration, population per house and found that room per house has done well then other features, it got some high negative correlation that indicated the less bedroom ratio more the price.
* Also Prepared data for machine learning algorithm by separating the features and target, and perform cleaning of data, replced missing values by filling it with median as it is less destructive.
![code for data cleaning](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/1a4f6b1318fd7e320d8673a0cd35d2e4e16149df/images/day42%20californina%20data%20cleaning.png)
### Use of Simple Imputer
* The benefit of using SimplImputer is that it will store the median value of each feature: this will make it possible to impute missing values not only on the training set, but also on the validation set,the test set, and any new data fed to the model.
![photo of simple imputer use](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/1a4f6b1318fd7e320d8673a0cd35d2e4e16149df/images/day42%20california%20handling%20missing%20using%20Imputer.png)
### Handling of text and categorical data
* Text and categorical data can be handled by using ordinal encoder and One Hot encoding but incase of ordinal encoder it think data nearby data are more similar than far data which is not the case in Oceanproximity so we use onehot encoding.
![handling text and categorical data](https://github.com/Utshav-paudel/MachineLearning-DeepLearning/blob/1a4f6b1318fd7e320d8673a0cd35d2e4e16149df/images/day42%20handling%20text%20and%20categorical%20data.png)

* 📚Resources
[**Hands-On Machine Learning with Scikit-Learn and TensorFlow**](https://github.com/ageron/handson-ml3)
