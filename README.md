# SSD-NeXt_PyTorch
## 基于SSD改进的一阶段目标检测算法
### SSD-NeXt改进内容有
+ 使用ConvNeXt-Tiny作为骨干网络，详细信息请参考https://github.com/facebookresearch/ConvNeXt
+ 使用FPNeXt、PANeXt、SPP进行特征融合
+ 使用Muilt Scale NeXt获取多尺度特征图
+ 使用基于位置预测的注意机制(ALP)辅助预测
## 内容简介
### 编写环境
Python3.8</br>
PyTorch1.10.0</br>
Windows10</br>
### 功能
+ 构建SSD300和SSD-NeXt模型
+ 使用VOC、KITTI数据集进行训练和测试
+ 基于PyQt5实现的目标检测系统GUI，可利用SSD-NeXt预训练权重对图片、视频进行目标检测
## 使用方式
### 训练
运行 train.py 即可
### 测试
设置参数：checkpoint=训练权重文件路径，mode='test'</br>
然后运行 train.py 即可
### GUI
运行 GUI.py 即可
## 其他
预训练权重下载地址：</br>
链接：https://pan.baidu.com/s/1JzFRfBvKGaWqMGtaSeqYBQ?pwd=itsx </br>
提取码：itsx</br>
