# Text-to-Image 简介

## 1. 简介
人类感知系统通过五种基本感官（听觉、触觉、味觉、嗅觉和视觉）来理解外部世界的刺激。我们接收到的刺激信息往往来自于不同时间和空间中的多个事件，因此我们需要在这种"多模态"感知中整合各类感官信息，才能更好地理解世界。

## 2. 背景
### 2.1 数据集
以下是一些重要的文本生成图像的数据集及其信息：

| 年份 | 数据集 | 类别 | 图片数（分辨率） | 其他信息 |
| -------- | -------- | -------- | -------- | -------- |
| 2008 | Oxford-102 Flowers | 花卉 | 8,189 | 无 |
| 2011 | CUB-200-2011 | 鸟类 | 11,788 | 包含边框、分割信息等 |
| 2014 | MS-COCO2014 | 多种物体 | 120,000 | 边框、分割信息等 |
| 2022 | LAION-400M | 随机抓取 | 400M | KNN索引等 |
| 2023 | ANNA | 新闻 | 29,625 | 无 |

## 3. 生成模型
主要的文本生成图像方法包括：

### 3.1 GAN 模型
#### [基于条件GAN]
- 2016~2021：
  - `Generative Adversarial Text to Image Synthesis` [论文链接](http://proceedings.mlr.press/v48/reed16.pdf) [代码链接](https://github.com/reedscot/icml2016)
  - `Tell, Draw, and Repeat` [论文链接](https://openaccess.thecvf.com/content_ICCV_2019/papers/El-Nouby_Tell_Draw_and_Repeat_ICCV_2019_paper.pdf) [代码链接](https://github.com/Maluuba/GeNeVA)

### 3.2 自回归模型
#### [基于Transformer]
- 2021：
  - `Zero-Shot Text-to-Image Generation` [论文链接](https://arxiv.org/pdf/2102.12092.pdf) [代码链接](https://github.com/openai/DALL-E)

### 3.3 Diffusion 模型
#### [基于扩散]
- 2022：
  - `High-Resolution Image Synthesis with Latent Diffusion Models` [论文链接](https://arxiv.org/abs/2112.10752) [代码链接](https://github.com/CompVis/latent-diffusion)

## 4. 生成应用
### 4.1 文本生成图像
- 通过GAN、Diffusion、Transformer等生成不同风格的人物面孔。

### 4.2 文本生成其他类型
- 如生成三维物体、情景图等。

## 5. 讨论
本文讨论了多模态感知和文本生成图像技术的演变，未来该领域可能在提高图像质量、降低计算复杂度等方面继续取得突破。