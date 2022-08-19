# Homework 基于Unet实现语义分割
## 开发环境
python==3.8.8     ;Pytorch==1.11.0
## 数据集
使用Weizmann Horse数据集训练，测试  
设置路径如下：
'''
dataset
├──── Training_set
│    ├──── alpha (431 images)
│    └──── merged (43100 images)
├──── Test_set
│    ├──── alpha (50 images)
│    ├──── fg (50 images)
│    ├──── merged (1000 images)
│    └──── trimaps (1000 images)
'''
