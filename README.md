# AI学习资料整理

对于AI的学习,我个人认为一定要理论结合实践,首先让自己的理论基础过关了,然后再去做一些小项目练手.

这个仓库就是本人在日常学习中以这种思路整理的笔记和一些小项目.

理论部分以Markdown文档为主,我在文档中使用了大量MathJax公式,而Github默认是不解析这些公式的,建议使用Chrome的插件[Github with MathJax](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima/related).或者使用拥有MathJax引擎的Markdown阅读器阅读.

因为MathJax的粗体太难看了(不支持Latex中的bm),所以我在文中的向量并没有用传统的粗体风格.不过除了特殊说明,基本上所有的小写字母都是向量.对于矩阵,我还是使用加粗的方式表示.

实践是利用Python将算法转化为现实的可执行程序.Anaconda包含了本项目用到的绝大多数库,一些Anaconda没有包含的库如下:

- Tensorflow: Google的开源DeepLearning库, [官方网站](https://www.tensorflow.org/)
- Keras: 底层基于Tensorflow, 提供更加人性化的API. [文档传送门](https://keras.io/)

所有小项目基于Python 3.x编写.部分源代码使用jupyter notebook的编写.

## 数学

机器学习的理论要求一定数学基础.其中线性代数尤为重要,其次是概率论和数值优化的一些理论.所以我一开始整理的是一些数学相关的markdown笔记:

- [线性代数Linear Algebra](mathematics/linear_algebra.md)
- [概率论Probability theory](mathematics/probability_theory.md)
- [数值优化Numberical Optimization](mathematics/numerical_optimization.md)
- [凸优化]()

## 深度学习

深度学习属于机器学习的分支,它通过嵌套深层简单概念构造复杂的模型,以解决现实世界一些比较复杂的智能任务.深度学习要求有高等数学(简单的求导,偏导数,梯度等),线性代数和数值优化基础.

下面是深度学习的理论笔记(主要内容来自花书):

- [深度前馈网络Deep Feedforward Network](deep_learning/notes/mlp.md)
- [正则化Regularization](deep_learning/notes/regularization.md)
- [优化方法Optimization](deep_learning/notes/optimization.md)
- [卷积神经网络Convolutional Neural Network](deep_learning/notes/cnn.md)
- [循环神经网络Recurrent Neural Network](deep_learning/notes/rnn.md)
- [深度学习实践Practice]()
- [深度学习应用Application]()
- [线性因子模型Linear Factor Model]()
- [自编码器Autoencoder]()
- [表示学习Express Learning]()
- [结构化概率模型Structured Probabilistic Model]()
- [蒙特卡洛方法Monte Carlo]()
- [近似推断Approximate Inference]()
- [深度生成模型Depth Generation Model]()

下面是Google的计算框架Tensorflow在深度学习上的应用笔记(基于Python):

- [Tensorflow基础](deep_learning/notes/tf_basic.md)
- [Tensorflow图像识别]()
- [Tensorflow自然语言处理]()

一些简单的深度学习小项目:

- [TensorFlow实现线性模型并训练随机数据](deep_learning/tf_projects/linear_model.py)
- [TensorFlow实现深层神经网络](deep_learning/tf_projecrs/deep_nn.py)

## 机器学习

## 计算机视觉

## 自然语言处理
