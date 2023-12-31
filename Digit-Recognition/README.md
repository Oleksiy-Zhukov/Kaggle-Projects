# Digit Recognition using Convolutional Neural Networks

In this project, we will be working on a digit recognition problem using the popular MNIST dataset. The MNIST dataset consists of a large number of images of handwritten digits ranging from 0 to 9. Our goal is to develop a machine learning model that can accurately classify these images and correctly identify the digit that is being represented.

## Getting Started

The project was implemented using Python, and the following Python libraries were used:

* [pandas](https://pandas.pydata.org/) - for data manipulation and analysis
* [numpy](https://numpy.org/) - for numerical computations and array operations
* [plotly](https://plotly.com/graphing-libraries/) - for data visualization
* [matplotlib](https://matplotlib.org/stable/index.html) - for data visualization
* [seaborn](https://seaborn.pydata.org/index.html) - for data visualization
* [keras](https://keras.io/) - for building and training deep learning models
* [scikit-learn](https://scikit-learn.org/stable/index.html) - for building and evaluating machine learning models
* [warnings](https://docs.python.org/3/library/warnings.html) - for handling warning messages generated by the models
* [kaleido](https://pypi.org/project/kaleido/) - for exporting static images of the visualizations

## Dataset

The dataset used for this project is the MNIST database of handwritten digits, which contains 60,000 training images and 10,000 testing images. Each image is a 28x28 grayscale image, representing a handwritten digit from 0 to 9.

## Architecture

The architecture of the model used in this project consists of 4 Convolutional layers with ReLU activation, followed by 2 fully connected (Dense) layers with ReLU activation, and an output layer with Softmax activation. BatchNormalization and Dropout techniques were also used to improve the performance and reduce overfitting.

## Training

The model was trained using the Adam optimizer and the Cross Entropy loss function. A learning rate annealer was also used to gradually reduce the learning rate during training. The training was performed on a GPU, which significantly reduced the training time.

## Results

The trained model achieved an accuracy of 99.52% on the testing set, which is a state-of-the-art performance on the MNIST dataset. 

## Contact

* My Kaggle profile: https://www.kaggle.com/zhukovoleksiy
* My GitHub profile: https://github.com/Oleksiy-Zhukov
* My LinkedIn profile: https://www.linkedin.com/in/oleksiizhukov/
