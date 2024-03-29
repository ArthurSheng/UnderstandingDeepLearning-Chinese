# UnderstandingDeepLearning-Chinese

# 关于这本书
关于这本最新的深度学习手册，作者 Simon J.D. Prince 这样介绍它：
> 正如书名所示，它不是最实用的书（没有代码），也不是最理论的书（没有证明）。本书的目标是让读者以最简单的方式理解支撑现代深度学习技术的核心思想。 读完本书后，读者将能够把深度学习应用于没有现成方法的新情况。

● 英文原版：[《Understanding Deep Learning》](https://udlbook.github.io/udlbook/)

![](https://oss-ata.alibaba.com/article/2023/12/960ca4fa-cd2d-487b-996b-36005ed980a1.png)
----
----
# 目录

* **前言** - Preface
* **致谢** - Acknowledgements

----

* 1 **引言** - Introduction
  * 1.1 监督学习 - Supervised learning
  * 1.2 无监督学习 - Unsupervised learning
  * 1.3 强化学习 - Reinforcement learning
  * 1.4 伦理 - Ethics
  * 1.5 本书结构 - Structure of book
  * 1.6 其他书籍 - Other books
  * 1.7 阅读本书的方法 - How to read this book

----

* 2 **监督学习** - Supervised learning
  * 2.1 监督学习概述 - Supervised learning overview
  * 2.2 线性回归示例 - Linear regression examplew
  * 2.3 总结 - Summary

----

* 3 **浅层神经网络** - Shallow neural networks
  * 3.1 神经网络示例 - Neural network example
  * 3.2 通用逼近定理 - Universal approximation theorem
  * 3.3 多变量输入和输出 - Multivariate inputs and outputs
  * 3.4 浅层神经网络：一般情况 - Shallow neural networks: general case
  * 3.5 术语 - Terminology
  * 3.6 总结 - Summary

----

* 4 **深度神经网络** - Deep neural networks
  * 4.1 组合神经网络 - Composing neural networks
  * 4.2 从组合网络到深度网络 - From composing networks to deep networks
  * 4.3 深度神经网络 - Deep neural networks
  * 4.4 矩阵表示 - Matrix notation
  * 4.5 浅层 vs. 深度神经网络 - Shallow vs. deep neural networks
  * 4.6 总结 - Summary

----

* 5 **损失函数** - Loss functions
  * 5.1 最大似然 - Maximum likelihood
  * 5.2 构建损失函数的方法 - Recipe for constructing loss functions
  * 5.3 示例1：单变量回归 - Example 1: univariate regression
  * 5.4 示例2：二分类 - Example 2: binary classification
  * 5.5 示例3：多类分类 - Example 3: multiclass classification
  * 5.6 多输出 - Multiple outputs
  * 5.7 交叉熵损失 - Cross-entropy loss
  * 5.8 总结 - Summary

----

* 6 **模型拟合** - Fitting models
  * 6.1 梯度下降 - Gradient descent
  * 6.2 随机梯度下降 - Stochastic gradient descent
  * 6.3 动量 - Momentum
  * 6.4 Adam
  * 6.5 训练算法的超参数 - Training algorithm hyperparameters
  * 6.6 总结 - Summary

----

* 7 **梯度和初始化** - Gradients and initialization
  * 7.1 问题定义 - Problem definitions
  * 7.2 计算导数 - Computing derivatives
  * 7.3 玩具示例 - Toy example
  * 7.4 反向传播算法 - Backpropagation algorithm
  * 7.5 参数初始化 - Parameter initialization
  * 7.6 示例训练代码 - Example training code
  * 7.7 总结 - Summary

----

* 8 **性能评估** - Measuring performance
  * 8.1 训练一个简单模型 - Training a simple model
  * 8.2 错误的来源 - Sources of error
  * 8.3 减少错误 - Reducing error
  * 8.4 双下降 - Double descent
  * 8.5 选择超参数 - Choosing hyperparameters
  * 8.6 总结 - Summary

----

* 9 **正则化** - Regularization
  * 9.1 显式正则化 - Explicit regularization
  * 9.2 隐式正则化 - Implicit regularization
  * 9.3 提高性能的启发式方法 - Heuristics to improve performance
  * 9.4 总结 - Summary

----

* 10 **卷积网络** - Convolutional networks
  * 10.1 不变性和等变性 - Invariance and equivariance
  * 10.2 一维输入的卷积网络 - Convolutional networks for 1D inputs
  * 10.3 二维输入的卷积网络 - Convolutional networks for 2D inputs
  * 10.4 降采样和上采样 - Downsampling and upsampling
  * 10.5 应用 - Applications
  * 10.6 总结 - Summary

----

* 11 **残差网络** - Residual networks
  * 11.1 顺序处理 - Sequential processing
  * 11.2 残差连接和残差块 - Residual connections and residual blocks
  * 11.3 残差网络中的梯度爆炸 - Exploding gradients in residual networks
  * 11.4 批归一化 - Batch normalization
  * 11.5 常见的残差网络结构 - Common residual architectures
  * 11.6 为什么带有残差连接的网络表现出色？ - Why do nets with residual connections perform so well?
  * 11.7 总结 - Summary

----

* 12 **Transformer** - Transformers
  * 12.1 处理文本数据 - Processing text data
  * 12.2 点积自注意力 - Dot-product self-attention
  * 12.3 点积自注意力的扩展 - Extensions to dot-product self-attention
  * 12.4 Transformer
  * 12.5 用于自然语言处理的Transformer - Transformers for natural language processing
  * 12.6 编码器模型示例：BERT - Encoder model example: BERT
  * 12.7 解码器模型示例：GPT3 - Decoder model example: GPT3
  * 12.8 编码器-解码器模型示例：机器翻译 - Encoder-decoder model example: machine translation
  * 12.9 长序列的Transformer - Transformers for long sequences
  * 12.10 图像的Transformer - Transformers for images
  * 12.11 总结 - Summary

----

* 13 **图神经网络** - Graph neural networks
  * 13.1 图是什么？ - What is a graph?
  * 13.2 图表示 - Graph representation
  * 13.3 图神经网络、任务和损失函数 - Graph neural networks, tasks, and loss functions
  * 13.4 图卷积网络 - Graph convolutional networks
  * 13.5 示例：图分类 - Example: graph classification
  * 13.6 归纳 vs. 传导模型 - Inductive vs. transductive models
  * 13.7 示例：节点分类 - Example: node classification
  * 13.8 图卷积网络的层 - Layers for graph convolutional networks
  * 13.9 边图 - Edge graphs
  * 13.10 总结 - Summary

----

* 14 **无监督学习** - Unsupervised learning
  * 14.1 无监督学习模型的分类 - Taxonomy of unsupervised learning models
  * 14.2 什么是好的生成模型？ - What makes a good generative model?
  * 14.3 量化性能 - Quantifying performance
  * 14.4 总结 - Summary

----

* 15 **生成对抗网络** - Generative Adversarial Networks
  * 15.1 辨别作为信号 - Discrimination as a signal
  * 15.2 提高稳定性 - Improving stability
  * 15.3 渐进增长、小批量辨别和截断 - Progressive growing, minibatch discrimination, and truncation
  * 15.4 条件生成 - Conditional generation
  * 15.5 图像转换 - Image translation
  * 15.6 StyleGAN
  * 15.7 总结 - Summary

----

* 16 **归一化流** - Normalizing flows
  * 16.1 一维示例 - 1D example
  * 16.2 一般情况 - General case
  * 16.3 可逆网络层 - Invertible network layers
  * 16.4 多尺度流 - Multi-scale flows
  * 16.5 应用 - Applications
  * 16.6 总结 - Summary

----

* 17 **变分自编码器** - Variational autoencoders
  * 17.1 潜变量模型 - Latent variable models
  * 17.2 非线性潜变量模型 - Nonlinear latent variable model
  * 17.3 训练 - Training
  * 17.4 ELBO性质 - ELBO properties
  * 17.5 变分近似 - Variational approximation
  * 17.6 变分自编码器 - Variational autoencoder
  * 17.7 重参数化技巧 - The reparameterization trick
  * 17.8 应用 - Applications
  * 17.9 总结 - Summary

----

* 18 **扩散模型** - Diffusion models
  * 18.1 概述 - Overview
  * 18.2 编码器（正向过程） - Encoder (forward process)
  * 18.3 解码器模型（反向过程） - Decoder model (reverse process)
  * 18.4 训练 - Training
  * 18.5 损失函数的重参数化 - Reparameterization of loss function
  * 18.6 实现 - Implementation
  * 18.7 总结 - Summary

----

* 19 **强化学习** - Reinforcement learning
  * 19.1 马尔可夫决策过程、回报和策略 - Markov decision processes, returns, and policies
  * 19.2 期望回报 - Expected return
  * 19.3 表格型强化学习 - Tabular reinforcement learning
  * 19.4 拟合Q学习 - Fitted Q-learning
  * 19.5 策略梯度方法 - Policy gradient methods
  * 19.6 演员-评论家方法 - Actor-critic methods
  * 19.7 离线强化学习 - Offline reinforcement learning
  * 19.8 总结 - Summary

----

* 20 **为什么深度学习有效？** - Why does deep learning work?
  * 20.1 反对深度学习的观点 - The case against deep learning
  * 20.2 影响拟合性能的因素 - Factors that influence fitting performance
  * 20.3 损失函数的特性 - Properties of loss functions
  * 20.4 决定泛化的因素 - Factors that determine generalization
  * 20.5 我们是否需要这么多参数？ - Do we need so many parameters?
  * 20.6 网络是否必须深层？ - Do networks have to be deep?
  * 20.7 总结 - Summary

----

* 21 **深度学习与伦理** - Deep learning and ethics
  * 21.1 价值对齐 - Value alignment
  * 21.2 有意的滥用 - Intentional misuse
  * 21.3 其他社会、伦理和专业问题 - Other social, ethical, and professional issues
  * 21.4 案例研究 - Case study
  * 21.5 科学的无价值理想 - The value-free ideal of science
  * 21.6 负责任的AI研究作为集体行动问题 - Responsible AI research as a collective action problem
  * 21.7 前进的方式 - Ways forward
  * 21.8 总结 - Summary

----

* **附录A** - 符号说明 - A Notation
* **附录B** - 数学 - B Mathematics
  * B.1 函数 - Functions
  * B.2 二项式系数 - Binomial coefficients
  * B.3 向量、矩阵和张量 - Vector, matrices, and tensors
  * B.4 特殊类型的矩阵 - Special types of matrix
  * B.5 矩阵微积分 - Matrix calculus
* **附录C** - 概率 - C Probability
  * C.1 随机变量和概率分布 - Random variables and probability distributions
  * C.2 期望 - Expectation
  * C.3 正态概率分布 - Normal probability distribution
  * C.4 抽样 - Sampling
  * C.5 概率分布之间的距离 - Distances between probability distributions
* **参考文献** - Bibliography
* **索引** - Index
