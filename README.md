# cs229
  记录cs229学习笔记并用python实现相应算法

## 学习笔记

### 1. linearRegression  

推导并实现了局部加权线性回归，并选取不同的bandwidth进行拟合，可视化了不同bandwidth对局部加权线性回归的影响。

### 2. logisticRegression  

主要总结了逻辑回归的常用公式。推导了逻辑回归cost function的Hessian矩阵。介绍了牛顿法的原理，并且采用牛顿法求解逻辑回归的参数。

### 3. generalizedLinearModels  

- generalizedLinearModels  
  介绍了指数分布族，并推导正态分布和伯努利分布都属于指数分布族。介绍了广义线性模型的三个假设，并推导了普通最小二乘法以及逻辑回归都是广义线性模型的特例。  
- softmaxRegression  
  推导多项分布属于指数分布族以及softmax是广义线性模型的特例，推导并实现了softmax regression，采用批量梯度下降求解softmax regression的参数。

### 4. generativeLearningAlgorithms  

- generativeLearningAlgorithms  
  介绍了生成学习算法  
- gaussianDiscriminantAnalysis  
  介绍了多元正态分布，推导了如何通过最大似然估计求解高斯判别分析的参数，讨论并推导了高斯判别分析和逻辑回归的关系。  
- naiveBayes  
  推导并实现了朴素贝叶斯算法（基于伯努利模型）

### 5. supportVectorMachine　　

ing

## 课后作业（不更新）
### 1. ex1-linearRegression  
分别通过批量梯度下降法和求解正规方程组来求解线性回归的参数。并绘制了在不同学习速率下，cost function的下降情况。
### 2. ex2-logisticRegression  
主要实现了带正则化项的逻辑回归，通过批量梯度下降法求解其参数。同时进行Feature mapping,使得逻辑回归能够更好地处理线性不可分的情况。并绘制了在正则化参数lambda不同取值下，决策边界的变化情况（即过拟合与欠拟合）。
### 3. ex3-neuralNetwork  
整理了ex2实现的逻辑回归函数，采用one-vs-all的方法，使用逻辑回归对手写数字进行识别。并采用已经训练好的神经网络权重，实现了神经网络的前向传播，对手写数字进行识别。