# 🧠 Fashion MNIST Classification using PyTorch

This project demonstrates how to build and train a Convolutional Neural Network (CNN) using **PyTorch** on the **Fashion MNIST** dataset.

---

---

## 🗂️ Dataset

We use the **Fashion MNIST** dataset, which is a drop-in replacement for the original MNIST. It includes 70,000 grayscale images of 10 fashion categories:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

---

## 🧰 Libraries Used

- `torch`
- `torchvision`
- `matplotlib`
- `numpy`

---

## 🧪 Model Architecture

#kernel, filters, stride, padding
- architecture_config = [(3,16,1,1),
     "M",
    (3,32,1,1),
    (3,64,1,1),
    "M"
    ]
- Flatten layer
- Fully connected layers
- Dropout for regularization
- `MeanSqaredError` and `Adam` optimizer

---

 Training Performance

    Training Accuracy: ~99%

    Test Accuracy: ~93.25%

## 🚀 How to Run

### 📌 In Google Colab:
1. Upload the notebook `pytorch_fashion_mnist.ipynb`
2. Run each cell sequentially

### 🖥️ On Local System:
```bash
git clone https://github.com/Arunesh2805/Image_processing_projects.git
cd Image_processing_projects
jupyter notebook pytorch_fashion_mnist.ipynb



##Author

Arunesh Gadia
