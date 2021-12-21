# Human_emotion_recognition
## About

Humans express their emotions on regular basis. Each second of their life is a 
reaction towards something. Different situation calls for the different emotion. As 
holidays are close enough, people feel happiness, if something doesn’t go according 
to their plan, they feel sad or angry, and for the normal routine days, they are neutral, 
or disgusted, or afraid of something. That means us humans, conveys everything 
with our emotions. For example, a person is standing on a bridge, might show 
complex emotions such as fear, sadness, anger, disgust and so much more and detect 
of such emotions is necessary sometime in the real-life situations. This model 
demonstrates the learning capability of the Convolution Neural Network (CNN) with 
the goal of image classification for the Human Emotion. There are 7 classes of 
emotions and a network is created to understand such complex human emotion from 
the collected image dataset. Here, various images are present with the goal that a 
neural network can train them and identify the emotion the image is exhibiting.

## Requirement

It is advisable if you upgrade your pip version because some modules might require the latest version of pip. To upgrade your pip, run the following command in your command prompt.

```
 > pip install --upgrade pip
```

Here is the main pre-requisite modules required to run the ConvNet projects.

```
 > pip install tensorflow
 > pip install keras
 > pip install matplotlib
 > pip install numpy
 > pip install tk
```

**Note:** All of these modules might not be required to run each project. Each project requires different modules, and you may head on to the specific project in order to know more about it.
All available files are the .ipynb files. If required, one can open them with Google Colab or Jupyter notebook.

## Projects

Here are some ConvNet sample projects:

### Recognition

This Image Recognition/Classification Software is built using the **CIFAR-10 Dataset** (Canadian Institute for Advanced Research, 10 Classes). The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. <br>

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.<br>

You may head on to <a href = 'https://github.com/YashvardhanG/CNN/tree/main/Image%20Recognition%20Software'>Image Recognition</a> to explore and know more about the project.

**Note:** The dataset is downloaded as soon as you open the main code, but you may also download the CIFAR-10 Dataset Externally. To download the CIFAR-10 Dataset, head on to <a href = 'https://www.cs.toronto.edu/~kriz/cifar.html'>CIFAR-10</a> website.
<br><br>

## Working

You may explore the working of a Convolutional Neural Network <a href = 'https://towardsdatascience.com/convolutional-neural-network-17fb77e76c05#:~:text=Fully%20Connected%20Layer%20is%20simply,into%20the%20fully%20connected%20layer.'>Here</a>.
<br><br>
The working of all the projects can broadly be categorised into two steps:
<ol>
  <li><b>Training:</b><br>This is the initialising step, or can be considered as the pre-processing step of a ConvNet. This indeed is the most important steop because this is where the CNN actually learns and understands the purpose of the user-application, and compiles a data model which can be integrated in a main driver code/application. This is the primary step where data is sorted, analysed, processed and arranged. </li><br>
  <li><b>Testing:</b><br>This is the secondary step of a CNN which includes the usage of the created data model in the previous step. In this step, you will create the driver code/application which will provide a user interface to interact with the dataset in order to carry out a specific operation, for which the application is designed for. This in summary, is the 'fancy' of a CNN.</li><br>
</ol>

To know more about the working of different projects, go ahead and explore all the <a href="#projects">Projects</a>.
<br>
**Note:** Each CNN is different, and you may or may not put both of these steps in the same code.
<br><br>

## License

Distributed under the GNU License. See <a href = "https://github.com/MahekPavthawala/human_emotion_recognition/blob/main/LICENSE"> LICENSE </a> for more information.
