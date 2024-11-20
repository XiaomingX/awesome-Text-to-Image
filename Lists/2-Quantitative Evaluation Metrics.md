# 量化评价指标

* **Inception Score (IS)**  
  用于评估生成模型生成图像的多样性和真实性。  
  [论文](https://arxiv.org/pdf/1606.03498.pdf) [代码](https://github.com/sbarratt/inception-score-pytorch)

* **Fréchet Inception Distance (FID)**  
  通过比较生成图像和真实图像的分布来评估生成质量。  
  [论文](https://papers.nips.cc/paper/7240-gans-trained-by-a-two-time-scale-update-rule-converge-to-a-local-nash-equilibrium.pdf) [代码](https://github.com/mseitzer/pytorch-fid)

* **R-precision**  
  用于文本生成图像的匹配准确度。  
  [论文](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf) [代码](https://github.com/dongdongdong666/CPGAN)

* **L<sub>2</sub> 误差**  
  衡量生成图像与目标图像之间的像素差异。  
  [论文](https://papers.nips.cc/paper/7290-text-adaptive-generative-adversarial-networks-manipulating-images-with-natural-language.pdf)

* **Learned Perceptual Image Patch Similarity (LPIPS)**  
  评估图像之间的感知相似度。  
  [论文](https://arxiv.org/abs/1801.03924) [代码](https://github.com/richzhang/PerceptualSimilarity)

* **CLIPScore**  
  使用CLIP模型评估图像和文本的匹配程度。  
  [论文](https://arxiv.org/abs/2104.08718) [代码](https://github.com/jmhessel/clipscore)

* **Mutual Information Divergence (MID)**  
  基于互信息的生成质量评估。  
  [论文](https://openreview.net/forum?id=wKd2XtSRsjl) [代码](https://github.com/naver-ai/mid.metric)

* **PickScore**  
  一种用于生成任务的新评估方法。  
  [论文](https://arxiv.org/abs/2305.01569) [代码](https://huggingface.co/yuvalkirstain/PickScore_v1)

* **HPS v2**  
  一种新的基于对比学习的图像评估指标。  
  [论文](https://arxiv.org/abs/2306.09341) [代码](https://github.com/tgxs002/HPSv2)
