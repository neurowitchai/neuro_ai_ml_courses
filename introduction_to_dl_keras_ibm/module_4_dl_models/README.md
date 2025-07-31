# 📘 Module 4: Deep Learning Models

This module introduces high-level APIs in Keras to build deep learning models efficiently. It covers different model architectures, how to configure and compile them, and how to monitor performance with metrics. You’ll also learn about optimizers that drive the learning process.

---

## 📚 Topics Covered

- **Keras Functional and Sequential APIs**  
- **Model Compilation and Evaluation**  
- **Loss Functions**  
- **Optimizers**  
- **Metrics**  

---

## 📓 Notebooks

- `convolutional_nn.ipynb` – Walks through the backpropagation algorithm.
- `transformers_keras.ipynb` – Compares different activation functions and their effects.

---

## 🎯 Learning Objectives

By the end of this module, you should be able to:

- Build models using the Sequential and Functional APIs in Keras  
- Choose appropriate loss functions based on the task (e.g., classification vs regression)  
- Select and configure optimizers like SGD, Adam, RMSProp  
- Evaluate model performance with appropriate metrics  

---

## 🔗 Resources

- [Keras Models](https://keras.io/models/about-keras-models/#about-keras-models)  
- [Keras Loss Functions](https://keras.io/losses/)  
- [Keras Optimizers](https://keras.io/optimizers/)  
- [Keras Metrics](https://keras.io/metrics/)  

---

## Did you know?
* A neural network with one hidden layer is considered a shallow neural network.
* A network with many hidden layers and a large number of neurons in each layer is considered a deep neural network.
* Shallow neural networks only take vectors as input.
* Deep neural networks can take raw data, such as images and text, as input.
* The sudden boom in the deep learning field can be attributed to three main factors: advancements in the field, data availability, and greater computational power.
* Convolutional neural networks make the explicit assumption that the inputs are images.
* Convolutional neural networks are best for solving problems related to image recognition, object detection, and other computer vision applications.
* The input to a convolutional neural network is mostly an (n x m x 1) for grayscale images or an (n x m x 3) for colored images.
* In the convolutional layer, we define filters and compute the convolution between the defined filters and each of the three images.
* A convolutional layer also consists of ReLUs, which filter the output of the convolutional step, passing only positive values and turning any negative values to 0.
* The pooling layer is added to reduce the spatial dimensions of the data propagating through the network.
* The two types of pooling widely used in convolutional neural networks are max pooling and average pooling.
* In the fully connected layer, we flatten the output of the last convolutional layer and connect every node of the current layer with every other node of the next layer.
* Neural networks and deep learning models see data points as independent instances.
* Recurrent Neural Networks, or RNNs, don't just take new input but also take the output from the previous data point as input.
* RNNs are good at modeling patterns and sequences of data, such as texts, genomes, handwriting, and stock markets.
* A popular type of RNN is the long short-term memory model (LSTM).
* LSTMs are used for applications such as image generation, handwriting generation, automatic image captioning, and automatic video descriptions.
* Autoencoding is a data compression algorithm where the compression and decompression functions are learned automatically from data.
* Autoencoders are data-specific.
* Applications of autoencoders include data denoising and dimensionality reduction for data visualization.
* Autoencoding can take an image as an input, use an encoder to find the optimal compressed representation of the input image, and then use a decoder to restore the original image.
* A popular type of autoencoder is restricted Boltzmann machines.
* Applications of restricted Boltzmann machines include fixing imbalanced data sets, estimating missing data set values, and automatic feature extraction.