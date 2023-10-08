# jittor-galaxy--CGAN

## 简介
        
本项目包含了第三届计图挑战赛计图 - 手写数字生成的代码实现。本项目的特点是：在手写数字图片数据集 MNIST 上训练 Conditional GAN模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

##安装

本项目的运行环境为：
- ubuntu 20.04
- python 3.9
- jittor 1.3.8

##训练

运行以下命令完成训练：
```
python CGAN.py

```

## 致谢

此项目基于论文 *Conditional generative adversarial nets* 实现，部分代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。
