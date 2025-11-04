# Awesome Visual Generation Foundations

## Overview

This *awesome list* curates high-quality resources on visual generation (with a strong focus on diffusion), especially **task-agnostic fundamentals** and core principles.

**Inclusion priorities**
- **Peer-reviewed** papers from top conferences/journals.
- Works with **high community traction** (broad citations, active re-implementations, thorough comparisons, lively discussions).

**Maintenance**
- We aim for **daily updates**.

If you find this useful, please **⭐ star the repo**.  
Suggestions are welcome—open an Issue or submit a PR with vetted, high-signal resources.

## Advanced Technical Report

✨**Video models are zero-shot learners and reasoners** \
Thaddäus Wiedemer, Yuxuan Li, Paul Vicol, Shixiang Shane Gu, Nick Matarese, Kevin Swersky, Been Kim, Priyank Jaini, Robert Geirhos. [arXiv 2509.20328](https://arxiv.org/abs/2509.20328),  **\[Veo 3\]**

## Visual Tokenizer
✨**Latent Diffusion Model without Variational Autoencoder** \
Minglei Shi, Haolin Wang, Wenzhao Zheng, Ziyang Yuan, Xiaoshi Wu, Xintao Wang, Pengfei Wan, Jie Zhou, Jiwen Lu. [arXiv 2510.15301](https://arxiv.org/abs/2510.15301)

✨**Diffusion Transformers with Representation Autoencoders** \
Boyang Zheng, Nanye Ma, Shengbang Tong, Saining Xie. [arXiv 2510.11690](https://arxiv.org/abs/2510.11690v1)

✨**Representation Entanglement for Generation: Training Diffusion Transformers Is Much Easier Than You Think** \
Ge Wu, Shen Zhang, Ruijing Shi, Shanghua Gao, Zhenyuan Chen, Lei Wang, Zhaowei Chen, Hongcheng Gao, Yao Tang, Jian Yang, Ming-Ming Cheng, Xiang Li. [NeurIPS 2025](https://arxiv.org/abs/2507.01467)

✨**REPA-E: Unlocking VAE for End-to-End Tuning with Latent Diffusion Transformers** \
Xingjian Leng, Jaskirat Singh, Yunzhong Hou, Zhenchang Xing, Saining Xie, Liang Zheng. [ICCV 2025](https://arxiv.org/abs/2504.10483)

🔥**Reconstruction vs. Generation: Taming Optimization Dilemma in Latent Diffusion Models** \
Jingfeng Yao, Bin Yang, Xinggang Wang.  [CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Yao_Reconstruction_vs._Generation_Taming_Optimization_Dilemma_in_Latent_Diffusion_Models_CVPR_2025_paper.pdf),  **\[VA-VAE\]**

🔥**Representation Alignment for Generation: Training Diffusion Transformers Is Easier Than You Think** \
Sihyun Yu, Sangkyung Kwak, Huiwon Jang, Jongheon Jeong, Jonathan Huang, Jinwoo Shin, Saining Xie. [ICLR 2025](https://arxiv.org/abs/2410.06940), **\[REPA\]**

## Sampling Temperature

✨**Mitigating the Noise Shift for Denoising Generative Models via Noise Awareness Guidance** \
Jincheng Zhong, Boyuan Jiang, Xin Tao, Pengfei Wan, Kun Gai, Mingsheng Long. [arXiv 2510.12497](https://arxiv.org/abs/2510.12497)

**Feedback Guidance of Diffusion Models** \
Felix Koulischer, Florian Handke, Johannes Deleu, Thomas Demeester, Luca Ambrogioni. [NeurIPS 2025](https://openreview.net/forum?id=8ySOcf7UpM)

**Visual Generation Without Guidance** \
Huayu Chen, Kai Jiang, Kaiwen Zheng, Jianfei Chen, Hang Su, Jun Zhu. [ICML 2025](https://openreview.net/forum?id=gM6aboVgTO)

**Domain Guidance: A Simple Transfer Approach for Pre-trained Diffusion Models**\
Jincheng Zhong, XiangCheng Zhang, Jianmin Wang, Mingsheng Long. [ICLR 2025](https://openreview.net/forum?id=PplM2kDrl3)

**Dynamic Negative Guidance of Diffusion Models** \
Felix Koulischer, Johannes Deleu, Gabriel Raya, Thomas Demeester, Luca Ambrogioni. [ICLR 2025](https://openreview.net/forum?id=6p74UyAdLa)

🔥**Guiding a Diffusion Model with a Bad Version of Itself**\
Tero Karras, Miika Aittala, Tuomas Kynkäänniemi, Jaakko Lehtinen, Timo Aila, Samuli Laine. [NeurIPS 2024](https://openreview.net/forum?id=bg6fVPVs3s)



## Fast Generation
✨**Scalable GANs with Transformers** \
Sangeek Hyun, MinKyu Lee, Jae-Pil Heo. [arXiv 2509.24935](https://arxiv.org/abs/2509.24935)

🔥**Mean Flows for One-step Generative Modeling** \
Zhengyang Geng, Mingyang Deng, Xingjian Bai, J. Zico Kolter, Kaiming He. [NeurIPS 2025](https://arxiv.org/abs/2505.13447)

🔥**Simplifying, Stabilizing and Scaling Continuous-Time Consistency Models**\
Cheng Lu, and Yang Song. [ICLR 2025](https://arxiv.org/abs/2410.11081)

🔥**One Step Diffusion via Shortcut Models**\
Kevin Frans, Danijar Hafner, Sergey Levine, Pieter Abbeel. [ICLR 2025](https://openreview.net/forum?id=OlzB6LnXcS)

## Inference Time Scaling

**Inference-Time Scaling for Flow Models via Stochastic Generation and Rollover Budget Forcing** \
Jaihoon Kim, TaeHoon Yoon, Jisung Hwang, Minhyuk Sung. [NeurIPS 2025](https://openreview.net/forum?id=quY3zRPalR)

**Scaling Inference Time Compute for Diffusion Models** \
Nanye Ma, Shangyuan Tong, Haolin Jia, Hexiang Hu, Yu-Chuan Su, Mingda Zhang, Xuan Yang, Yandong Li, Tommi Jaakkola, Xuhui Jia, Saining Xie. [CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Ma_Scaling_Inference_Time_Compute_for_Diffusion_Models_CVPR_2025_paper.pdf)

## Post Training

✨**DiffusionNFT: Online Diffusion Reinforcement with Forward Process** \
Kaiwen Zheng, Huayu Chen, Haotian Ye, Haoxiang Wang, Qinsheng Zhang, Kai Jiang, Hang Su, Stefano Ermon, Jun Zhu, Ming-Yu Liu. [arXiv 2509.16117](https://arxiv.org/abs/2509.16117)

**Flow-GRPO: Training Flow Matching Models via Online RL** \
Jie Liu, Gongye Liu, Jiajun Liang, Yangguang Li, Jiaheng Liu, Xintao Wang, Pengfei Wan, Di Zhang, Wanli Ouyang. [NeurIPS 2025](https://arxiv.org/abs/2505.05470)

**Direct Discriminative Optimization: Your Likelihood-Based Visual Generative Model is Secretly a GAN Discriminator** \
Kaiwen Zheng, Yongxin Chen, Huayu Chen, Guande He, Ming-Yu Liu, Jun Zhu, Qinsheng Zhang. [ICML 2025](https://openreview.net/forum?id=OJ6WE7F8tK)

**Diffusion Tuning: Transferring Diffusion Models via Chain of Forgetting** \
Jincheng Zhong, Xingzhuo Guo, Jiaxiang Dong, Mingsheng Long. [NeurIPS 2024](https://openreview.net/forum?id=S98OzJD3jn)

## Training Tricks

**On the Importance of Noise Scheduling for Diffusion Models** \
Ting Chen. [arXiv 2301.10972](https://arxiv.org/abs/2301.10972)

## Miscellaneous

**On the Closed-Form of Flow Matching: Generalization Does Not Arise from Target Stochasticity** \
Quentin Bertrand, Anne Gagneux, Mathurin Massias, Rémi Emonet. [NeurIPS 2025](https://openreview.net/forum?id=kVz9uvqUna)

**Scaling Diffusion Transformers Efficiently via $\mu$P** \
Chenyu Zheng, Xinyu Zhang, Rongzhen Wang, Wei Huang, Zhi Tian, Weilin Huang, Jun Zhu, Chongxuan Li. [NeurIPS 2025](https://openreview.net/forum?id=VfIOdGiBAv)

**REPA Works Until It Doesn’t: Early-Stopped, Holistic Alignment Supercharges Diffusion Training** \
Ziqiao Wang, Wangbo Zhao, Yuhao Zhou, Zekai Li, Zhiyuan Liang, Mingjia Shi, Xuanlei Zhao, Pengfei Zhou, Kaipeng Zhang, Zhangyang Wang, Kai Wang, Yang You. [NeurIPS 2025](https://openreview.net/forum?id=HK96GI5s7G)

**Is Noise Conditioning Necessary for Denoising Generative Models?** \
Qiao Sun, Zhicheng Jiang, Hanhong Zhao, Kaiming He. [ICML 2025](https://openreview.net/pdf?id=pTSWi6RTtJ)
