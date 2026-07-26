# 🎭 CelebA Vanilla GAN

A PyTorch implementation of a **Vanilla Generative Adversarial Network (GAN)** trained on the **CelebA dataset** to generate synthetic human face images.

This project demonstrates the fundamentals of GANs by training a **Generator** and a **Discriminator** in an adversarial setting. The Generator learns to create realistic-looking face images, while the Discriminator learns to distinguish between real and generated images.

---

## 📸 Sample Output

> Generated face images after training.

<p align="center">
  <img src="results/Results of GAN.png" width="700">
</p>


---

## ✨ Features

- Vanilla GAN implementation using PyTorch
- Trained on the CelebA dataset
- Image preprocessing and normalization
- Generator and Discriminator built using Fully Connected Layers
- Binary Cross Entropy (BCE) Loss
- Adam Optimizer
- Image generation after each epoch

---

## 🧠 Model Architecture

### Generator
- Input: 100-dimensional Random Noise Vector
- Fully Connected Layers
- ReLU Activation
- Tanh Output

### Discriminator
- Input: 64 × 64 RGB Image
- Fully Connected Layers
- LeakyReLU Activation
- Sigmoid Output

---

## 📂 Dataset

**CelebFaces Attributes Dataset (CelebA)**

- **Images:** 202,599
- **Identities:** 10,177
- **Image Size:** 178 × 218 RGB

Dataset Link:

https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pillow

---

## 📁 Project Structure

```
celeba-vanilla-gan/
│
├── dataset/
├── results/
├── train.py
├── generator.py
├── discriminator.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/celeba-vanilla-gan.git

cd celeba-vanilla-gan

pip install -r requirements.txt
```

---

## ▶️ Training

Run

```bash
python train.py
```

---

## 📈 Loss Function

- Binary Cross Entropy Loss (BCELoss)

---

## 🎯 Future Improvements

- Deep Convolutional GAN (DCGAN)
- Wasserstein GAN (WGAN)
- Conditional GAN (CGAN)
- Higher Resolution Image Generation
- Better Training Stability

---

## 📚 Learning Outcomes

- Understanding GAN architecture
- Generator vs Discriminator
- Adversarial Training
- Binary Cross Entropy Loss
- Face Image Generation using GANs
- Working with Large Image Datasets

---

## ⭐ Acknowledgements

- CelebA Dataset by CUHK
- PyTorch
- Kaggle

---

## 👩‍💻 Author

**Vaishnavi Rathi**

If you found this project helpful, consider giving it a ⭐ on GitHub!
