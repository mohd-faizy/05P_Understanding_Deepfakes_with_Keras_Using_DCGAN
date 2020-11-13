# __Understanding-Deepfakes-with-Keras-Using-DCGAN__


<img src = 'https://zhangruochi.com/Understanding-Deepfakes-with-Keras/2020/07/30/DCGAN.png'>

## __Dataset__
__MNIST__(Modified National Institute of Standards and Technology database)

```python

# Downloding the dataset
(x_train, y_train), (x_test, y_test) = tfutils.datasets.mnist.load_data(one_hot=False)

# Loading the Subsets that belong to the class zero 
# So the x_train, x_test have the images of only '0'
x_train = tfutils.datasets.mnist.load_subset([0], x_train, y_train)
x_test = tfutils.datasets.mnist.load_subset([0], x_test, y_test)

# Creating the Combined set Using the NumPy Concatenate function
x = np.concatenate([x_train, x_test], axis=0)
```

## :heavy_check_mark: Objectives

:one: Implement a Deep Convolutional Generative Adversarial Network (DCGAN).
    
:two: Train a DCGAN to synthesize realistic looking images.

By the end of this course, you will understand how to implement DCGANs, and how to train them to generate realistic synthetic images.


## Task 1: Introduction

    - Introduction to the DCGANS

## Task 2: Importing and Plotting the Data

    - Importing the MNIST Dataset
    - Creating a subset of the dataset for just one class.
    - Visualizing the subset.

## Task 3: Discriminator

    - Basic understanding of how a GAN works.
    - Creating a Discriminator Network.
    - Creating an optimizer instance.

## Task 4: Generator

    - Creating a Generator Network.
    - Generating a new image from the untrained Generator model.

## Task 5: Generative Adversarial Network (GAN)

    - Connecting the Generator and Discriminator to create a Generative Adversarial Network (GAN)
    
 <img src='https://courses.csail.mit.edu/18.337/2017/projects/morales_manuel/img/dcgan.png'>

## Task 6: Training the GAN

    - Creating a training loop.
    - Creating a dynamic plot that displays generated images after each epoch.
    
 --- 

### Connect with me:


[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][StackExchange AI]

[twitter]: https://twitter.com/F4izy
[linkedin]: https://www.linkedin.com/in/faizy-mohd-836573122/
[StackExchange AI]: https://ai.stackexchange.com/users/36737/cypher


---


![Faizy's github stats](https://github-readme-stats.vercel.app/api?username=mohd-faizy&show_icons=true)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mohd-faizy&layout=compact)](https://github.com/mohd-faizy/github-readme-stats)

