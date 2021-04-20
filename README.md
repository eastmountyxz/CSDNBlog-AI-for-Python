# CSDNBlog-AI-for-Python
为了更好地管理博客文章，分享更好的知识，该系列资源为作者CSDN博客的备份文件。本资源为作者Python人工智能的系列博客，涉及Theano、TensorFlow、Keras搭建的回归神经网络、CNN、RNN、LSTM等内容。基础性文章，希望对您有所帮助。

By：Eastmount CSDN Yangxiuzhang

---


本专栏主要结合作者之前的博客、AI经验和相关视频及论文介绍，后面随着深入会讲解更多的Python人工智能案例及应用。基础性文章，希望对您有所帮助，如果文章中存在错误或不足之处，还请海涵~作者作为人工智能的菜鸟，希望大家能与我在这一笔一划的博客中成长起来。写了这么多年博客，尝试第一个付费专栏，但更多博客尤其基础性文章，还是会继续免费分享，但该专栏也会用心撰写，望对得起读者，共勉！


同时推荐前面作者另外五个Python系列文章。从2014年开始，作者主要写了三个Python系列文章，分别是基础知识、网络爬虫和数据分析。2018年陆续增加了Python图像识别和Python人工智能专栏。


- Python基础知识系列：[Python基础知识学习与提升](https://blog.csdn.net/eastmount/category_2547623.html)
- Python网络爬虫系列：[Python爬虫之Selenium+BeautifulSoup+Requests](https://blog.csdn.net/eastmount/category_9264385.html)
- Python数据分析系列：[知识图谱、web数据挖掘及NLP](https://blog.csdn.net/eastmount/category_9265165.html)
- Python图像识别系列：[Python图像处理及图像识别](https://blog.csdn.net/eastmount/category_9278090.html)
- Python人工智能系列：[Python人工智能及知识图谱实战](https://blog.csdn.net/eastmount/category_9292178.html)

<div algin="center">
    <img src="https://img-blog.csdnimg.cn/2019112810131675.png" />
</div>

前文：<br />
- [[Python人工智能] 一.TensorFlow2.0环境搭建及神经网络入门](https://blog.csdn.net/Eastmount/article/details/103282042) <br />
- [[Python人工智能] 二.TensorFlow基础及一元直线预测案例](https://blog.csdn.net/Eastmount/article/details/103322331) <br />
- [[Python人工智能] 三.TensorFlow基础之Session、变量、传入值和激励函数](https://blog.csdn.net/Eastmount/article/details/103336214) <br />
- [[Python人工智能] 四.TensorFlow创建回归神经网络及Optimizer优化器](https://blog.csdn.net/Eastmount/article/details/103410289) <br />
- [[Python人工智能] 五.Tensorboard可视化基本用法及绘制整个神经网络](https://blog.csdn.net/Eastmount/article/details/103569858) <br />
- [[Python人工智能] 六.TensorFlow实现分类学习及MNIST手写体识别案例](https://blog.csdn.net/Eastmount/article/details/103586271) <br />
- [[Python人工智能] 七.什么是过拟合及dropout解决神经网络中的过拟合问题](https://blog.csdn.net/Eastmount/article/details/103595096) <br />
- [[Python人工智能] 八.卷积神经网络CNN原理详解及TensorFlow编写CNN](https://blog.csdn.net/Eastmount/article/details/103620235) <br />
- [[Python人工智能] 九.gensim词向量Word2Vec安装及《庆余年》中文短文本相似度计算](https://blog.csdn.net/Eastmount/article/details/103647573) <br />
- [[Python人工智能] 十.Tensorflow+Opencv实现CNN自定义图像分类案例及与机器学习KNN图像分类算法对比](https://blog.csdn.net/Eastmount/article/details/103757386) <br />
- [[Python人工智能] 十一.Tensorflow如何保存神经网络参数](https://blog.csdn.net/Eastmount/article/details/103810291) <br />
- [[Python人工智能] 十二.循环神经网络RNN和LSTM原理详解及TensorFlow编写RNN分类案例](https://blog.csdn.net/Eastmount/article/details/103811752) <br />
- [[Python人工智能] 十三.如何评价神经网络、loss曲线图绘制、图像分类案例的F值计算](https://blog.csdn.net/Eastmount/article/details/103847406) <br />
- [[Python人工智能] 十四.循环神经网络LSTM RNN回归案例之sin曲线预测](https://blog.csdn.net/Eastmount/article/details/103914851) <br />
- [[Python人工智能] 十五.无监督学习Autoencoder原理及聚类可视化案例详解](https://blog.csdn.net/Eastmount/article/details/103990297) <br />
- [[Python人工智能] 十六.Keras环境搭建、入门基础及回归神经网络案例](https://blog.csdn.net/Eastmount/article/details/104313140) <br />
- [[Python人工智能] 十七.Keras搭建分类神经网络及MNIST数字图像案例分析](https://blog.csdn.net/Eastmount/article/details/104366166) <br />
- [[Python人工智能] 二十六.基于BiLSTM-CRF的医学命名实体识别研究（上）数据预处理](https://blog.csdn.net/Eastmount/article/details/111526240) <br />
- [[Python人工智能] 二十七.基于BiLSTM-CRF的医学命名实体识别研究（下）模型构建](https://blog.csdn.net/Eastmount/article/details/112249976)  <br />
- [[Python人工智能] 二十八.Keras深度学习中文文本分类万字总结（CNN、TextCNN、LSTM、BiLSTM、BiLSTM+Attention）](https://blog.csdn.net/Eastmount/article/details/114809729)  <br />
- [[Python人工智能] 二十九.什么是生成对抗网络GAN？基础原理和代码普及(1)](https://blog.csdn.net/Eastmount/article/details/115256149)  <br />
- [《人工智能狂潮》读后感——什么是人工智能？(一)](https://blog.csdn.net/Eastmount/article/details/104161047) <br />


---

持续更新中.....

By: Eastmount 2021-04-20

