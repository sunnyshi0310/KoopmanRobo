# KoopmanRobo

This repository provides an **end-to-end tutorial** for understanding and applying **Koopman operator theory in robotics**.  
It accompanies the upcoming survey paper:

> **Lu Shi**, Masih Haseli, Giorgos Mamakoukas, Daniel Bruder, Ian Abraham, Todd D. Murphey, Jorge Cortes, and Konstantinos Karydis,  
> *"Koopman Operators in Robot Learning"*, In Process.

---

## 🧠 Overview

This tutorial is designed for both **beginners** and **researchers** interested in applying Koopman operator theory to robotic systems.  
It walks you through the **entire pipeline** — from raw data collection to Koopman-based model estimation, controller design, and practical implementation.

All the main steps are demonstrated in **[`demo.ipynb`](demo.ipynb)**, which you can run directly to reproduce the results.  
The notebook provides detailed comments, visualizations, and practical notes to help you understand not only *how* but also *why* each step works.

---

## 🧩 What You’ll Learn

In the tutorial, you will:
- Collect and preprocess robot motion data  
- Estimate a Koopman operator model purely from data  
- Design a **Koopman-based Model Predictive Controller (MPC)** for a differential drive robot  
- Visualize and evaluate the performance of the learned controller  
- Understand how changing the **lifting function dictionary**, **MPC parameters**, or **training data** affects performance  

The implementation emphasizes clarity and educational value — the code is intentionally simple and not optimized for performance.  
We encourage readers to extend and experiment further.

---
## 🚀 Getting Started

The tutorial notebook **[`demo.ipynb`](demo.ipynb)** is fully self-contained and can be run directly on **[Google Colab](https://colab.research.google.com/)** without any additional setup.  
We recommend starting there to quickly reproduce all results and visualizations.

If you prefer to run the code in your **local environment**, please ensure the following dependencies are installed.  
The versions listed below are the ones we have tested and verified to work properly, but other compatible versions should also function as long as the interfaces remain consistent.

```bash
numpy==1.26
matplotlib==3.9.2
cvxpy==1.6.4
scipy==1.12
```

---
## 🔍 Recommended Further Reading & Tools

If you want to explore more advanced or large-scale Koopman learning frameworks, we highly recommend the following resources:

1. [**PyKoopman**](https://github.com/dynamicslab/pykoopman):  
   Compare the effects of different dictionary selections and Koopman estimation methods.  

2. [**Koopman Learning and Control**](https://github.com/udaylunawat/koopman_learning_and_control):  
   Examples of Koopman-based controllers across various robotic systems.  

3. [**Active Learning Koopman**](https://github.com/xxxx/active-learning-koopman):  
   Extensions of Koopman learning with active data collection strategies.

---

## 🧾 Citation

If you find this repository helpful, please cite our [survey paper](https://arxiv.org/pdf/2408.04200) once published.


