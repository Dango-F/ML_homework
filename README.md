# KAN 网络复现项目

本项目旨在复现论文 "KAN: Kolmogorov–Arnold Networks" 中提出的神经网络模型，并将其应用于手写数字识别任务。以下是该项目的详细说明。

## 项目成员

- FYL
- MYT
- HY
- WYN

## 项目背景

KAN 网络是一种基于 Kolmogorov-Arnold 表示定理的创新型网络。本项目将尝试复现论文中描述的 KAN 模型，并将其应用于 MNIST 手写数字数据集上进行测试和其他方面的应用(详见 KAN_Model.ipynb)。

## 项目内容

- `ML_homework_KAN的复现`目录：包含 KAN 网络的源代码，以及若干改进代码
- `README.md`：本文件，用于提供项目概述和说明

## 复现步骤

1. 下载代码和论文：

   - KAN 源码：[https://github.com/KindXiaoming/pykan](https://github.com/KindXiaoming/pykan)
   - KAN 论文：[https://arxiv.org/abs/2404.19756](https://arxiv.org/abs/2404.19756)

2. 设置环境：

   - 确保已安装 Python 和 PyTorch 深度学习框架
   - Requirements：
     ·python==3.9.7 /及以上
     ·matplotlib==3.6.2
     ·numpy==1.24.4
     ·scikit_learn==1.1.3
     ·setuptools==65.5.0
     ·sympy==1.11.1
     ·torch==2.2.2
     ·tqdm==4.66.2

3. 数据准备：

   - 下载并准备 MNIST 手写数字数据集

4. 模型复现：

   - 使用 KAN 源码中提供的模型代码，按照论文中的描述实现 KAN 网络模型

5. 训练与测试：

   - 对复现的 KAN 模型进行训练，并在 MNIST 数据集上进行测试，评估模型性能

6. 改进尝试：
   - 尝试改进 KAN 模型，如调整网络结构、超参数调优等，以提高模型性能

## 项目结论

通过本项目，我们期望能够深入理解 KAN 网络模型的原理和设计，并通过实际复现和应用加深对其性能表现的认识。同时，我们也将尝试对模型进行改进，为后续研究提供更多的思路和实践经验。祝愿 KAN 网络继续发展下去。

---

以上是我们对 KAN 网络复现项目的详细说明。如有任何疑问或建议，请随时联系我们1847539781@qq.com.
