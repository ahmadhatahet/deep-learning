# Deep Learning
Utilizing PyTorch to build custom and fine-tune pre-trained models for various tasks.

_!Note: GitHub has an issue openeing jupyter notebooks._<br>
_To view the notebooks replace github with nbsanity._<br>
_The URL underneath are using nbsanity by default_<br>

### **1. [Classification | Convolution Network:](https://nbsanity.com/ahmadhatahet/deep-learning/blob/master/cnn-model-cifar10.ipynb)**
Train custom convolution network model to classify Cifar-10 image dataset.<br />
The model achieved  ~91% accuracy and ~0.22% loss.


### **2. [Fine-Tuning | DensNet:](https://nbsanity.com/ahmadhatahet/deep-learning/blob/master/transfer-learning-cifar10.ipynb)**
Utilizing the pre-trained weights for a [DensNet](https://arxiv.org/abs/1608.06993) model, and train it for a couple of epochs to adapt for classifying cifar-10 image dataset.

<img src="https://github.com/ahmadhatahet/deep-learning/blob/master/imgs/densenet.png"
width=500>

### **3. [VAE | Variational Autoencoder:](https://nbsanity.com/ahmadhatahet/deep-learning/blob/master/variational-autoencoders-fashionmnist.ipynb)**
Apply [variational autoencoder](https://arxiv.org/abs/1906.02691) to construct FachionMNIST images
using only 2 latent dimension space.

<img src="https://github.com/ahmadhatahet/deep-learning/blob/master/imgs/vae.png"
width=500>

### **4. [Exploring | Learning Rate Schedulers:](https://nbsanity.com/ahmadhatahet/deep-learning/blob/master/learning-schedulers.ipynb)**
Plot the behavior of different known learning rate schedulers to use in training models.