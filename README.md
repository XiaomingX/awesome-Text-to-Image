# 精选：文本到图像资源集合

本项目集合了与文本到图像生成和编辑相关的资源。

## 描述
最近几年，计算机视觉（CV）和自然语言处理（NLP）领域在深度学习方面取得了许多突破性进展，研究者们逐渐将语义信息与视觉信息相结合，进行文本到图像的合成研究，将输入的文本描述（关键词或句子）转化为真实图像。

### 文本到面部图像
* (ECCV 2024) **PreciseControl: 提升文本到图像扩散模型的细粒度属性控制**，作者：Rishubh Parihar等。[[论文](https://www.arxiv.org/abs/2408.05083)] [[项目](https://rishubhpar.github.io/PreciseControl.home/)]
* (CVPR 2024) **CosmicMan: 用于人物的文本到图像基础模型**，作者：Shikai Li等。[[论文](https://arxiv.org/abs/2404.01294)] [[项目](https://cosmicman-cvpr2024.github.io/)]
* (ICML 2024) **快速文本到3D面部生成及操控，通过跨模态映射和几何正则化**，作者：Jinlu Zhang等。[[论文](https://arxiv.org/abs/2403.06702)] [[代码](https://github.com/Aria-Zhangjl/E3-FaceNet)]
* (NeurIPS 2023) **在扩散模型中插入任何人**，作者：Ge Yuan等。[[论文](https://arxiv.org/abs/2306.00926)] [[项目](https://celeb-basis.github.io/)]

**2024**
- **Flow Generator Matching**，Zemin Huang等。[[论文](https://arxiv.org/abs/2410.19310)]
- **Kandinsky 3: 多功能生成框架的文本到图像合成**，Vladimir Arkhipkin等。[[论文](https://arxiv.org/abs/2410.21061)] [[代码](https://github.com/ai-forever/Kandinsky-3)] [[项目](https://ai-forever.github.io/Kandinsky-3/)]
- **Imagen 3** (⭐⭐)，ImagenTeam-Google [[论文](https://arxiv.org/abs/2408.07009)]
- **Ranni: 精准指令跟随的文本到图像扩散模型**，Yutong Feng等。[[论文](https://arxiv.org/abs/2311.17002)] [[项目](https://ranni-t2i.github.io/Ranni/)] [[代码](https://github.com/ali-vilab/Ranni)]
- **SDXL-Lightning: 渐进对抗扩散蒸馏** (⭐)，Shanchuan Lin等。[[论文](https://arxiv.org/abs/2402.13929)] [[HuggingFace](https://huggingface.co/ByteDance/SDXL-Lightning)] [[演示](https://fastsdxl.ai/)]

**2023**
- **CoDi-2: 任意生成的上下文交互模型**，Zineng Tang等。[[论文](https://arxiv.org/abs/2311.18775)] [[项目](https://codi-2.github.io/)] [[代码](https://github.com/microsoft/i-Code/tree/main/CoDi-2)]
- **Kandinsky: 改进的文本到图像合成** (⭐)，Anton Razzhigaev等。[[论文](https://arxiv.org/abs/2310.03502)] [[代码](https://github.com/ai-forever/Kandinsky-2)] [[演示](https://fusionbrain.ai/en/editor/)]
- **Pick-a-Pic: 用户偏好开放数据集** (⭐⭐)，Yuval Kirstain等。[[论文](https://arxiv.org/abs/2305.01569)] [[代码](https://github.com/yuvalkirstain/PickScore)] [[数据集](https://huggingface.co/datasets/yuvalkirstain/pickapic_v1)] [[应用](https://pickapic.io/)]
- **Visual ChatGPT: 视觉基础模型对话、绘图与编辑** (⭐⭐)，Chenfei Wu等。[[论文](https://arxiv.org/abs/2303.04671)] [[代码](https://github.com/microsoft/visual-chatgpt)]
- **AltCLIP: 扩展语言功能的文本到图像生成** (⭐⭐)，Zhongzhi Chen等。[[论文](https://arxiv.org/abs/2211.06679)] [[代码](https://github.com/FlagAI-Open/FlagAI/tree/master/examples/AltDiffusion-m18)]



## 6. 相关研究

### 📝提示工程
- **PromptCharm: 多模态提示优化的文本到图像生成** (CHI 2024) [[论文](https://arxiv.org/abs/2403.04014)]
- **自动化黑盒提示工程用于个性化文本到图像生成** (arXiv 2024) [[论文](https://arxiv.org/abs/2403.191039)]
- **自动提示工程用于文本到图像合成** (EMNLP 2023) [[论文](https://arxiv.org/abs/2311.06752)]
- **NeuroPrompts: 提示优化的自适应框架** (arXiv 2023) [[论文](https://arxiv.org/abs/2311.12229)] [[视频](https://www.youtube.com/watch?v=Cmca_RWYn2g)]
  
### ⭐多模态生成
- **4M-21: 任意到任意的视觉模型** (arXiv 2024) [[论文](https://arxiv.org/abs/2406.09406)] [[项目](https://4m.epfl.ch/)]
  - 支持文本到图像、深度图、语义分割等多任务
- **Ctrl-X: 结构和外观控制的文本到图像生成** (arXiv 2024) [[论文](https://arxiv.org/abs/2406.07540)] [[项目](https://genforce.github.io/ctrl-x/)]
- **CoDi: 通过可组合扩散实现任意到任意生成** (NeurIPS 2023) [[论文](https://arxiv.org/abs/2305.11846)] [[项目](https://codi-gen.github.io/)]
  - 支持文本、图像、音频之间的互相转换与组合生成
- **ImageBind: 跨六种模态的嵌入空间** (CVPR 2023) [[论文](https://arxiv.org/abs/2305.05665)] [[项目](https://ai.facebook.com/blog/imagebind-six-modalities-binding-ai/)]


### 主要应用领域

- **多概念组合**: [Gen4Gen: 生成数据管道用于多概念组合生成](https://arxiv.org/abs/2402.15504)，Chun-Hsiao Yeh 等。
- **3D 发型生成**: [HAAR: 基于文本的 3D 发型生成模型](https://arxiv.org/abs/2312.11666)，Vanessa Sklyarova 等。
- **图像超分辨率**: [基于文本提示的超分辨率](https://arxiv.org/abs/2311.14282)，Zheng Chen 等。
- **图像编辑**: [生成填充](https://www.adobe.com/products/photoshop/generative-fill.html)。
- **大语言模型 (LLM)**: [LaDi: 利用 LLMs 改善文本生成](https://arxiv.org/abs/2311.03716v1)，Allen Roush 等。
- **分割模型**: [SegGen: 通过文本与图像生成增强分割](https://arxiv.org/abs/2311.03355)，Hanrong Ye 等。
- **文本编辑**: [DiffUTE: 通用文本编辑扩散模型](https://arxiv.org/abs/2305.10825)，Haoxing Chen 等。
- **文本角色生成**: [TextDiffuser: 文本绘制扩散模型](https://arxiv.org/abs/2305.10855)，Jingye Chen 等。
- **开放词汇全景分割**: [基于文本生成模型的全景分割](https://arxiv.org/abs/2303.04803)，Jiarui Xu 等。
- **中文字符生成**: [GlyphDraw: 学习绘制中文字符](https://arxiv.org/abs/2303.17870)，Jian Ma 等。

### 文本+图像/视频 → 图像/视频

- **风格迁移**: [StyleShot: 快速风格捕捉](https://arxiv.org/abs/2407.01414)，Junyao Gao 等。
- **复杂图像编辑**: [SmartEdit: 基于多模态大语言模型的复杂图像编辑](https://arxiv.org/abs/2312.06739)，Yuzhou Huang 等。
- **高保真图像个性化**: [MM-Diff](https://arxiv.org/abs/2403.15059)，Zhichao Wei 等。
- **文本驱动的三维对象插入**: [InseRF](https://arxiv.org/abs/2401.05335)，Mohamad Shahbazi 等。

### 文本+布局 → 图像

- **零样本布局控制**: [Zero-Painter: 文本到图像的布局控制](https://arxiv.org/abs/2406.04032)，Marianna Ohanyan 等。
- **多实例生成控制器**: [MIGC](https://arxiv.org/abs/2402.05408)，Dewei Zhou 等。
- **生成对抗监督**: [Adversarial Supervision Makes Layout-to-Image Diffusion Models Thrive](https://arxiv.org/abs/2401.08815)，Yumeng Li 等。

### 其他

- **视频编辑**: [MagicStick: 基于控制手柄变换的视频编辑](https://arxiv.org/abs/2312.03047v1)，Yue Ma 等。
- **图像合成和编辑**: [MasaCtrl: 一致性图像合成和编辑](https://arxiv.org/abs/2304.08465)，Mingdeng Cao 等。

**文本+图像/视频 → 图像/视频**
- (arXiv 2024) **ECNet: 高效可控文本生成图像扩散模型**，Sicheng Li 等。[[论文](https://arxiv.org/abs/2403.18417)]
- (ICCV 2023) **HumanSD: 基于骨架的人像生成扩散模型**，Xuan Ju 等。[[论文](https://arxiv.org/abs/2304.04269)] [[项目](https://idea-research.github.io/HumanSD/)] [[代码](https://github.com/IDEA-Research/HumanSD)] [[视频](https://drive.google.com/file/d/1Djc2uJS5fmKnKeBnL34FnAAm3YSH20Bb/view)]
- (arXiv 2023) **机器人共感: 声音与情感引导的AI绘画**，Vihaan Misra 等。[[论文](https://arxiv.org/abs/2302.04850)]

**布局/遮罩 → 图像**
- (CVPR 2024) **InstanceDiffusion: 实例级别图像生成控制**，XuDong Wang 等。[[论文](https://arxiv.org/abs/2402.03290)] [[项目](https://people.eecs.berkeley.edu/~xdwang/projects/InstDiff/)] [[代码](https://github.com/frank-xwang/InstanceDiffusion)]
- (CVPR 2023) **自由布局到图像合成**，Han Xue 等。[[论文](https://arxiv.org/abs/2303.14412)] [[代码](https://github.com/essunny310/FreestyleNet)]
- (CVPR 2023) **LayoutDiffusion: 可控扩散模型生成布局到图像**，Guangcong Zheng 等。[[论文](https://arxiv.org/abs/2303.17189)] [[代码](https://github.com/ZGCTroy/LayoutDiffusion)]

**语音 → 图像**
- (IEEE/ACM TASLP 2021) **从语音描述生成图像**，Xinsheng Wang 等。[[论文](https://dl.acm.org/doi/10.1109/TASLP.2021.3053391)] [[代码](https://github.com/xinshengwang/S2IGAN)] [[项目](https://xinshengwang.github.io/project/s2igan/)]
- (IEEE JSTSP 2020) **直接语音到图像转换**，Jiguo Li 等。[[论文](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9067083)] [[代码](https://github.com/smallflyingpig/speech-to-image-translation-without-text)] [[项目](https://smallflyingpig.github.io/speech-to-image/main)]

**场景图 → 图像**
- (arXiv 2023) **基于扩散的场景图生成图像**，Ling Yang 等。[[论文](https://arxiv.org/abs/2211.11138)]
- (CVPR 2018) **场景图到图像生成**，Justin Johnson 等。[[论文](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0764.pdf)] [[代码](https://github.com/google/sg2im)]

**文本 → 3D/动画/形状/网格等**
- (arXiv 2024) **CrowdMoGen: 零样本文本驱动集体动作生成**，Xinying Guo 等。[[论文](https://arxiv.org/abs/2407.06188)] [[项目](https://gxyes.github.io/projects/CrowdMoGen.html)]
- (ACMMM 2024) **PlacidDreamer: 文本生成3D**，Shuo Huang 等。[[论文](https://arxiv.org/abs/2407.13976)] [[代码](https://github.com/HansenHuang0823/PlacidDreamer)]
- (arXiv 2023) **4D-fy: 文本生成4D**，Sherwin Bahmani 等。[[论文](https://arxiv.org/abs/2311.17984)] [[项目](https://sherwinbahmani.github.io/4dfy/)] [[代码](https://github.com/sherwinbahmani/4dfy)]

**文本 → 视频生成相关工作**：

1. **VideoTetris: 组合文本到视频生成**（arXiv 2024）  
   [论文](https://arxiv.org/abs/2406.04277) | [项目](https://videotetris.github.io/) | [代码](https://github.com/YangLing0818/VideoTetris)

2. **MovieDreamer: 分层生成长时间视觉序列**（arXiv 2024）  
   [论文](https://arxiv.org/abs/2407.16655) | [项目](https://aim-uofa.github.io/MovieDreamer/) | [代码](https://github.com/aim-uofa/MovieDreamer) | [演示视频](https://www.youtube.com/watch?v=aubRVOGrKLU)

3. **Sora**（OpenAI 2024）  
   [主页](https://openai.com/sora) | [技术报告](https://openai.com/research/video-generation-models-as-world-simulators) | [带音频版本](https://x.com/elevenlabsio/status/1759240084342059260?s=20)

4. **ControlVideo: 无需训练的可控文本到视频生成**（ICLR 2024）  
   [论文](https://arxiv.org/abs/2305.13077) | [代码](https://github.com/YBYBZhang/ControlVideo)

5. **MagicVideo-V2: 多阶段高美感视频生成**（arXiv 2024）  
   [论文](https://arxiv.org/abs/2401.04468) | [项目](https://magicvideov2.github.io/)

6. **LAVIE: 高质量视频生成（级联潜在扩散模型）**（arXiv 2023）  
   [论文](https://arxiv.org/abs/2309.15103) | [项目](https://vchitect.github.io/LaVie-project/) | [代码](https://github.com/Vchitect/LaVie)

7. **Emu Video: 显式图像条件化文本到视频生成**（arXiv 2023）  
   [论文](https://arxiv.org/abs/2311.10709) | [项目](https://emu-video.metademolab.com/)

8. **Text2Video-Zero: 文本到图像扩散模型用于零样本视频生成**（ICCV 2023）  
   [论文](https://arxiv.org/abs/2303.13439) | [项目](https://text2video-zero.github.io/) | [视频](https://www.dropbox.com/s/uv90mi2z598olsq/Text2Video-Zero.MP4?dl=0) | [代码](https://github.com/Picsart-AI-Research/Text2Video-Zero)

9. **FETV: 开放领域文本到视频生成的细粒度评估基准**（NeurIPS 2023）  
   [论文](https://arxiv.org/abs/2311.01813v1) | [项目](https://github.com/llyx97/FETV)
