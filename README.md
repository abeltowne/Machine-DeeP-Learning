这是一篇关于机器学习和深度学习的实战知识点集
===
## 第一个为统计学基础和Python基础.
* 快速入门 [Statsmodels](http://blog.163.com/bioinfor_cnu/blog/static/1944622372015815103523278/)<br>
* Python零碎点集<br>
  >>joblib是对机器学习模型的保存重新恢复加载[joblib](http://blog.csdn.net/Dream_angel_Z/article/details/47175373)
## 第二个为seaborn.
Seaborn其实是在matplotlib的基础上进行了更高级的API封装，从而使得作图更加容易，在大多数情况下使用seaborn就能做出很具有吸引力的图。[seaborn](http://blog.csdn.net/suzyu12345/article/details/69029106)
## 第三个为pandas
* 兼具NumPy高性能的数组计算功能以及电子表格和关系型数据库灵活的数据处理功能。他提供了复杂精细的索引功能，以便更为便捷地完成重塑、切片和切块，聚合以及选取数据子集等操作。[pandas](http://python.jobbole.com/84416/)<br>
* pandas数据基础（索引，排序，连接，去重，分箱，异步处理）[pandas基础](http://blog.csdn.net/niuniuyuh/article/details/77102442)
## 第四个为Numpy
Numpy是Python的一个科学计算的库，提供了矩阵运算的功能，其一般与Scipy、matplotlib一起使用。[Numpy](http://www.jb51.net/article/49397.htm)
## 第五个为Scipy
Scipy是一个高级的科学计算库，它和Numpy联系很密切，Scipy一般都是操控Numpy数组来进行科学计算，所以可以说是基于Numpy之上了。[Scipy](http://blog.csdn.net/q583501947/article/details/76735870)
还有像scipy的其他模块[high-level scientific computing](http://www.scipy-lectures.org/intro/scipy.html)
## 第六个为matplotlib
 * matplotlib 绘图可视化知识点整理[matplotlib](http://python.jobbole.com/85106/)<br>
 * matplotlib绘制柱状图[plt绘制柱状图](http://blog.csdn.net/sinat_36772813/article/details/77244189)

## 第七个为scikit-learn中的逻辑回归
`scikit-learn-逻辑回归实践中主要写了如何标准化数据，逻辑回归预测，对其中较为难理解的函数也相应找到对应理解` [logistic](http://blog.csdn.net/pipisorry/article/details/52251305)
## 第八个为scikit-learn中的朴素贝叶斯
`它也是最有名的机器学习的算法之一，它的主要任务是恢复训练样本的数据分布密度。这个方法通常在多类的分类问题上，小样本量问题表现的很好。`[朴素贝叶斯](http://blog.csdn.net/pipisorry/article/details/52251305)。对拉普拉斯平滑的理解[朴素贝叶斯](https://yq.aliyun.com/articles/113512)
## 第九个为scikit-learn中的最近邻
`这是第一遍觉得最容易懂的算法它的思想是通过一个点最邻接的k个点的分类来预测这个点的分类。`[KNN](http://blog.itpub.net/29829936/viewspace-2149679/)
## 第十个为scikit-learn中的决策树
`决策树是一种非参数的监督学习方法，可用于分类和回归的应用中。旨在通过数据学习出简单的决策规则来创建模型，进而预测和判定目标变量的结果。`[决策树](https://www.jianshu.com/p/62c5a5c086be).`其中包含最简单的几个数据划分分类，但是没有剪枝，有明显过拟合现象。`
## 第十一个为scikit-learn中的支持向量机
`支持向量机是一种监督学习数学模型，由n个变量组成的数据项都可以抽象成n维空间内的一个点，点的各个维度坐标值即为各个变量。如果一堆数据项可以分为m个类，那么可以构建m－1个n维超平面将不同种类的数据项的点尽量分隔开，则这些超平面为支持向量面，这个分类数学模型为支持向量机分类模型。`[支持向量机](https://www.jianshu.com/p/84015743be01)代码只提供了分类部分，回归部分没有测试，后续测试。
## 第十二个为scikit-learn中的GBDT
`GBDT也是集成学习Boosting家族的成员，但是却和传统的Adaboost有很大的不同`[GBDT简述](http://www.cnblogs.com/pinard/p/6140514.html)
`GBDT调参是一个比较繁琐的过程可以看代码`[GBDT调参](https://www.cnblogs.com/pinard/p/6143927.html)
## 第十三个为金融风控-逻辑回归-首借用户
`本篇为信贷风控行业主流方法逻辑回归的介绍，首先讲述了数据的预处理，再次讲了ＷＯＥ，ＩＶ值的原理，通过不同的分箱处理如等频或者差分的方式求ＩＶ的最大值，然后通过逻辑回归训练建立最合适的模型.根据py1,py0画ROC曲线，计算AUC值，PY1，PY0,的倍数关系，初步决定评分卡的评分范围值，然后对评分卡的范围进行分组求各组的KS值。算出最大的KS时候对的评分卡分值，根据实际收益调整波动值，得出结果`
## 第十四个为BP神经网络
`本篇为BP神经网络基础。BP网络学习算法的实质是使网络输出总误差函数E的达到最小，因此这是一个优化问题，BP算法具体就是采用“最速下降法”使总误差函数尽量达到最小`[BP神经网络](http://python.jobbole.com/82208/)
![BP神经网络](http://img.blog.csdn.net/20170211175842071?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdHloal9zZg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
