**Project 3 Classification Using Neural Networks and Deep Learning**

Descriptions
In this project, a Convolutional Neural Network (CNN) is compiled of four layers and used to classify images of digit numbers.  

Contents  
1. "Project3ClassificationUsingCNN_XinYang.pdf" is the report.  
2. "main.py" is the python code for main function.  
3. "precode.py" and "mnist.py" are the python codes for obtaining and preparing image data from mnist database.
4. CNN_package is the folder including the python codes for layers and the neural network structure.  
4.1 "Convolution2D.py" is for convolution layer.  
4.2 "Maxpooling2D.py" is for pooling layer.  
4.3 "FullConnected.py" is for fully-connected neuron layer.  
4.4 "Flatten.py" is used to flatten data dimensions.  
4.5 "ReLu.py" is used as a activation function to convert the outputs.  
4.6 "Softmax.py" is used as a activation function to convert the outputs.  
4.7 "Net.py" defines the structure of CNN class.  

Instruction  
The main function accept two optional parameters - epoch (default=10), batch_size (default=100).  
The main.py, precode.py, mnist.py, CNN_package, and data folder need to be under the same directory.  
Below are four examples of commands. All give the same results, as epoch and batch_size are set as default values, which can be changed to customerize values.  
python main.py  
python main.py --epoch 10  
python main.py --batch_size 100  
python main.py --epoch 10 --batch_size 100
