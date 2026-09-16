#                    研一深度学习入门指南

​												（时间：2026年9月13日 - 至今，宋璞、吴水珍）

### 一、环境的搭建

**（1）系统环境**

​        深度学习的环境分为windows系统和linux系统。

​        如果在自己的电脑上跑，一般采用windows本地开发 + GPU服务器训练。没有服务器也可以先用CPU跑通流程。

​        若在云服务器（AutoDL）上跑，需要使用linux系统，需要熟悉Linux命令行。

**（2）软件清单**

- 推荐使用Visual Studio Code，代码编辑、终端与调试。
- Git：拉取、保存与提交代码。
- Miniconda或Anaconda或UV：管理Python虚拟环境。
- Jupyter：
- Python、PyTorch、TorchVision。
- 安装参考教程（有问题，问AI）：[深度学习环境配置超详细教程【Anaconda+PyTorch(GPU版)+CUDA+cuDNN】-CSDN博客](https://blog.csdn.net/qq_43874102/article/details/123164105)
- [ 【深度学习环境配置】Anaconda + PyCharm + CUDA + cuDNN + PyTorch + OpenCV_anaconda安装opencv-CSDN博客](https://blog.csdn.net/shinuone/article/details/129054444?spm=1001.2101.3001.6650.16&utm_medium=distribute.pc_relevant.none-task-blog-2~default~ElasticSearch~Rate-16-129054444-blog-123164105.235^v43^pc_blog_bottom_relevance_base8&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2~default~ElasticSearch~Rate-16-129054444-blog-123164105.235^v43^pc_blog_bottom_relevance_base8&utm_relevant_index=27)

- 安装参考教程（服务器版，有问题，问AI）[AutoDL服务器配置+配置深度学习环境（pytorch）_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV17S4y1b7LV/?vd_source=3943fa0f47d1e24347b59fbb50be07c9)

**（3）环境测试**

​		在安装完相关软件后，测试当前环境是否可以（自己可在CSDN找教程）



### 二、了解理论与背景

（1）所提供的两本PDF书籍，一本为实战书籍《pytorch深度学习实战》，一本为理论知识《nndl-book》。

	- 《pytorch深度学习实战》实战书籍优先完成张量、自动微分、训练分类模型和可视化相关章节
	- 《nndl-book》理论书籍优先阅读基础模型和优化相关章节。

（2）



### 三、动手跑项目

（1）第一个任务建议为 MNIST 手写数字分类

- 下载与查看数据；
- 理解样本、标签、张量维度
- 建立简单全连接网络
- 编写训练、验证、测试循环
- 输出 loss 和 accuracy
- 保存最佳 checkpoint
- 抽取错误样本并分析原因



（2）第二个任务再进入 CIFAR-10 与 CNN



### 四、理论学习与调参

​	初步了解以下这些概念：

- 数据、标签、特征、训练/验证/测试集

- 张量与维度变化

- 线性层、激活函数、Softmax

- 损失函数与准确率

- 梯度下降、反向传播、自动微分

- 优化器、学习率、batch size、epoch

- 过拟合、正则化、数据增强

- CNN 的卷积、池化、感受野

- 混淆矩阵、Precision、Recall、F1

  

### 五、代码复现（进阶）

Buildformer

服务器上复现代码参考教程：[深度学习代码复现基本流程（以SDSC-UNet为例）_深度学习顶会论文复现-CSDN博客](https://blog.csdn.net/qq_53723681/article/details/144513686)



### 六、进一步学习

了解目标检测、分割、变化检测等不同任务的区别，常用的方法有哪些，梳理发展脉络。

熟悉常用的模型与骨干网络。

寻找新的方法。

学会模块拼接、模块修改。



### 七、确定自己的研究方向