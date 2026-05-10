# HW07: 胸部 X 光肺炎影像二分类实验

## 项目简介
本项目基于 Kaggle 公开数据集 **Chest X-Ray Images (Pneumonia)**，使用卷积神经网络（CNN）实现**正常胸片 / 肺炎胸片**二分类任务。
实验在 **Kaggle Notebook CPU 环境**下完成，无需 GPU，满足课程作业全部要求。

## 数据集
- 数据集名称：Chest X-Ray Images (Pneumonia)
- 类别：NORMAL（正常）、PNEUMONIA（肺炎）
- 划分方式：从训练集按 **8:2** 重新划分训练集与验证集
- 运行平台：Kaggle Notebook

## 文件结构
```
hw07/
├── train.ipynb          # 完整代码 + 运行结果
├── report.md            # 实验报告（含结果分析、图表）
├── requirements.txt     # 项目依赖库
├── README.md            # 项目说明
└── figures/
    ├── training_curves.png    # 训练/验证准确率与损失曲线
    └── confusion_matrix.png   # 测试集混淆矩阵
```

## 运行环境
- Python 3.x
- 深度学习框架：TensorFlow / Keras
- 运行模式：**CPU 即可运行**

## 依赖安装
```bash
pip install -r requirements.txt
```

## 核心结果
- 测试集准确率：~87%
- 肺炎类别召回率：~99.5%
- 模型：轻量级 CNN
- 训练轮数：8 epochs

## 实验内容
1. 数据集加载与路径确认
2. 按 8:2 划分训练集与验证集
3. 图像预处理与数据增强
4. CNN 模型搭建、训练与评估
5. 绘制训练曲线 & 混淆矩阵
6. 完成实验报告与结果分析

