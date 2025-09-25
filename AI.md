以下是调整格式后的技术栈内容，并梳理了各个技术的作用和重要性：

# EPI 人工智能技术栈

## 一、人工智能数据基础
### （一）高等数学
- 高等数学是理解人工智能中许多核心概念的基础，如梯度下降算法中的导数、偏导数，以及神经网络中的微积分等。它帮助我们理解模型的优化过程和数据的变化规律。
- 是构建和优化机器学习模型的基石，对于深入理解算法原理至关重要。
- **推荐资源**：
  - [《高等数学》同济版 2024 年更新 | 宋浩老师](https://www.bilibili.com/video/BV1Eb411u7Fw/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)
  - [2025 深度学习】不愧是 3Blue1Brown 大神！把机器学习、神经网络、CNN、Transformer、反向传播、梯度下降、贝叶斯等核心知识点一口气全讲透](https://www.bilibili.com/video/BV1idpkzsEwZ/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)（重点）

### （二）线性代数（非常重要）
- 线性代数在人工智能中用于处理数据的向量化表示，如矩阵运算、特征值分解等。它帮助我们高效地处理大规模数据，优化算法性能，并且是深度学习中神经网络结构的基础。
- 是人工智能技术的核心数学工具之一，几乎所有的人工智能算法都依赖于线性代数的运算。
- **推荐资源**：
  - [《线性代数》教学视频 2.0 版（增加了同济版）【宋浩老师】](https://www.bilibili.com/video/BV1h7pteyEww/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)
  - [UP 主汉语配音 - 线性代数的本质合集 - 转载于 3Blue1Brown 官方双语](https://www.bilibili.com/video/BV1ib411t7YR/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （三）统计学基础
- 统计学帮助我们理解和分析数据的分布、相关性、假设检验等。在人工智能中，用于数据预处理、特征选择、模型评估等环节，确保数据的质量和模型的可靠性。
- 是数据分析和机器学习的基础，帮助我们从数据中提取有价值的信息。
- **推荐资源**：
  - [《概率论与数理统计》教学视频 2.0 版本【宋浩老师】](https://www.bilibili.com/video/BV1JXppejE8q/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

## 二、人工智能编程基础
### （一）C 语言
- C 语言是一种底层编程语言，帮助我们理解计算机的内存管理、指针等概念。虽然在人工智能中直接使用较少，但其对底层逻辑的理解有助于优化算法性能。
- 为学习其他高级编程语言打下基础，理解计算机底层原理。
- **推荐资源**：
  - [浙江大学翁恺教你 C 语言程序设计！C 语言基础入门！](https://www.bilibili.com/video/BV1dr4y1n7vA/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （二）Python
- Python 是人工智能领域最常用的语言之一，具有丰富的库和框架支持。它用于数据处理、模型构建、算法实现等各个环节，简单易学且功能强大。
- 是人工智能开发的主要工具，几乎所有的人工智能项目都依赖于 Python。
- **推荐资源**：
  - [黑马程序员 python 教程，8 天 python 从入门到精通，学 python 看这套就够了](https://www.bilibili.com/video/BV1qW4y1a7fU/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （三）数据结构和算法
- 数据结构和算法是编程的核心，帮助我们高效地存储和处理数据。在人工智能中，用于优化模型的计算效率、设计高效的算法流程等。
- 是编程能力的基础，对于解决复杂问题和优化性能至关重要。
- **推荐资源**：
  - [黑马程序员 2020 最新数据结构与算法教程（求职面试必备）【源码 + 笔记】](https://www.bilibili.com/video/BV1Cz411B7qd/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)
- **刷题进阶**：力扣 hot100
  - [刷完力扣热题 100 基本就业不用愁了](https://leetcode.cn/problem-list/2cktkvj/)

## 三、数据分析
- 数据分析是人工智能的前置步骤，帮助我们理解数据的特征、分布和关系。通过数据分析，可以进行数据清洗、特征工程等，为模型训练提供高质量的数据。
- 是人工智能项目的基础，直接影响模型的性能和效果。
- **推荐资源**：
  - [孙兴华中文讲 Python 数据分析三部曲入门篇 Numpy 教程 Pandas 教程 Matplotlib 教程](https://www.bilibili.com/video/BV1ji4y157uB/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

## 四、人工智能理论
### （一）深度学习
- 深度学习是人工智能的核心技术之一，通过构建多层神经网络，能够自动学习数据的特征表示，用于图像识别、自然语言处理等任务。
- 是现代人工智能技术的核心驱动力，广泛应用于各种复杂的任务中。
- **推荐资源**：
  - [（超爽中英!）2024 公认最好的【吴恩达深度学习】教程！附课件代码 Professionalization of Deep Learning](https://www.bilibili.com/video/BV11H4y1F7uH/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)（深度学习理论）
  - [2025 最新已完结！李沐【动手学深度学习 V2】PyTorch 版（171 集全）人工智能丨机器学习丨AI丨神经网络](https://www.bilibili.com/video/BV1f54ZzGEMC/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)（深度学习 + pytorch）

### （二）PyTorch 框架
- PyTorch 是一个流行的深度学习框架，提供了灵活的张量操作和自动微分功能，方便构建和训练复杂的神经网络。
- 是深度学习开发中常用的工具之一，具有强大的社区支持和丰富的功能。
- **推荐资源**：
  - [PyTorch 深度学习快速入门教程（绝对通俗易懂！）【小土堆】](https://www.bilibili.com/video/BV1hE411t7RN/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （三）传统机器学习
- 传统机器学习算法（如线性回归、决策树、支持向量机等）是人工智能的基础，适用于一些简单的任务和数据结构，为深度学习的发展奠定了基础。
- 是人工智能技术的基础，帮助我们理解模型的基本原理和应用场景。
- **推荐资源**：
  - [【官方中英】2025 年公认最好的【吴恩达机器学习课程】附课件、代码及实战项目！！！--人工智能/机器学习/深度学习](https://www.bilibili.com/video/BV1owrpYKEtP/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （四）强化学习（可选）
- 强化学习是一种通过与环境交互来学习最优策略的方法，适用于需要动态决策的任务，如机器人控制、游戏等。
- 是人工智能的一个重要分支，适用于复杂的决策场景。
- **推荐资源**：
  - [【2025 最新版】王树森深度强化学习全套课程（280 集）涵盖 PPO 算法/DQN 算法/A3CQ-Learning/SARSA 算法等强化学习经典算法！学完即可就业！](https://www.bilibili.com/video/BV1hhbSzjEi1/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

## 五、NLP（自然语言处理算法）
### （一）NLP 基础
- 自然语言处理是人工智能的一个重要领域，用于处理和理解人类语言。NLP 基础包括文本预处理、分词、词性标注等，为后续的模型训练提供数据支持。
- 是实现人机交互、文本分析等应用的基础。
- **推荐资源**：
  - [自然语言处理发展史](https://blog.csdn.net/2302_80236633/article/details/148474754?spm=1001.2014.3001.5502)
  - [从 Tokenization 到 Embedding](https://blog.csdn.net/2302_80236633/article/details/145848189?spm=1001.2014.3001.5502)
  - [RNN 模型与 NLP 应用(1/9)：数据处理基础](https://www.bilibili.com/video/BV1w54y1L7xK/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （二）Transformer
- Transformer 是一种基于注意力机制的架构，能够处理长文本序列，广泛应用于自然语言处理任务，如翻译、文本生成等。
- 是现代自然语言处理的核心技术之一，极大地提升了模型的性能。
- **推荐资源**：
  - [Transformer 模型(1/2): 剥离 RNN，保留 Attention](https://www.bilibili.com/video/BV1SK4y1d7Qh/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)
  - [Transformer 模型(2/2): 从 Attention 层到 Transformer 网络](https://www.bilibili.com/video/BV1N54y1L7N5/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （三）BERT
- BERT 是一种预训练语言模型，通过大量的文本数据进行预训练，能够捕捉语言的语义信息，广泛应用于自然语言处理任务，如问答系统、文本分类等。
- 是自然语言处理领域的一个重要突破，极大地提升了模型的性能和效果。
- **推荐资源**：
  - [BERT (预训练 Transformer 模型)](https://www.bilibili.com/video/BV1y64y127bF/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)

### （四）transformers 系列课
- HuggingFace 的 transformers 库提供了丰富的预训练模型和工具，方便开发者快速实现自然语言处理任务。
- 是自然语言处理开发中常用的工具之一，能够加速项目开发和模型部署。
- **推荐资源**：
  - [手把手带你实战 HuggingFace Transformers - 入门篇】基础知识与环境安装](https://www.bilibili.com/video/BV1ma4y1g791/?share_source=copy_web&vd_source=94b34c69ba41a5c49e6ca8e8e7d52939)（系列课）