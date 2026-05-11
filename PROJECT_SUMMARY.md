# 深度图像信息隐藏与提取框架

英文名称：`deep-image-stego`

开源地址：`https://github.com/Buzzbbb/deep-image-stego`

项目时间：2024年10月-至今

## 作者信息

- 负责人：林裕斌，专业：网络空间安全，硕士生
- 参与人：曾科，专业：网络空间安全，硕士生
- 参与人：田承金，专业：网络空间安全，硕士生
- 指导教师：吕善翔，网络空间安全学院教师

## 项目内容

本项目实现基于深度学习的图像信息隐藏与恢复框架，包含数据集加载、秘密图像编码、载体图像融合、失真约束训练、秘密信息解码和可视化评估等功能。框架预留 U-Net、注意力模块和残差网络等模型接口，可根据不同载体质量要求调整嵌入容量、感知损失和恢复损失。系统输出 PSNR、SSIM、LPIPS 等图像质量指标，并保存训练日志和样例结果，适合用于人工智能信息隐藏、图像水印和隐写分析对抗实验。

## 影响力

项目可为图像隐写、神经网络水印和生成式内容保护研究提供基础代码，帮助学生快速搭建深度图像隐藏实验流程，并降低复现实验的工程门槛。

## 开发语言

Python

## 代码规模

1012行（按当前项目 src/tests/examples 下 Python 代码统计）

## 建议仓库结构

```text
deep-image-stego/
├── README.md
├── LICENSE
├── PROJECT_SUMMARY.md
├── src/
├── examples/
├── tests/
├── docs/
└── screenshots/
```

## 截图材料

- 项目目录截图：`screenshots/directory.png`
- 项目说明截图：`screenshots/readme.png`
- 项目声明截图：`screenshots/license.png`

## 关键词

deep learning, image steganography, U-Net, perceptual loss
