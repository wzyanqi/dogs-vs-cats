# dogs-vs-cats
[猫狗大战](https://www.kaggle.com/c/dogs-vs-cats)是kaggle比赛中的经典题目，也是Udacity的机器学习学位的毕业课题。要求在最终在测试集的结果排在Public Leaderboard的前10%，具体要求为[dog_vs_cat](https://github.com/nd009/capstone/tree/master/dog_vs_cat)。  

### 项目资料
数据集下载：[训练集 + 测试集](https://www.kaggle.com/c/dogs-vs-cats/data)  ，kaggle一共提供了两个数据集train与test。其中train set包含25000个样本，cat和dog各12500个。
![](https://i.imgur.com/kS76chv.jpg)  
test set包含12500张图片，但没有分类。  
![](https://i.imgur.com/BW4ga6N.jpg)

### 神经网络模型
本次项目采用经典的ResNet50模型，ResNet在2015年提出以来，曾在ImageNet比赛classification任务上获得第一名，因为它“简单与实用”并存，之后很多方法都建立在ResNet50或者ResNet101的基础上完成的，检测，分割，识别等领域都有着广泛的运用。

![image](http://img.blog.csdn.net/20180114184946861?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbGFucmFuMg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
![image](http://img.blog.csdn.net/20180114205444652?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbGFucmFuMg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### 文件结构
- file3.csv 测试集结果
- model.png 神经网络模型结构图
- test.ipynb/test.html 程序文件
- training_log2.txt 训练log文件
- 毕业报告 2.5.pdf 提交的毕业报告
 
