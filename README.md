# Deep Convolutional GAN (DCGAN) on MNIST

This repository contains the code for a Deep Convolutional GAN (DCGAN) implemented in PyTorch. The model is trained on the MNIST dataset to generate novel images of handwritten digits.



## Project Context

This project is the assignment for **Week 2** of the **"Build Basic Generative Adversarial Networks (GANs)"** course, part of the [DeepLearning.AI GANs Specialization on Coursera](https://www.coursera.org/specializations/generative-adversarial-networks-gans).

The core logic is contained in the `C1_W2_.ipynb` notebook. It follows the architecture described in the original DCGAN paper, "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks."

## Key Concepts & Technologies

* **Model:** Deep Convolutional GAN (DCGAN)
* **Framework:** PyTorch
* **Dataset:** MNIST
* **Key Layers:** `ConvTranspose2d` (for upsampling in the Generator), `Conv2d` (in the Discriminator), `BatchNorm2d`, `ReLU` & `LeakyReLU` activations.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Joseph1997-eng/Deep-Convolution-GAN-DCGAN-.git]([https://github.com/YourUsername/YourRepoName.git](https://github.com/Joseph1997-eng/Deep-Convolution-GAN-DCGAN-.git))
    cd YourRepoName
    ```

2.  **Install dependencies:**
    (It's recommended to use a virtual environment)
    ```bash
    pip install torch torchvision matplotlib jupyter
    ```

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

4.  Open the `C1_W2_.ipynb` file and run the cells.

## (Optional) Example Results

