<!-- TOC -->

- [Q&A record](#qa-record)
    - [$1*1$卷积核作用](#11卷积核作用)
    - [卷积层感受野，小滤波器有效性](#卷积层感受野小滤波器有效性)
    - [RCNN](#rcnn)
        - [Efficient Graph-Based Image Segmentation(基于图的图像分割)](#efficient-graph-based-image-segmentation基于图的图像分割)
        - [Selective Search](#selective-search)
        - [bounding-box regression](#bounding-box-regression)
        - [RCNN](#rcnn-1)
        - [mAP,Precision,Recall](#mapprecisionrecall)
        - [Liner-classifier](#liner-classifier)
    - [Fast-RCNN](#fast-rcnn)
        - [双线性插值法(Bilinear Interpolation)](#双线性插值法bilinear-interpolation)
        - [RoIPooling、RoIAlign](#roipoolingroialign)
        - [用SVD压缩深度模型的全连接层](#用svd压缩深度模型的全连接层)
        - [SPP-net简要介绍](#spp-net简要介绍)
        - [池化层反向传播求梯度](#池化层反向传播求梯度)
        - [RoIPooling层反向传播求梯度](#roipooling层反向传播求梯度)
    - [一文读懂Faster RCNN](#一文读懂faster-rcnn)
    - [如何评价rcnn、fast-rcnn和faster-rcnn这一系列方法？](#如何评价rcnnfast-rcnn和faster-rcnn这一系列方法)
    - [Semantic Segmentation](#semantic-segmentation)

<!-- /TOC -->
# Q&A record

## $1*1$卷积核作用
>[[来源]](https://www.cnblogs.com/CZiFan/p/9490565.html)

## 卷积层感受野，小滤波器有效性
>[[来源]](https://blog.csdn.net/program_developer/article/details/80958716)


## RCNN
>[[CNN-Object Detection 视频简明教程来源]](https://www.youtube.com/playlist?list=PL_IHmaMAvkVxdDOBRg2CbcJBq9SY7ZUvs)
### Efficient Graph-Based Image Segmentation(基于图的图像分割)
>[[博客来源1]](https://blog.csdn.net/guoyunfei20/article/details/78727972)[[博客来源2]](https://blog.csdn.net/surgewong/article/details/39008861?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.channel_param&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-2.channel_param)
### Selective Search
>[[博客来源]](https://www.cnblogs.com/zyly/p/9259392.html#_labelTop)
其中第三步进行 Selective Search 选择很多目标 bounding-box 后，根据非极大值抑制进一步筛选bounding-box。原文的介绍有待考证。

### bounding-box regression
>[[博客来源]](https://blog.csdn.net/czp_374/article/details/86631910?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.nonecase&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.nonecase)
### RCNN
>[[简介博客来源]](https://blog.csdn.net/briblue/article/details/82012575)<br>论文见目录《Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation》
### mAP,Precision,Recall
>[[博客来源]](http://blog.sina.com.cn/s/blog_9db078090102whzw.html)
### Liner-classifier
>[[来源]](https://cs231n.github.io/linear-classify/)

## Fast-RCNN
>[[简介博客来源]](https://blog.csdn.net/u014380165/article/details/72851319)<br>
论文见目录《Girshick_Fast_R-CNN_ICCV_2015_paper》
### 双线性插值法(Bilinear Interpolation)
>[[博客来源]](https://blog.csdn.net/qq_37577735/article/details/80041586)
### RoIPooling、RoIAlign
>[[博客来源]](https://www.cnblogs.com/wangyong/p/8523814.html)
### 用SVD压缩深度模型的全连接层
>[[博客来源]](https://my.oschina.net/liusicong/blog/866364)
### SPP-net简要介绍
>[[博客来源]](https://www.cnblogs.com/gongxijun/p/7172134.html)
### 池化层反向传播求梯度
>[[博客来源]](https://blog.csdn.net/Jason_yyz/article/details/80003271)
### RoIPooling层反向传播求梯度
>[[博客来源]](https://www.cnblogs.com/kerwins-AC/p/9651352.html)
<br>[[知乎来源(更清晰)]](https://zhuanlan.zhihu.com/p/45293568)

## 一文读懂Faster RCNN 
>[[知乎来源]](https://zhuanlan.zhihu.com/p/31426458) 

## 如何评价rcnn、fast-rcnn和faster-rcnn这一系列方法？
>[[知乎来源]](https://www.zhihu.com/question/35887527)
## Semantic Segmentation
>[[Awesome Semantic Segmentation资源汇总]](https://github.com/mrgloom/awesome-semantic-segmentation#awesome-semantic-segmentation)
