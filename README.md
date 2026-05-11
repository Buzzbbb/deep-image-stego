# 深度图像信息隐藏与提取框架

`deep-image-stego` 是一个信息隐藏与网络空间安全方向的可运行开源项目，包含核心算法代码、命令行入口、实验配置、示例脚本和 smoke tests。

## Overview

本项目实现基于深度学习的图像信息隐藏与恢复框架，包含数据集加载、秘密图像编码、载体图像融合、失真约束训练、秘密信息解码和可视化评估等功能。框架预留 U-Net、注意力模块和残差网络等模型接口，可根据不同载体质量要求调整嵌入容量、感知损失和恢复损失。系统输出 PSNR、SSIM、LPIPS 等图像质量指标，并保存训练日志和样例结果，适合用于人工智能信息隐藏、图像水印和隐写分析对抗实验。

## Features

- 统一的数据加载、实验配置和结果保存流程
- 面向信息隐藏/数字水印/隐写分析任务的模块化设计
- 支持实验指标输出、样例结果归档和后续算法扩展
- 适合课程实验、毕业设计、论文复现实验和课题组日常开发

## Quick Start

```bash
python examples/demo.py
python -m unittest discover -s tests
open docs/visual_report.html
python -m deep_image_stego.cli --message "demo payload" --report docs/cli_report.md
```

## Keywords

deep learning · image steganography · U-Net · perceptual loss

## Authors

- 负责人：林裕斌
- 参与人：曾科、田承金
- 指导教师：吕善翔
- 单位：暨南大学网络空间安全学院

## License

本项目采用 MIT License 开源。Copyright (c) 2026 Lin Yubin, Zeng Ke, Tian Chengjin, Shanxiang Lv, Jinan University.
