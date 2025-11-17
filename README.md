# Advanced MNIST Classification: MobileNetV3-Large

An implementation of the **MobileNetV3-Large** architecture for the classic MNIST handwritten digit classification task.



---

## Overview

This project serves as an experiment in applying modern, high-efficiency architectures to foundational datasets. Instead of a simple ANN or CNN, this notebook implements the MobileNetV3-Large model (pre-trained on ImageNet) and fine-tunes it for the MNIST dataset.

The goal is to demonstrate proficiency in:
* **Transfer Learning:** Adapting a complex, pre-trained model.
* **Modern Architectures:** Implementing and utilizing SOTA (State-of-the-Art) models like MobileNetV3.
* **Data Adaptation:** Handling the specific input requirements of MobileNetV3 (e.g., 3-channel input) for a 1-channel dataset (MNIST).

---

## Tech Stack

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)

---

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mahdifelfeli/Advanced-MNIST-MobileNetV3.git](https://github.com/mahdifelfeli/Advanced-MNIST-MobileNetV3.git)
    cd Advanced-MNIST-MobileNetV3
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Notebook:**
    * Open and run the `mnist_mobilenetv3large.ipynb` notebook using Jupyter.
    ```bash
    jupyter notebook
    ```
