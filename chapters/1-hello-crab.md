# 第一章 Hello Crab

## 1.1 基础概念

Crab是一个基于python的推荐系统框架，使用numpy（提供强大的矩阵运算功能），scipy（提供大量科学测量工具），metplotlib（绘图）科学计算包。

使用Crab你可以很方便的构建自己的简易推荐系统.

## 1.2 模块

* datasets
	
	使用movielens100k数据集并包装了相应的使用函数

* metrics

	计算模块，包含了向量距离计算，评估预测等

* models
	
	数据模型模块，建立了user模型以及item模型，方便处理数据
	
* recommenders
	
	推荐模块，分为knn聚类模块，以及svd奇异值分解模块，提供相应的推荐算法。

* similarities

	相似度计量模块	

* tests

	测试模块

* utils

	功能模块，兼容python2、3
