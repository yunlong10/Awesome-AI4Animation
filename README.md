# Awesome Research on AI for Animation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository includes research, datasets, and other resources on AI for cel / cel-look / illust-look animation.

<img src="assets/teaser.png">

## Table of Contents
- [Awesome Research on AI for Animation](#awesome-research-on-ai-for-animation)
  - [Table of Contents](#table-of-contents)
  - [Process of Animation Production](#process-of-animation-production)
  - [Methods](#methods)
    - [Storyboarding](#storyboarding)
    - [Layout](#layout)
    - [Genga](#genga)
    - [Inbetweening](#inbetweening)
    - [Colorization](#colorization)
    - [Editing](#editing)
    - [After Record (AR)](#after-record-ar)
    - [Dubbing (DB)](#dubbing-db)
  - [Datasets](#datasets)
  - [Others](#others)
  - [Related Repository](#related-repository)


## Process of Animation Production
This is the production process of traditional 2D animation. We will list these research topics roughly in this sequence.
<img src="assets/pipeline.png">
<img src="assets/production.png">

## Methods

### Storyboarding

**Storyboarder.ai**\
[[Website]](https://www.storyboarder.ai/)

**CogCartoon: Towards Practical Story Visualization**\
*Zhongyang Zhu, Jie Tang*\
[[Paper]](https://arxiv.org/abs/2312.10718)

### Layout

### Genga


### Inbetweening

**ToonCrafter: Generative Cartoon Interpolation** [arXiv 2024]\
*Jinbo Xing, Hanyuan Liu, Menghan Xia, Yong Zhang, Xintao Wang, Ying Shan, Tien-Tsin Wong*\
[[Paper]](https://arxiv.org/abs/2405.17933)
[[Code]](https://github.com/ToonCrafter/ToonCrafter)
[[Project]](https://doubiiu.github.io/projects/ToonCrafter/)
<table>
    <tr>
        <td><img src="assets/72109_125.mp4_00-00.png"></td>
        <td><img src="assets/72109_125.mp4_00-01.png"></td>
        <td><img src="assets/00.gif"></td>
    </tr>
    <tr>
        <td><img src="assets/04.gif"></td>
        <td><img src="assets/frame0001_05.png"></td>
        <td><img src="assets/05.gif"></td>
    </tr>
</table>



**Joint Stroke Tracing and Correspondence for 2D Animation** [SIGGRAPH 2024]\
*Haoran Mo, Chengying Gao, Ruomei Wang*\
[[Paper]](https://dl.acm.org/doi/10.1145/3649890)
[[Project]](https://markmohr.github.io/JoSTC/)
[[Code]](https://github.com/MarkMoHR/JoSTC)

**Deep Geometrized Cartoon Line Inbetweening** [ICCV 2023]\
*Li Siyao, Tianpei Gu, Weiye Xiao, Henghui Ding, Ziwei Liu, Chen Change Loy*\
[[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Siyao_Deep_Geometrized_Cartoon_Line_Inbetweening_ICCV_2023_paper.pdf)
[[Demo]](https://www.youtube.com/watch?v=iUF-LsqFKpI&feature=youtu.be)
[[Code]](https://github.com/lisiyao21/AnimeInbet)
[[Dataset]](https://drive.google.com/file/d/1SNRGajIECxNwRp6ZJ0IlY7AEl2mRm2DR/view)

**Exploring Inbetween Charts with Trajectory-Guided Sliders for Cutout Animation** [MTA 2023]\
*T Fukusato, A Maejima, T Igarashi, T Yotsukura*\
[[Paper]](https://link.springer.com/article/10.1007/s11042-023-17354-x)

**Enhanced Deep Animation Video Interpolation** [arXiv 2022]\
*Wang Shen, Cheng Ming, Wenbo Bao, Guangtao Zhai, Li Chen, Zhiyong Gao*\
[[Paper]](https://arxiv.org/abs/2206.12657)

**Improving the Perceptual Quality of 2D Animation Interpolation** [arXiv 2021]\
*Shuhong Chen, Matthias Zwicker*\
[[Paper]](https://arxiv.org/abs/2111.12792)

**Deep Animation Video Interpolation in the Wild** [arXiv 2021]\
*Li Siyao, Shiyu Zhao, Weijiang Yu, Wenxiu Sun, Dimitris N. Metaxas, Chen Change Loy, Ziwei Liu*\
[[Paper]](https://arxiv.org/abs/2104.02495)
[[Code]](https://github.com/lisiyao21/AnimeInterp/)
[[Dataset]](https://github.com/lisiyao21/AnimeInterp/)

**Deep Sketch-Guided Cartoon Video Inbetweening** [arXiv 2020]\
*Xiaoyu Li, Bo Zhang, Jing Liao, Pedro V. Sander*\
[[Paper]](https://arxiv.org/abs/2008.04149)

**Optical Flow Based Line Drawing Frame Interpolation Using Distance Transform to Support Inbetweenings** [IEEE 2019]\
*Rei Narita, Keigo Hirakawa, Kiyoharu Aizawa*\
[[Paper]](https://ieeexplore.ieee.org/document/8803506)

**DiLight: Digital Light Table – Inbetweening for 2D Animations Using Guidelines** [Elsevier 2017]\
*Leonardo Carvalho, Ricardo Marroquim, Emilio Vital Brazil*\
[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0097849317300390)

### Colorization
**Learning Inclusion Matching for Animation Paint Bucket Colorization** [CVPR 2024]\
*Yuekun Dai, Shangchen Zhou, Qinyue Li, Chongyi Li, Chen Change Loy*\
[[Paper]](https://arxiv.org/abs/2403.18342)
[[Project]](https://ykdai.github.io/projects/InclusionMatching)
[[Demo]](https://www.youtube.com/watch?v=nNnPUItGvSo&ab_channel=YuekunDai)
[[Code]](https://github.com/ykdai/BasicPBC)
[[Dataset]](https://github.com/ykdai/BasicPBC/tree/main/dataset)\
<img src="assets/paintbucket-charactor.png">

**AniDoc: Animation Creation Made Easier** [Arxiv 2024]\
*Yihao Meng, Hao Ouyang, Hanlin Wang, Qiuyu Wang, Wen Wang, Ka Leong Cheng, Zhiheng Liu, Yujun Shen, Huamin Qu*\
[[Paper]](https://arxiv.org/pdf/2412.14173)
[[Project]](https://yihao-meng.github.io/AniDoc_demo/)
[[Code]](https://github.com/yihao-meng/AniDoc)

**ToonCrafter: Generative Cartoon Interpolation** [TOG 2024]\
*Jinbo Xing, Hanyuan Liu, Menghan Xia, Yong Zhang, Xintao Wang, Ying Shan, Tien-Tsin Wong*\
[[Paper]](https://arxiv.org/abs/2405.17933)
[[Project]](https://doubiiu.github.io/projects/ToonCrafter/)
[[Code]](https://github.com/Doubiiu/ToonCrafter)

**VToonify: Controllable High-Resolution Portrait Video Style Transfer** [TOG 2024]\
*Shuai Yang, Liming Jiang, Ziwei Liu, Chen Change Loy*\
[[Paper]](https://arxiv.org/abs/2209.11224)
[[Project]](https://www.mmlab-ntu.com/project/vtoonify/)
[[Code]](https://github.com/williamyang1991/VToonify)

**Coloring Anime Line Art Videos with Transformation Region Enhancement Network** [Pattern Recognition 2023]\
*Ning Wang, Muyao Niu, Zhi Dou, Zhihui Wang, Zhiyong Wang, Zhaoyan Ming, Bin Liu, Haojie Li*\
[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0031320323002625)

**SketchBetween: Video-to-Video Synthesis for Sprite Animation via Sketches** [ECCV 2022]\
*Dagmar Lukka Loftsdóttir, Matthew Guzdial*\
[[Paper]](https://arxiv.org/abs/2209.00185)
[[Code]](https://github.com/ribombee/SketchBetween)

**Animation Line Art Colorization Based on Optical Flow Method** [SSNR 2022]\
*Yifeng Yu, Jiangbo Qian, Chong Wang, Yihong Dong, Baisong Liu*\
[[Paper]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4202289)

**The Animation Transformer: Visual Correspondence via Segment Matching** [arXiv 2021]\
*Evan Casey, Víctor Pérez, Zhuoru Li, Harry Teitelman, Nick Boyajian, Tim Pulver, Mike Manh, William Grisaitis*\
[[Paper]](https://arxiv.org/abs/2109.02614)
[[Demo]](https://cadmium.app/)

**Artist-Guided Semiautomatic Animation Colorization** [arXiv 2020]\
*Harrish Thasarathan, Mehran Ebrahimi*\
[[Paper]](https://arxiv.org/abs/2006.13717)

**Line Art Correlation Matching Feature Transfer Network for Automatic Animation Colorization** [arXiv 2020]\
*Zhang Qian, Wang Bo, Wen Wei, Li Hai, Liu Jun Hui*\
[[Paper]](https://arxiv.org/abs/2004.06718)

**Deep Line Art Video Colorization with a Few References** [arXiv 2020]\
*Min Shi, Jia-Qi Zhang, Shu-Yu Chen, Lin Gao, Yu-Kun Lai, Fang-Lue Zhang*\
[[Paper]](https://arxiv.org/abs/2003.10685)

**Automatic Temporally Coherent Video Colorization** [arXiv 2019]\
*Harrish Thasarathan, Kamyar Nazeri, Mehran Ebrahimi*\
[[Paper]](https://arxiv.org/abs/1904.09527)
[[Code]](https://github.com/Harry-Thasarathan/TCVC)


### Editing

**Re:Draw -- Context Aware Translation as a Controllable Method for Artistic Production** [TBA 2024]\
*Joao Liborio Cardoso, Francesco Banterle, Paolo Cignoni, Michael Wimmer*\
[[Paper]](https://arxiv.org/abs/2401.03499)

**Sprite-from-Sprite: Cartoon Animation Decomposition with Self-supervised Sprite Estimation** [ACM 2022]\
*Lvmin Zhang, Tien-Tsin Wong, Yuxin Liu*\
[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3550454.3555439)
[[Code]](https://lllyasviel.github.io/GitPageToonDecompose/)

**Toonsynth: Example-based Synthesis of Hand-Colored Cartoon Animations** [TOG 2018]\
*M Dvorožnák, W Li, VG Kim, D Sýkora*\
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3197517.3201326)

### After Record (AR)

### Dubbing (DB)


## Datasets

### Comprehension, Generation
**Sakuga-42M Dataset: Scaling Up Cartoon Research** [arXiv 2024]\
*Zhenglin Pan, Yu Zhu, Yuxuan Mu*\
[[Paper]](https://drive.google.com/file/d/1aeJqsBw92ebELEpP-oFBo-kcUpBzHm_E/view)
[[Dataset]](https://huggingface.co/datasets/aidenpan/s_clips-v1.0)\
<img src="assets/sakuga.png">

**Anisora: Exploring the frontiers of animation video generation in the sora era** \
*Yudong Jiang, Baohan Xu, Siqian Yang, Mingyu Yin, Jing Liu, Chao Xu, Siqi Wang, Yidi Wu, Bingwen Zhu, Xinwen Zhang, Xingyu Zheng, Jixuan Xu, Yue Zhang, Jinlong Hou, Huyang Sun*\
[[Paper]](https://arxiv.org/pdf/2412.10255)
[[Code]](https://github.com/bilibili/Index-anisora)

### Dubbing
**ANIM-400K: A Large-Scale Dataset for Automated End-To-End Dubbing of Video** [ICASSP 2024]\
*Kevin Cai, Chonghua Liu, David M. Chan*\
[[Paper]](https://arxiv.org/pdf/2401.05314)
[[Code]](https://github.com/davidmchan/Anim400K)
[[Dataset]](https://huggingface.co/datasets/davidchan/anim400k)

**V2C: Visual Voice Cloning** [[CVPR 2022]]\
*Qi Chen, Yuanqing Li, Yuankai Qi, Jiaqiu Zhou, Mingkui Tan, Qi Wu*\
[[Paper]](https://arxiv.org/abs/2111.12890)
[[Code]](https://github.com/chenqi008/V2C)

### Compositing, Photography
**DoveNet: Deep Image Harmonization via Domain Verification** [[CVPR 2020]]\
*Wenyan Cong, Jianfu Zhang, Li Niu, Liu Liu, Zhixin Ling, Weiyuan Li, Liqing Zhang*\
[[Paper]](https://arxiv.org/abs/1911.13239)
[[Code]](https://github.com/bcmi/Image-Harmonization-Dataset-iHarmony4)
[[Demo]](https://bcmi.sjtu.edu.cn/home/niuli/demo_image_composition/)
[[Dataset(Baidu Cloud(access code: kqz3))]](https://pan.baidu.com/s/1xEN0Xrv_MbuKT0ZqsipeEg)
[[Dataset(OneDrive)]](https://1drv.ms/f/s!AohNSvvkuxZmgTHOraRzo5-X3nMp?e=bQQKkR)

**SSH: A Self-Supervised Framework for Image Harmonization** [[ICCV 2021]]\
*Yifan Jiang, He Zhang, Jianming Zhang, Yilin Wang, Zhe Lin, Kalyan Sunkavalli, Simon Chen, Sohrab Amirghodsi, Sarah Kong, Zhangyang Wang*\
[[Paper]](https://arxiv.org/abs/2108.06805)
[[Code]](https://github.com/VITA-Group/SSHarmonization)
[[Dataset]](https://drive.google.com/file/d/1jBx-DBtRX8GaqMvMv-CZutK4jn9tz-fT/view)

**Intrinsic Image Harmonization** [[CVPR 2021]]\
*Zonghui Guo, Haiyong Zheng, Yufeng Jiang, Zhaorui Gu, Bing Zheng*\
[[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Guo_Intrinsic_Image_Harmonization_CVPR_2021_paper.pdf)
[[Code]](https://github.com/zhenglab/IntrinsicHarmony)
[[Dataset(Baidu Cloud(access code: akbi))]](https://pan.baidu.com/s/1DR600XJFhm8lqfHZ6mOU_A)
[[Dataset(Google Drive)]](https://drive.google.com/file/d/1-pa_9BNgIkuR0j1gcCxh8GI3XSWZN0e7/view?usp=sharing)

**Alchemist: Parametric Control of Material Properties with Diffusion Models** [CVPR 2024]\
*Prafull Sharma, Varun Jampani, Yuanzhen Li, Xuhui Jia, Dmitry Lagun, Fredo Durand, William T. Freeman, Mark Matthews*\
[[Paper]](https://arxiv.org/abs/2312.02970)
[[Project Page]](https://www.prafullsharma.net/alchemist/)

### Colorization
**Learning Inclusion Matching for Animation Paint Bucket Colorization** [CVPR 2024]\
*Yuekun Dai, Shangchen Zhou, Qinyue Li, Chongyi Li, Chen Change Loy*\
[[Paper]](https://arxiv.org/abs/2403.18342)
[[Project]](https://ykdai.github.io/projects/InclusionMatching)
[[Demo]](https://www.youtube.com/watch?v=nNnPUItGvSo&ab_channel=YuekunDai)
[[Code]](https://github.com/ykdai/BasicPBC)
[[Dataset]](https://github.com/ykdai/BasicPBC/tree/main/dataset)

### Inbetweening
**Deep Animation Video Interpolation in the Wild** [CVPR 2021]\
*Li Siyao, Shiyu Zhao, Weijiang Yu, Wenxiu Sun, Dimitris N. Metaxas, Chen Change Loy, Ziwei Liu*\
[[Paper]](https://arxiv.org/pdf/2104.02495)
[[Code]](https://github.com/lisiyao21/AnimeInterp/)
[[Data (Google Drive)]](https://drive.google.com/file/d/1XBDuiEgdd6c0S4OXLF4QvgSn_XNPwc-g/view) 
[[Data (OneDrive)]](https://entuedu-my.sharepoint.com/:u:/g/personal/siyao002_e_ntu_edu_sg/EY3SG0-IajxKj9HMPz__zOMBvyJdrA-SlwpyHYFkDsQtng?e=q7nGlu)
[[Video Demo]](https://www.youtube.com/watch?v=2bbujT-ZXr8)

**Deep Geometrized Cartoon Line Inbetweening** [ICCV 2023]\
*Li Siyao, Tianpei Gu, Weiye Xiao, Henghui Ding, Ziwei Liu, Chen Change Loy*\
[[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Siyao_Deep_Geometrized_Cartoon_Line_Inbetweening_ICCV_2023_paper.pdf)
[[Demo]](https://www.youtube.com/watch?v=iUF-LsqFKpI&feature=youtu.be)
[[Code]](https://github.com/lisiyao21/AnimeInbet)
[[Dataset]](https://drive.google.com/file/d/1SNRGajIECxNwRp6ZJ0IlY7AEl2mRm2DR/view)

**AnimeRun: 2D Animation Visual Correspondence from Open Source 3D Movies** [NeurIPS 2022]\
*Li Siyao, Yuhang Li, Bo Li, Chao Dong, Ziwei Liu, Chen Change Loy*\
[[Paper]](https://arxiv.org/abs/2211.05709)
[[Project & Dataset]](https://lisiyao21.github.io/projects/AnimeRun)
[[Code]](https://github.com/lisiyao21/AnimeRun)



## Others

**Globally Optimal Toon Tracking**\
*Haichao Zhu, Xueting Liu, Tien-Tsin Wong, Pheng-Ann Heng*\
[[Paper]](https://ttwong12.github.io/papers/toontrack/toontrack.pdf)
[[Supplementary]](https://ttwong12.github.io/papers/toontrack/supp.pdf)
[[Results Video]](https://ttwong12.github.io/papers/toontrack/result.mp4)
[[Project Page]](https://ttwong12.github.io/papers/toontrack/toontrack.html)

**Stereoscopizing Cel Animations**\
*Xueting Liu, Xiangyu Mao, Xuan Yang, Linling Zhang, Tien-Tsin Wong*\
[[Project Page]](https://ttwong12.github.io/papers/3dcel/3dcel.html)
[[Paper]](https://ttwong12.github.io/papers/3dcel/3dcel.pdf)

## Related Repository
