# 🧠 Capsule Network for MNIST Classification

A Python implementation of a **Capsule Network (CapsNet)** designed to classify handwritten digits from the **MNIST dataset**. Unlike traditional CNNs, Capsule Networks preserve hierarchical spatial relationships and achieve better generalization with fewer parameters.

![MNIST sample](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

---

## 🔍 What is a Capsule Network?

Capsule Networks, introduced by **Geoffrey Hinton** in 2017, aim to address shortcomings in CNNs such as:
- **Loss of spatial hierarchies** (e.g., part-to-whole relationships)
- **Sensitivity to viewpoint and rotation**

CapsNets use **capsules** (groups of neurons) and a dynamic routing algorithm instead of max pooling to better preserve spatial relationships.

---

## 📦 Features

- ✅ Implemented using **PyTorch**
- ✅ Trained on **MNIST dataset**
- ✅ Replaces max-pooling with **dynamic routing**
- ✅ Visualizes **reconstructions** and **latent capsules**
- ✅ Modular and easy to extend to other datasets

---

## 🛠️ Setup & Installation

### 🔗 Clone the repository

```bash
git clone https://github.com/AnujS394/-Capsule-Network-for-MNIST.git
cd -Capsule-Network-for-MNIST
