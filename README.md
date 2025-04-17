# 📚 Pytorch Lessons

This repository contains notebooks implementing machine learning models using PyTorch, based on lessons from the [YouTube tutorial](https://www.youtube.com/watch?v=GIsg-ZUy0MY).

---

## 🧑‍💻 Notebooks Included

- `1-pytorch-tensor-basics.ipynb` - Basics of PyTorch tensors and tensor operations.
- `2-linear-regression-using-gradient-descent.ipynb` - Implementing linear regression using gradient descent.
- `3-logistic-regression.ipynb` - Implementing logistic regression using PyTorch.
- `4-image-classification-on-MNIST-using-logistic-regression.ipynb` - Image classification on the MNIST dataset using logistic regression.
- `5-image-classification-on-MNIST-using-feedforward-nn-gpu.ipynb` - Image classification on MNIST using a feedforward neural network on a GPU.
- `6-image-classification-on-CIFAR10-using-cnn-GPU.ipynb` - Image classification on CIFAR-10 using a Convolutional Neural Network (CNN) with GPU support.



## 💡 Requirements

To run the notebooks, you'll need:

- Python 3.x
- PyTorch (install with `pip install torch`)
- Other dependencies can be installed with:

    ```bash
    pip install -r requirements.txt
    ```


```

│   .gitattributes
│   1-pytorch-tensor-basics.ipynb
│   2-linear-regression-using-gradient-descent.ipynb
│   3-logistic-regression.ipynb
│   4-image-classification-on-MNIST-using-logistic-regression.ipynb
│   5-image-classification-on-MNIST-using-feedforward-nn-gpu.ipynb
│   6-image-classification-on-CIFAR10-using-cnn-GPU.ipynb
│   README.md
│
├── data
│   └───MNIST
│       ├───processed
│       │       test.pt
│       │       training.pt
│       │
│       └───raw
│               t10k-images-idx3-ubyte
│               t10k-images-idx3-ubyte.gz
│               t10k-labels-idx1-ubyte
│               t10k-labels-idx1-ubyte.gz
│               train-images-idx3-ubyte
│               train-images-idx3-ubyte.gz
│               train-labels-idx1-ubyte
│               train-labels-idx1-ubyte.gz
│
└──saved_models
        cifar10-cnn.pth

```

## 📺 Video Link

The content in this repository is based on the tutorial available on YouTube: [PyTorch Deep Learning Tutorials](https://www.youtube.com/watch?v=GIsg-ZUy0MY).



## 📬 Contact

Feel free to [open an issue](https://github.com/AnirbanMukherjeeXD/pytorch-lessons/issues) for any questions or feedback, or reach out via [my GitHub profile](https://github.com/AnirbanMukherjeeXD).
