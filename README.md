## 说明
- 一些开源数据集。
- Kaggle数据集地址：https://www.kaggle.com/datasets
- 企业数据不可公开和泄露，在开源数据集上做一些学习和尝试是个不错的选择。
## 数据集简介
### 1. ufcdata
- 来源：kaggle
- 竞赛："UFC-Fight historical data from 1993 to 2019"
- 描述：记录了UFC比赛及选手的统计信息
### 2. creditcardfraud
- 来源：kaggle
- 竞赛："Credit Card Fraud Detection"
- 描述：匿名信用卡的欺诈和正常标记交易数据
### 3. heart-disease-uci
- 来源：kaggle
- 竞赛："Heart Disease UCI"
- 描述：心脏疾病数据集
### 4. titanic
- 来源：kaggle
- 竞赛："Titanic: Machine Learning from Disaster"
- 描述：泰坦尼克数据集
### 5. fashionmnist
- 来源：kaggle
- 竞赛："Fashion MNIST"
- 描述：时尚图像数据集
### 6. boston housing price
- 波士顿房价数据
- 可用于回归挖掘
### 7. mnist_dataset
- 手写数字数据集
- 图像多分类
- 加载方式：
```
from tensorflow.examples.tutorials.mnist import input_data  # 1.0版本tf
mnist = input_data.read_data_sets('mnist_dataset/',one_hot=True) # 解压后的文件
```
### 8. cat-in-the-dat
- 类别特征数据集
- Kaggle "Categorical Feature Encoding Challenge"竞赛
- 二分类