# PyTorch 基础学习项目总结

## 项目目标

本项目旨在通过多种实现方式，帮助初学者理解神经网络的基本原理及 PyTorch 框架的核心功能。内容涵盖了从最基础的 numpy 实现，到 PyTorch 的 tensor、autograd、nn.Module 等模块的逐步演进，帮助大家掌握深度学习建模的底层机制与高阶接口。

## 主要内容

### 1. 神经网络的多种实现方式

- **Numpy 实现**  
  通过 numpy 手动实现前向传播和反向传播，帮助理解神经网络的数学本质和梯度计算过程。

- **PyTorch Tensor 实现**  
  利用 PyTorch 的 tensor 运算，手动实现前向与反向传播，体验 GPU 加速和 tensor 操作的便捷性。

- **Autograd 自动求导**  
  使用 PyTorch 的 autograd 自动微分机制，简化反向传播过程，体会自动求导带来的便利。

- **自定义 Autograd Function**  
  通过自定义 ReLU 激活函数，深入理解 autograd 的底层机制和自定义反向传播的实现方法。

- **nn.Module 封装**  
  利用 PyTorch 的 nn.Module 和 nn.Sequential，快速搭建神经网络结构，体验模块化开发的优势。

- **自定义网络结构**  
  通过继承 nn.Module 自定义两层神经网络，掌握自定义模型的标准流程。

### 2. 代码结构

- `numpy_net.py`：Numpy 实现的神经网络
- `tensor_net.py`：PyTorch Tensor 实现
- `autograd_net.py`：PyTorch Autograd 实现
- `my_relu.py`：自定义 ReLU 激活函数
- `my_nn.py`：自定义 nn.Module 网络结构
- `nn_net.py`：标准 nn.Module 实现
- `TorchStudy.ipynb`：整合上述内容的 Jupyter Notebook，便于交互式学习和实验

### 3. 学习收获

- 理解神经网络的基本结构（输入层、隐藏层、输出层）
- 掌握前向传播与反向传播的原理
- 熟悉 PyTorch 的核心模块（tensor、autograd、nn）
- 学会自定义激活函数和网络结构
- 体会从底层到高阶 API 的开发流程
