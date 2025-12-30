# XAI_assignment3
肺炎胸部X光图像异常检测与模型解释
## 项目概述

本项目基于胸部X光图像数据集，完成肺炎异常检测任务，包括：
1. 数据预处理
2. 训练3个ML/DL模型并评估
3. 实现两种XAI方法（GradCAM和LIME）进行模型解释

## 数据集
- **数据来源（自行下载）**: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
- **数据路径**: `/root/autodl-tmp/data` （本项目基于AutoDL服务，请修改自己的数据路径）
- **数据集结构**:
  - `train/`: 5,217张 (NORMAL: 1,342, PNEUMONIA: 3,875)
  - `test/`: 624张 (NORMAL: 234, PNEUMONIA: 390)
  - `val/`: 16张 (NORMAL: 8, PNEUMONIA: 8)

## 项目结构

```
7009assignment3/
├── main.ipynb                    # 主Jupyter Notebook
├── requirements.txt              # Python依赖包
├── README.md                     # 项目说明文档
└── results/                      # 结果输出目录（自行创建）
    ├── models/                   # 保存的模型文件
    ├── figures/                  # 可视化图表
    └── explanations/             # XAI解释结果
```

## 安装依赖

```bash
pip install -r requirements.txt
```
