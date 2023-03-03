# 机器学期和深度学习参考资料大全
在这里整理自己入门机器学习以及深度学习用到的资料以及遇到的问题

## 机器学习
1.机器学习入门参考书：周志华《机器学习》[主页](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/MLbook2016.htm)

这本书适合新手入门，因封面有很多西瓜并且书中也用挑选好的西瓜作为算法的任务，所以也称为西瓜书。是我接触的第一本机器学习的书籍。


2.python入门教学视频：中国大学MOOC《Python语言程序设计》[课程主页](https://www.icourse163.org/course/BIT-268001)

上书只讲了机器学习的思想以及算法，并没有限定某种语言，但是现在机器学习用python还是方便很多，并且很多开源项目也是用python完成的。这个编程课程适合零基础或者非零基础的同学，讲python简单明了，一共约24个小时，2倍速每天4小时，3天就可以速成python。

这里有自己的博客[从零开始机器学习](https://blog.csdn.net/qq_45510888/article/details/113060102)


3.python在机器学习中的应用：中国大学MOOC《Python机器学习应用》[课程主页](https://www.icourse163.org/course/BIT-1001872001)

完成以上2步，实际上理论与工具都已经具备了，那么现在就只剩下将二者结合了。这个视频很短，讲解原理部分都略过了，侧重于举例子说明与python的结合，以及使用第三方库sklearn的方法。

这里有我自己的笔记[机器学习算法概述](https://blog.csdn.net/qq_45510888/article/details/113444640)


4.一个机器学习资料大全：MachineLearning  [主页](https://allmachinelearning.github.io/MachineLearning/)  [GitHub](https://github.com/allmachinelearning/MachineLearning)

里面东西很全，足够系统的学习。


## 深度学习
1.深度学习经典之作：伊恩·古德费洛《深度学习》[主页](https://www.deeplearningbook.org/)

这本书很多地方都会推荐，也叫花书，此处不赘述。


2.深度学习教学视频：李宏毅《机器学习》[bilibili链接](https://www.bilibili.com/video/av94519857)

虽然名字是机器学习，但是大部分内容都是深度学习。看完我只想说，李宏毅，YYDS，讲的特比好，强烈推荐，如果不喜欢看书喜欢看网课的一定要认真看，B站下面的评论有分享出来的PPT和数据，感谢B站的小伙伴！

这里附李宏毅的个人网站：[主页](http://speech.ee.ntu.edu.tw/~tlkagk/index.html)


3.pytorch环境搭建：

了解深度学习之后，部分模型需要借助一些框架帮助实现了，深度学习的框架有很多，自己用的是pytorch，其他似乎大同小异。注意官网下载的python只是一个解释器，为了开发方便会利用IDE，值得注意的是，python语言对每一个工程都会有其独立的环境，于是为了方便管理这些环境，anaconda诞生了。anaconda也有自己携带的解释器，并且在下载pytorch时需要选择环境，conda代表的就是anaconda，pip代表python本身，由于二者速度都很慢，记得使用国内镜像来加速或者离线下载，并且conda的离线和pip的离线也不一样，小心踩坑。

pytorch官方文档：[中文文档](https://pytorch.apachecn.org/docs/1.0/)


4.利用GPU：

CPU计算能力相比GPU较差，所以一些计算需要放在GPU上面进行，所以需要配置GPU的环境，在自己电脑上或者连接到服务器。也就是安装cuda和cudavision，网上有很多教程，这里不赘述，注意首先查看自己的NVIDIA-CUDA驱动版本，版本需要和cuda以及python等对应。


5.神经网络与深度学习：[主页](http://neuralnetworksanddeeplearning.com/)


6.机器学习的动机与应用：[网易公开课](http://open.163.com/newview/movie/free?pid=M6SGF6VB4&mid=M6SGHFBMC)


7.pytorch教学视频：[bilibili](https://www.bilibili.com/video/av89899074)

这个视频重点讲pytorch的应用，都是用实例来讲的，个人比较推荐，如果侧重基础语法，可以参考：[bilibili](https://www.bilibili.com/video/av97078147)


## 数据集
1.一个比较全的数据集导航：[CVonline](http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm#action)

以及其翻译版：[CSDN博客](https://blog.csdn.net/weixin_41036461/article/details/80667690)

2.LSUN：[主页](http://dl.yf.io/lsun/)

是一个很大的数据集，比较权威。建议搭配其转换方法食用，效果更佳：[CSDN博客](https://blog.csdn.net/OpenSceneGraph/article/details/108975017)


## 论文相关
1.使用必应学术、百度学术等按照题目进行搜索，会显示其来源


2.根据其来源，到相应的地方下载，利用学校的数据库，当然也有开源的，例如ResearchGate、arXiv都可以免费下载


3.找论文相关的代码：[paper with code](https://paperswithcode.com/)


4.一个机器学习论坛：[Kaggle](https://www.kaggle.com/)


5.几个不易翻译的短语：

"ground truth"一词指的是训练集对监督学习技术的分类的准确性。这在统计模型中被用来证明或否定研究假设。"ground truth"这个术语指的是为这个测试收集适当的目标（可证明的）数据的过程。翻译的意思是地面实况，放到机器学习里面，再抽象点可以把它理解为真值、真实的有效值或者是标准的答案。

"ablation experiment"就是用来告诉你或者读者整个流程里面的关键部分到底起了多大作用，就像Ross将RPN换成SS进行对比实验，以及与不共享主干网络进行对比，就是为了给读者更直观的数据来说明算法的有效性。知乎回答：你朋友说你今天的样子很帅，你想知道发型、上衣和裤子分别起了多大的作用，于是你换了几个发型，你朋友说还是挺帅的，你又换了件上衣，你朋友说不帅了，看来这件衣服还挺重要的。


## 其他资料
1.IT相关的书籍大全：[GitHub](https://github.com/XiangLinPro/IT_book)
