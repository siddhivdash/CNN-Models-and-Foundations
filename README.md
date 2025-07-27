# CNN-Models-and-Foundations

A structured repository for learning, implementing, and showcasing classic and foundational Convolutional Neural Network (CNN) architectures. This repo demonstrates your journey from basic CNN concepts to advanced deep learning models using Jupyter Notebooks.

---

## Repository Structure

- **1-CNN-Foundation/**: Introductory materials and notebooks to help understand basic CNN building blocks and simple network implementations.
- **AlexNet/**: Implementation and experiments with the AlexNet architecture, a pioneering deep CNN for large-scale image recognition.
- **VGG/**: Notebooks related to VGG models, which further increased depth and regularized network design.
- **Inception.ipynb**: Notebook focused on the Inception (GoogLeNet) architecture, introducing novel multi-scale processing within CNNs.
- **Lenet.ipynb**: Classic LeNet implementation, one of the earliest CNNs designed for digit recognition.
- **ResNet50.ipynb**: Notebook on ResNet50, featuring residual connections to train much deeper networks.
- **jpg/**: Contains image assets or results for visualizations and demonstrations.
- **17flowers.tgz**: A compressed dataset (likely the Oxford 17 Category Flower Dataset) used to train and evaluate models throughout the repo.

---

## Learning Pathway

This repository is organized to guide learners through a progression:

1. **Foundational Concepts**: Start with `1-CNN-Foundation` to learn about convolution, pooling, activation functions, and the basic structure of CNNs. These notebooks break down each key building block with code and visualization.
2. **Classic Architectures**:
   - **LeNet**: Study the foundational digit recognition pipeline.
   - **AlexNet**: Examine how deeper architectures and ReLU activation accelerated CNN advancements.
   - **VGG**: Explore very deep networks and the idea of stacking small convolution filters.
   - **Inception**: Learn about multi-branch architectures that process information at varied scales simultaneously.
   - **ResNet50**: Understand how residual connections help train deep models, a core advancement in modern deep learning.
3. **Hands-on Practice**: Each notebook is runnable with minimal setup, featuring explanations, code, and results so that learners can experiment and build intuition.

---

## Getting Started

1. **Clone this repository**:
git clone https://github.com/siddhivdash/CNN-Models-and-Foundations.git
cd CNN-Models-and-Foundations


2. **Set up environment**:
- Install Python 3.x (Anaconda recommended).
- Install required packages (Jupyter, TensorFlow, Keras, NumPy, Matplotlib).
- If using datasets like `17flowers.tgz`, extract before training:
  ```
  tar -xvzf 17flowers.tgz
  ```

3. **Launch Jupyter Notebook**:
Open the relevant notebook to begin learning and experimenting.

---

## Folder Contents Overview

| Folder/File         | Description                                      |
|---------------------|--------------------------------------------------|
| 1-CNN-Foundation/   | Intro notebooks for basic CNN concepts           |
| AlexNet/            | AlexNet model code and experiments               |
| VGG/                | VGG architecture implementation                  |
| jpg/                | Image assets for demos/results                   |
| 17flowers.tgz       | Flower images dataset (extract before use)       |
| Inception.ipynb     | Inception architecture notebook                  |
| Lenet.ipynb         | Classic LeNet architecture notebook              |
| ResNet50.ipynb      | Modern deep ResNet50 implementation and insights |

---

## Why This Repo?

- **Educational Focus**: Step-by-step, readable Jupyter Notebooks aimed at clear understanding.
- **Model Variety**: Implementations of historic and modern CNNs expose you to a range of ideas, helping you compare architectures and their evolution.
- **Practical Skills**: Learn not just model architectures, but also data handling, training tips, and visualization of results.

---

## Contributing

Suggestions, error reports, and additional notebooks implementing new architectures or experiments are welcome. Please open issues or submit pull requests!


---

## Acknowledgments

Inspired by academic deep learning courses and major classic papers:
- LeNet (LeCun et al., 1998)
- AlexNet (Krizhevsky et al., 2012)
- VGGNet (Simonyan & Zisserman, 2015)
- GoogLeNet/Inception (Szegedy et al., 2015)
- ResNet (He et al., 2015)

Datasets and additional materials are credited as appropriate in each notebook.

---

*Happy learning and building with CNNs!*


