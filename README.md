# Awesome Concealed Object Segmentation

A curated list of awesome **Concealed Object Segmentation** (COS) works. 

We will keep updating it.

**Last updated at 2024/01/19.**

---

## Contributing

Please feel free to send us pull requests or email us(issja_hu@163.com) to add links.

## Contents

* [Papers](#Papers)
  * [Camouflaged Object Detection(COD)](#p_COD)
    * [Normal](#p_Normal)
    * [Video(VCOD)](#p_Video)
    * [Reference-Based](#p_Referring)
    * [Open-Vocabulary](#p_Open-Vocabulary)
  * [Transparent Object Segmentation(TOS)](#p_TOS)
  * [Surface Defect Detection(SDD)](#p_SDD)
  * [Polyp Segmentation(PS)](#p_PS)
  * [Lung Nodule Detection(LND)](#p_LND)
* [Datasets](#Datasets)
  * [COD](#d_COD)
  * [TOS](#d_TOS)
  * [SDD](#d_SDD)
  * [PS](#d_PS)
  * [LND](#d_LND)

* [Latest Works Recommended](#Recommended)
* [Reference](#Reference)

## <span id = "Papers">Papers</span>

### <span id = "p_COD">1. Camouflaged Object Detection(COD)</span>

#### <span id = "p_Normal">1.1 Normal</span>

|  when   |            what             | title                                                        |         pub.          |                             link                             |
| :-----: | :-------------------------: | ------------------------------------------------------------ | :-------------------: | :----------------------------------------------------------: |
| 2023/08 |          **PENet**          | Locate, Refine and Restore: A Progressive Enhancement Network for Camouflaged Object Detection<br/><sup><sub>*Xiaofei Li; Jiaxin Yang; Shuohao Li; Jun Lei; Jun Zhang; Dong Chen*</sub></sup> |    IJCAI<br />2023    |   [Paper](https://www.ijcai.org/proceedings/2023/0124.pdf)   |
| 2023/08 | **Camouflageator and ICEG** | Strategic Preys Make Acute Predators: Enhancing Camouflaged Object Detectors by Generating Camouflaged Objects<br/><sup><sub>*Chunming He, Kai Li, Yachao Zhang, Yulun Zhang, Zhenhua Guo, Xiu Li, Martin Danelljan, Fisher Yu*</sub></sup> |    ICLR<br />2024     | [Paper](https://arxiv.org/abs/2308.03166)/[Code](https://github.com/ChunmingHe/Camouflageator) |
| 2023/04 |         **FLCNet**          | Camouflaged Object Detection with a Feature Lateral Connection Network <br> <sup><sub>*Tao Wang, Jian Wang, and Ruihao Wang*</sub></sup> | Electronics<br />2023 | [Paper](https://www.mdpi.com/2079-9292/12/12/2570)/[Code](https://github.com/Tao-Wang-CV/FLCNet) |
| 2023/02 |         **FSPNet**          | Feature Shrinkage Pyramid for Camouflaged Object Detection with Transformers<br/><sup><sub>*Zhou Huang, Hang Dai, Tian-Zhu Xiang, Shuo Wang, Huai-Xin Chen, Jie Qin, and Huan Xiong*</sub></sup> |    CVPR<br />2023     | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Feature_Shrinkage_Pyramid_for_Camouflaged_Object_Detection_With_Transformers_CVPR_2023_paper.pdf)/[Code](https://github.com/ZhouHuang23/FSPNet) |
| 2023/02 |          **FEDER**          | Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction<br/><sup><sub>*Chunming He, Kai Li, Yachao Zhang, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup> |    CVPR<br />2023     | [ Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/He_Camouflaged_Object_Detection_With_Feature_Decomposition_and_Edge_Reconstruction_CVPR_2023_paper.pdf)/[Code](https://github.com/ChunmingHe/FEDER) |
|  2023   |         **PFNet+**          | Distraction-aware camouflaged object segmentation<br/><sup><sub>*Haiyang Mei, Xin Yang, Yunduo Zhou, Ge-Peng Ji, Xiaopeng Wei, and Deng-Ping Fan*</sub></sup> |     SSI<br />2023     | [Paper]/[Code](https://github.com/Mhaiyang/PFNet_Plus)/[Project](https://mhaiyang.github.io/SSI2023-PFNet-Plus/index.html) |
| 2022/12 |       **Camoformer**        | Camoformer: Masked separable attention for camouflaged object detection <br><sup><sub>*Bowen Yin, Xuying Zhang, Qibin Hou, Bo-Yuan Sun, Deng-Ping Fan, and Luc Van Gool*</sub></sup> |         arXiv         | [Paper](https://arxiv.org/abs/2212.06570)/[Code](https://github.com/HVision-NKU/CamoFormer) |
| 2022/12 |         **PopNet**          | Source-free depth for object pop-out <br><sup><sub>*Zongwei Wu, Danda Pani Paudel, Deng-Ping Fan, Jingjing Wang, Shuo Wang, Cédric Demonceaux, Radu Timofte, Luc Van Gool*</sub></sup> |    ICCV<br />2023     | [Paper](https://arxiv.org/abs/2212.05370)/[Code](https://github.com/Zongwei97/PopNet) |
| 2022/12 |         **AGFNet**          | AGFNet: Attention Guided Fusion Network for Camouflaged Object Detection <br><sup><sub>*Zeyu Zhao, Zhihao Liu & Chenglei Peng*</sub></sup> |    CICAI<br />2022    | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-20497-5_39) |
| 2022/11 |         **FAP-Net**         | Feature Aggregation and Propagation Network for Camouflaged Object Detection <br><sup><sub>*Tao Zhou, Yi Zhou, Chen Gong, Jian Yang, Yu Zhang*</sub></sup> |     TIP<br />2022     | [Paper](https://ieeexplore.ieee.org/document/9940173/authors#authors)/[Code](https://github.com/taozh2017/FAPNet) |
| 2022/11 |         **DPS-Net**         | Global-Local Aggregation with Deformable Point Sampling for Camouflaged Object Detection <br><sup><sub>*Lee, Minhyeok, Suhwan Cho, Chaewon Park, Dogyoon Lee, Jungho Lee, and Sangyoun Lee*</sub></sup> |         arXiv         |          [Paper](https://arxiv.org/abs/2211.12048)           |
| 2022/10 |          **MFFN**           | MFFN: Multi-view Feature Fusion Network for Camouflaged Object Detection <br><sup><sub>*Dehua Zheng, Xiaochen Zheng, Laurence T. Yang, Yuan Gao, Chenlu Zhu, Yiheng Ruan*</sub></sup> |    WACV<br />2023     | [Paper](https://arxiv.org/abs/2210.06361)/[Code](https://github.com/dwardzheng/MFFN_COD) |
| 2022/10 |         **PreyNet**         | PreyNet: Preying on camouflaged objects <br> <sup><sub>*M Zhang, S Xu, Yongri Piao, D Shi, S Lin, H Lu*</sub></sup> |   ACM MM<br />2022    | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548178)/[Code](https://github.com/sxu1997/PreyNet) |
| 2022/07 |              -              | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations <br><sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup> |    AAAI<br />2023     | [Paper](https://arxiv.org/abs/2207.14083)/[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations) |
| 2022/07 |         **BASNet**          | Boundary-Guided Camouflaged Object Detection <br> <sup><sub>*Yujia Sun, Shuo Wang, Chenglizhao Chen, Tian-Zhu Xiang*</sub></sup> |    IJCAI<br />2022    | [Paper](https://www.ijcai.org/proceedings/2022/186)/[Code](https://github.com/thograce/BGNet) |
| 2022/07 |         **C2F-Net**         | Camouflaged Object Detection via Context-aware Cross-level Fusion (`C2FNet Extension`)  <br> <sup><sub>*Geng Chen, Si-Jie Liu, Yu-Jia Sun, Ge-Peng Ji, Ya-Feng Wu, Tao Zhou*</sub></sup> |    TCSVT<br />2022    | [Paper](https://arxiv.org/abs/2207.13362)/[Code](https://github.com/Ben57882/C2FNet-TSCVT) |
| 2022/07 |         **DTC-Net**         | Deep Texton-Coherence Network for Camouflaged Object Detection <br> <sup><sub>*Wei Zhai, Yang Cao, HaiYong Xie, Zheng-Jun Zha*</sub></sup> |     TMM<br />2022     | [Paper](https://ieeexplore.ieee.org/abstract/document/9815160) |
| 2022/07 |          **BgNet**          | Boundary-guided network for camouflage object detection <br> <sup><sub>*Tianyou Chen, Jin Xiao, Xiaoguang Hu, Guofeng Zhang, Shaojie Wang*</sub></sup> |     KBS<br />2022     | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122004294)/[Code](https://github.com/clelouch/BgNet) |
| 2022/07 |         **CubeNet**         | CubeNet: X-shape connection for camouflaged object detection <br> <sup><sub>*Mingchen Zhuge, Xiankai Lu, Yiyou Guo, Zhihua Cai, Shuhan Chen*</sub></sup> |     PR<br />2022      | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S003132032200125X?dgcid=raven_sd_recommender_email)/[Code](https://github.com/mczhuge/CubeNet) |
| 2022/06 |              -              | Detecting Camouflaged Object in Frequency Domain <br> <sup><sub>*Yijie Zhong, Bo Li, Lv Tang, et al.*</sub></sup> |    CVPR<br />2022     | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Detecting_Camouflaged_Object_in_Frequency_Domain_CVPR_2022_paper.pdf) |
| 2022/06 |         **SegMaR**          | Segment, Magnify and Reiterate: Detecting Camouflaged Objects the Hard Way <br> <sup><sub>*Qi Jia, S. Yao, Yu Liu, et al.*</sub></sup> |    CVPR<br />2022     | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jia_Segment_Magnify_and_Reiterate_Detecting_Camouflaged_Objects_the_Hard_Way_CVPR_2022_paper.pdf)/[Code](https://github.com/dlut-dimt/SegMaR) |
| 2022/06 |          **CANet**          | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup> |    CVPR<br />2022     | [Paper](https://arxiv.org/abs/2203.02688)/[Code](https://github.com/lartpang/ZoomNet) |
| 2022/06 |          **FBNet**          | Frequency-aware Camouflaged Object Detection <br> <sup><sub>*Jiaying Lin, Xin Tan, Ke Xu, Lizhuang Ma, Rynson W.H. Lau*</sub></sup> |    TOMM<br />2022     |     [Paper](https://dl.acm.org/doi/abs/10.1145/3545609)      |
| 2022/05 |          **DGNet**          | Deep Gradient Learning for Efficient Camouflaged Object Detection <br><sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Yu-Cheng Chou, Dengxin Dai, Alexander Liniger, Luc Van Gool*</sub></sup> |     MIR<br />2023     | [Paper](https://arxiv.org/abs/2205.12853v2)/[Code](https://github.com/GewelsJI/DGNet) |
| 2022/05 |      **LSR extension**      | Towards Deeper Understanding of Camouflaged Object Detection <br> <sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, et al.*</sub></sup> |    TCSVT<br />2023    | [Paper](https://arxiv.org/abs/2205.11333)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) |
| 2022/03 |         **HitNet**          | High-resolution Iterative Feedback Network for Camouflaged Object Detection <br> <sup><sub>*Xiaobin Hu, Shuo Wang, Xuebin Qin, Hang Dai, Wenqi Ren, Donghao Luo, Ying Tai, Ling Shao*</sub></sup> |    AAAI<br />2023     | [Paper](https://arxiv.org/abs/2203.11624)/[Code](https://github.com/HUuxiaobin/HitNet) |
| 2022/01 |          **CANet**          | Modeling Aleatoric Uncertainty for Camouflaged Object Detection <br> <sup><sub>*Jiawei Liu, Jing Zhang, Nick Barnes*</sub></sup> |    WACV<br />2022     | [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Liu_Modeling_Aleatoric_Uncertainty_for_Camouflaged_Object_Detection_WACV_2022_paper.pdf)/[Code](https://github.com/Carlisle-Liu/OCENet) |
|  2022   |         **BSA-Net**         | I can find you! Boundary-guided Separated Attention Network for Camouflaged Object Detection <br><sup><sub>*Hongwei Zhu, Peng Li, Haoran Xie, Mingqiang Wei, et al.*</sub></sup> |    AAAI<br />2022     | [Paper](https://aaai.org/papers/03608-i-can-find-you-boundary-guided-separated-attention-network-for-camouflaged-object-detection/)/[Code](https://github.com/WolfberryCoke/BSA-Net) |
| 2021/11 |         **ERRNet**          | Fast Camouflaged Object Detection via Edge-based Reversible Re-calibration Network <br><sup><sub>*Ge-Peng Ji, Lei Zhu, Mingchen Zhuge, Keren Fu*</sub></sup> |     PR<br />2022      | [Paper](https://arxiv.org/abs/2111.03216)/[Code](https://github.com/GewelsJI/ERRNet) |
| 2021/11 |         **POCINet**         | Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection  <br><sup><sub>*Yi Liu, Dingwen Zhang, Qiang Zhang, and Jungong Han*</sub></sup> |    TIFS<br />2021     | [Paper](https://ieeexplore.ieee.org/document/9600863/)/[Code](https://github.com/liuyi1989/TSPORTNet) |
| 2021/11 |              -              | Rethinking Camouflaged Object Detection: Models and Datasets <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup> |    TCSVT<br />2021    |    [Paper](https://ieeexplore.ieee.org/document/9598866)     |
| 2020/07 |        **MirrorNet**        | MirrorNet: Bio-Inspired Camouflaged Object Segmentation <br><sup><sub>*Jinnan Yan, Trung-Nghia Le, Khanh-Duy Nguyen, Minh-Triet Tran, Thanh-Toan Do, Tam V. Nguyen*</sub></sup> |   Access<br />2021    | [Paper](https://arxiv.org/abs/2007.12881)/[Project](https://sites.google.com/view/ltnghia/research/camo) |
| 2021/06 |              -              | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection <br><sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Bowen Liu, Tong Zhang, Yuchao Dai*</sub></sup> |    CVPR<br />2021     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Uncertainty-Aware_Joint_Salient_Object_and_Camouflaged_Object_Detection_CVPR_2021_paper.html)/[Code](https://github.com/JingZhang617/Joint_COD_SOD) |
| 2021/06 |              -              | Simultaneously Localize, Segment and Rank the Camouflaged Objects (`NC4K dataset`)  <br><sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, et al.*</sub></sup> |    CVPR<br />2021     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) |
| 2021/06 |          **PFNet**          | Camouflaged Object Segmentation with Distraction Mining      <br><sup><sub>*Haiyang Mei, Ge-Peng Ji, Ziqi Wei, Xin Yang, Xiaopeng Wei, Deng-Ping Fan*</sub></sup> |    CVPR<br />2021     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Camouflaged_Object_Segmentation_With_Distraction_Mining_CVPR_2021_paper.pdf)/[Code](https://mhaiyang.github.io/CVPR2021_PFNet/index) |
| 2021/06 |           **MGL**           | Mutual Graph Learning for Camouflaged Object Detection       <br><sup><sub>*Qiang Zhai, Xin Li, Fan Yang, Chenglizhao Chen, Hong Cheng, Deng-Ping Fan*</sub></sup> |    CVPR<br />2021     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Mutual_Graph_Learning_for_Camouflaged_Object_Detection_CVPR_2021_paper.pdf)/[Code](https://github.com/fanyang587/MGL) |
| 2021/06 |              -              | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> |    arXiv<br />2021    |         [Paper](https://arxiv.org/abs/2106.13217v3)          |
| 2021/05 |          **ACFM**           | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup> |    IJCAI<br />2021    | [Paper](https://arxiv.org/abs/2105.12555)/[Code](https://github.com/thograce/C2FNet) |
| 2021/05 |          **TINet**          | Inferring Camouflaged Objects by Texture-Aware Interactive Guidance Network <br><sup><sub>*Jinchao Zhu, Xiaoyu Zhang, Shuo Zhang, Junnan Liu*</sub></sup> |    AAAI<br />2021     | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16475) |
| 2021/05 |              -              | CamouFinder: Finding Camouflaged Instances in Images <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> |    AAAI<br />2021     | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA) |
| 2021/03 |         **D2C-Net**         | D2C-Net: A Dual-branch, Dual-guidance and Cross-refine Network for Camouflaged Object Detection <br><sup><sub>*Kang Wang, Hongbo Bi, Yi Zhang, Cong Zhang, Ziqi Liu, Shuang Zheng*</sub></sup> |     TIE<br />2021     | [Paper](https://ieeexplore.ieee.org/document/9430677)/[Code](https://github.com/MS-KangWang/COD-D2Net) |
| 2021/02 |          **SINet**          | Concealed Object Detection (`COD10K dataset`)                       <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Ming-Ming Cheng, Ling Shao*</sub></sup> |    TPAMI<br />2022    | [Paper](https://arxiv.org/abs/2102.10274)/[Code](https://github.com/GewelsJI/SINet-V2) |
| 2021/02 |          **TANet**          | Deep Texture-Aware Features for Camouflaged Object Detection <br><sup><sub>*Jingjing Ren, Xiaowei Hu, Lei Zhu, Xuemiao Xu, et al.*</sub></sup> |    TCSVT<br />2021    |          [Paper](https://arxiv.org/abs/2102.02996)           |
| 2021/01 |         **BASNet**          | Boundary-Aware Segmentation Network for Mobile and Web Applications <br> <sup><sub>*Xuebin Qin, Deng-Ping Fan, Chenyang Huang, et al.*</sub></sup> |         arXiv         | [Paper](https://arxiv.org/abs/2101.04704)/[Code](https://github.com/xuebinqin/BASNet) |
| 2021/01 |        **MCIF-Net**         | Accurate Camouflaged Object Detection via Mixture Convolution and Interactive Fusion <br> <sup><sub>*Bo Dong, Mingchen Zhuge, Yongxiong Wang, Hongbo Bi, Geng Chen*</sub></sup> |    arXiv<br />2021    |          [Paper](https://arxiv.org/abs/2101.05687)           |
|  2021   |          **UGTR**           | Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection <br><sup><sub>*Fan Yang, Qiang Zhai, Xin Li, Rui Huang, et al.*</sub></sup> |    ICCV<br />2021     | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Uncertainty-Guided_Transformer_Reasoning_for_Camouflaged_Object_Detection_ICCV_2021_paper.pdf)/[Code](https://github.com/fanyang587/UGTR) |
|  2020   |          **SINet**          | Camouflaged Object Detection (`COD10K dataset`)                            <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao*</sub></sup> |    CVPR<br />2020     | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)/[Code](https://github.com/DengPingFan/SINet) |
|  2019   |          **ANet**           | Anabranch network for camouflaged object segmentation (`CAMO dataset`) <br><sup><sub>*Trung-Nghia Le, Tam V. Nguyen, Zhongliang Nie, Minh-Triet Tran, Akihiro Sugimoto*</sub></sup> |    CVIU<br />2019     | [Paper](https://arxiv.org/abs/2105.09451)/[Code](https://sites.google.com/view/ltnghia/research/camo)/[Project](https://sites.google.com/view/ltnghia/research/camo) |
| 2018/04 |              -              | Detection of People With Camouflage Pattern Via Dense Deconvolution Network (`CPD1K dataset`) <br><sup><sub>*Yunfei Zheng, Xiongwei Zhang, Feng Wang, Tieyong Cao, Meng Sun, Xiaobing Wang*</sub></sup> |     SPL<br />2019     |    [Paper](https://ieeexplore.ieee.org/document/8336933)     |
| 2018/04 |          **FWFC**           | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup> |     TIP<br />2018     |          [Paper](https://arxiv.org/abs/1804.05984)           |
| 2016/10 |              -              | <span style="white-space:nowrap;">Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour&emsp;&emsp;&emsp;</span> <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup> |    IJCV<br />2016     | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5) |

#### <span id = "p_Video">1.2 Video(VCOD)</span>

|  when   |    what     | title                                                        |       pub.        |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2022/08 |      -      | EM-driven unsupervised learning for efficient motion segmentation <br> <sup><sub>*Etienne Meunier, Ana¨ıs Badoual, and Patrick Bouthemy.*</sub></sup> |  TPAMI<br />2022  | [Paper](https://ieeexplore.ieee.org/document/9855882)/[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation) |
| 2022/06 | **SLT-Net** | **Implicit Motion Handling for Video Camouflaged Object Detection** (`MoCA-Mask dataset`) <br> <sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> |  CVPR<br />2022   | [Paper](https://dengpingfan.github.io/papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)/[Code](https://github.com/XuelianCheng/SLT-Net) |
| 2022/03 |      -      | The Right Spin: Learning Object Motion from Rotation-Compensated Flow Fields <br> <sup><sub>*Pia Bideau, Erik Learned-Miller, Cordelia Schmid, et al.*</sub></sup> |       arXiv       |          [Paper](https://arxiv.org/abs/2203.00115)           |
|  2022   |  **OCLR**   | Segmenting Moving Objects via an Object-Centric Layered Representation <br> <sup><sub>*Junyu Xie, Weidi Xie, Andrew Zisserman.*</sub></sup> | NeurIPS<br />2022 |      [Paper](https://openreview.net/pdf?id=tUH1Or4xblM)      |
|  2021   |      -      | Self-Supervised Video Object Segmentation by Motion Grouping <br> <sup><sub>*Charig Yang, Hala Lamdouar, Erika Lu, et al.*</sub></sup> |  ICCV<br />2021   | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Self-Supervised_Video_Object_Segmentation_by_Motion_Grouping_ICCV_2021_paper.pdf)/[Code](https://github.com/charigyang/motiongrouping)/[Project](https://charigyang.github.io/motiongroup/) |
|  2021   |      -      | Segmenting Invisible Moving Objects <br> <sup><sub>*Hala Lamdouar, Weidi Xie, and Andrew Zisserman.*</sub></sup> |  BMVC<br />2021   | [Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0056.pdf)/[Project](https://www.robots.ox.ac.uk/~vgg/research/simo/) |
|  2020   |      -      | Betrayed By Motion: Camouflaged Object Discovery via Motion Segmentation  (`MoCA dataset`)<br> <sup><sub>*Hala Lamdouar, Charig Yang, Weidi Xie,et al.*</sub></sup> |  ACCV<br />2020   | [Paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.pdf)/[Code](https://github.com/hlamdouar/MoCA/) |
|  2019   |      -      | Object discovery in videos as foreground motion clustering <br> <sup><sub>*Christopher Xie, Yu Xiang, Zaid Harchaoui, et al.*</sub></sup> |  CVPR<br />2019   | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xie_Object_Discovery_in_Videos_as_Foreground_Motion_Clustering_CVPR_2019_paper.pdf) |
| 2018/06 |      -      | The best of both worlds: Combining cnns and geometric constraints for hierarchical motion segmentation <br> <sup><sub>*Pia Bideau, Aruni RoyChowdhury, Rakesh R. Menon,et al.*</sub></sup> |  CVPR<br />2018   | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bideau_The_Best_of_CVPR_2018_paper.pdf)/[Code](https://github.com/pbideau/hierarchical-motion-segmentation) |
| 2016/09 |      -      | <span style="white-space:nowrap;">It’s Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos&emsp;&emsp;&emsp;</span> <br><sup><sub>*Bideau, Pia, and Erik Learned-Miller.*</sub></sup> |  ECCV<br />2016   | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_26) |

#### <span id = "p_Referring">1.3 Reference-Based</span>

|  when   |    what     | title                                                        | pub. |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :--: | :----------------------------------------------------------: |
| 2023/11 |  **MLKG**   | Large Model Based Referring Camouflaged Object Detection<br/><sup><sub>*Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu*</sub></sup> |  -   |          [Paper](https://arxiv.org/abs/2311.17122)           |
| 2023/06 | **Ref-COD** | Referring Camouflaged Object Detection<br/><sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup> |  -   | [Paper](https://arxiv.org/abs/2306.07532)/[Code](https://github.com/zhangxuying1004/RefCOD) |

#### <span id = "p_Open-Vocabulary">1.4 Open-Vocabulary(OVD)</span>

|  when   |     what     | title                                                        |      pub.      |                             link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :------------: | :----------------------------------------------------------: |
| 2022/11 |  **VLDet**   | Learning Object-Language Alignments for Open-Vocabulary Object Detection<br /><sup><sub>Chuang Lin, Peize Sun, Yi Jiang, Ping Luo, Lizhen Qu, Gholamreza Haffari, Zehuan Yuan, Jianfei Cai</sub></sup> | ICLR<br />2023 | [Paper](https://arxiv.org/abs/2211.14843)/[Code](https://github.com/clin1223/VLDet) |
| 2021/11 | **Grad-OVD** | Open Vocabulary Object Detection with Pseudo Bounding-Box Labels<br /><sup><sub>Mingfei Gao, Chen Xing, Juan Carlos Niebles, Junnan Li, ran Xu, Wenhao Liu, Caiming Xiong</sub></sup> | ECCV<br />2022 | [Paer](https://arxiv.org/abs/2111.09452v3)/[Code](https://github.com/salesforce/pb-ovd) |

### <span id = "p_TOS">2. Transparent Object Segmentation(TOS)</span>

|  when   |     what      | title                                                        |      pub.       |                             link                             |
| :-----: | :-----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2022/04 |       -       | Glass Segmentation with RGB-Thermal Image Pairs<br /><sup><sub>Dong Huo, Jian Wang, Yiming Qian, Yee-Hong Yang</sub></sup> |  TIP<br />2023  | [Paper](https://arxiv.org/abs/2204.05453)/[Code](https://github.com/Dong-Huo/RGB-T-Glass-Segmentation) |
| 2022/03 | **ClearPose** | ClearPose: Large-scale Transparent Object Dataset and Benchmark(`ClearPose dataset`)<br /><sup><sub>Xiaotong Chen, Huijie Zhang, Zeren Yu, Anthony Opipari, Odest Chadwicke Jenkins</sub></sup> | ECCV <br />2022 | [Paper](https://arxiv.org/abs/2203.03890)/[Code](https://github.com/opipari/ClearPose) |
| 2021/01 | **Trans2Seg** | Segmenting Transparent Object in the Wild with Transformer (`Trans10K-v2 dataset`)<br /><sup><sub>Enze Xie, Wenjia Wang, Wenhai Wang, Peize Sun, Hang Xu, Ding Liang, Ping Luo</sub></sup> | IJCAI<br />2021 | [Paper](https://arxiv.org/abs/2101.08461v3)/[Code](https://github.com/xieenze/Trans2Seg) |
| 2020/06 |   **GDNet**   | Don’t Hit Me! Glass Detection in Real-world Scenes (`GDD dataset`)<br /><sup><sub>Haiyang Mei, Xin Yang, Yang Wang, Yuanyuan Liu, Shengfeng He, Qiang Zhang, Xiaopeng Wei, Rynson W.H. Lau</sub></sup> | CVPR<br />2020  | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mei_Dont_Hit_Me_Glass_Detection_in_Real-World_Scenes_CVPR_2020_paper.pdf)/[Code](https://github.com/Mhaiyang/CVPR2020_GDNet) |
| 2020/03 | **TransLab**  | Segmenting Transparent Objects in the Wild (`Trans10K dataset`)<br /><sup><sub>Enze Xie, Wenjia Wang, Wenhai Wang, Mingyu Ding, Chunhua Shen, Ping Luo</sub></sup> | ECCV<br />2020  | [Paper](https://arxiv.org/abs/2003.13948)/[Code](https://github.com/xieenze/Segment_Transparent_Objects) |
| 2018/03 |  **TOM-Net**  | TOM-Net: Learning Transparent Object Matting from a Single Image (`TOM-Net dataset`)<br /><sup><sub>Guanying Chen, Kai Han, Kwan-Yee K. Wong</sub></sup> | CVPR<br />2018  | [Paper](https://guanyingc.github.io/TOM-Net/files/tom-net_cvpr18.pdf)/[Code](https://github.com/guanyingc/TOM-Net) |
| 2015/11 | **TransCut**  | TransCut: Transparent Object Segmentation from a Light-Field Image (`TransCut dataset`)<br /><sup><sub>Yichao Xu, Hajime Nagahara, Atsushi Shimada, Rin-ichiro Taniguchi</sub></sup> | ICCV<br />2015  |          [Paper](https://arxiv.org/abs/1511.06853)           |

### <span id = "p_SDD">3. Surface Defect Detection(SDD)</span>

|  when   | what | title                                                        |           pub.           |                   link                    |
| :-----: | :--: | ------------------------------------------------------------ | :----------------------: | :---------------------------------------: |
| 2019/03 |  -   | Segmentation Based Deep-Learning Approach for Surface DefectDetection (`KolektorSDD dataset`)<br /><sup><sub>Domen Tabernik, Samo Šela, Jure Skvarč, Danijel Skočaj</sub></sup> | J Intell Manuf<br />2019 | [Paper](https://arxiv.org/abs/1903.08536) |

### <span id = "p_PS">4. Polyp Segmentation(PS)</span>

|  when   |    what    | title                                                        |        pub.         |                             link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :-----------------: | :----------------------------------------------------------: |
| 2022/09 | **LDNet**  | Lesion-aware Dynamic Kernel for Polyp Segmentation<br /><sup><sub>Ruifei Zhang, Peiwen Lai, Xiang Wan, De-Jun Fan, Feng Gao, Xiao-Jian Wu & Guanbin Li</sub></sup> |  MICCAI<br />2022   | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_10)/[Code](https://github.com/ReaFly/LDNet) |
| 2022/08 | **BCNet**  | Boundary Constraint Network With Cross Layer Feature Integration for Polyp Segmentation<br/><sup><sub>*Guanghui Yue, Wanwan Han, Bin Jiang, Tianwei Zhou, Runmin Cong, Tianfu Wang*</sub></sup> | IEEE JHBI<br />2022 | [Paper](https://ieeexplore.ieee.org/document/9772424/authors#authors) |
| 2022/05 | **TGANet** | TGANet: Text-Guided Attention for Improved Polyp Segmentation<br /><sup><sub>*Nikhil Kumar Tomar, Debesh Jha, Ulas Bagci, Sharib Ali*</sub></sup> |  MICCAI<br />2022   | [Paper](https://arxiv.org/abs/2205.04280)/[Code](https://github.com/nikhilroxtomar/TGANet) |

### <span id = "p_LND">5. Lung Nodule Detection(LND)</span>

|  when   |    what     | title                                                        |       pub.       |                             link                             |
| :-----: | :---------: | :----------------------------------------------------------- | :--------------: | :----------------------------------------------------------: |
| 2022/08 | **LSSANet** | LSSANet: A Long Short Slice-Aware Network for Pulmonary Nodule Detection<br /><sup><sub>*Rui Xu, Yong Luo, Bo Du, Kaiming Kuang, Jiancheng Yang*</sub></sup> | MICCAI<br />2022 | [Paper](https://arxiv.org/abs/2208.02122)/[Code](https://github.com/Ruixxxx/LSSANet) |
| 2021/03 |  **SANet**  | SANet: A Slice-Aware Network for Pulmonary Nodule Detection(`PN9 dataset`)<br /><sup><sub>Domen Tabernik, Samo Šela, Jure Skvarč, Danijel Skočaj</sub></sup> | TPAMI<br />2021  | [Paper](https://mftp.mmcheng.net/Papers/21pami-lungNodule.pdf)/[Code](https://github.com/mj129/SANet) |

## <span id = "Datasets">Datasets</span>

### <span id = "d_COD">1. Camouflaged Object Detection(COD)</span>

|                             Name                             | Year | Pub. |                            Links                             | level |
| :----------------------------------------------------------: | :--: | :--: | :----------------------------------------------------------: | :---: |
| [NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2021/Papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_Paper.pdf) | Image |
| [CAMO++](https://sites.google.com/view/ltnghia/research/camo_plus_plus?authuser=0) | 2021 | TIP  |          [Paper](https://arxiv.org/abs/2103.17123)           | Image |
|            [COD10K](http://dpfan.net/camouflage/)            | 2020 | CVPR | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/Papers/Fan_Camouflaged_Object_Detection_CVPR_2020_Paper.pdf) | Image |
| [CAMO](https://sites.google.com/view/ltnghia/research/camo)  | 2019 | CVIU | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) | Image |
| [CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2018 | SPL  |    [Paper](https://ieeexplore.ieee.org/document/8336933)     | Image |
| [CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 |  -   | [Webpage](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | Image |
| [MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 | CVPR |          [Paper](https://arxiv.org/abs/2203.07363)           | Video |
|     [MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/)      | 2020 | ACCV | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_Paper.html) | Video |
| [Camouflaged Animal](http://vis-www.cs.umass.edu/motionSegmentation/) | 2016 | ECCV | [Paper](http://vis-www.cs.umass.edu/motionSegmentation/ECCV16Paper/1698.pdf) | Video |

### <span id = "d_TOS">2. Transparent Object Segmentation(TOS)</span>

|                             Name                             | Year | Pub.  |                            Links                             | level |
| :----------------------------------------------------------: | :--: | :---: | :----------------------------------------------------------: | :---: |
| [ClearPose](https://github.com/opipari/ClearPose?tab=readme-ov-file) | 2022 | ECCV  |          [Paper](https://arxiv.org/abs/2203.03890)           | Image |
| [Trans10K-v2](https://github.com/xieenze/Trans2Seg?tab=readme-ov-file) | 2021 | IJCAI |         [Paper](https://arxiv.org/abs/2101.08461v3)          | Image |
|    [GDD](https://mhaiyang.github.io/CVPR2020_GDNet/index)    | 2020 | CVPR  | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mei_Dont_Hit_Me_Glass_Detection_in_Real-World_Scenes_CVPR_2020_paper.pdf) | Image |
| [Trans10K](https://xieenze.github.io/projects/TransLAB/TransLAB.html) | 2020 | ECCV  |          [Paper](https://arxiv.org/abs/2003.13948)           | Image |
|       [TOM-Net](https://guanyingc.github.io/TOM-Net/)        | 2018 | CVPR  | [Paper](https://guanyingc.github.io/TOM-Net/files/tom-net_cvpr18.pdf) | Image |
|                           TransCut                           | 2015 | ICCV  |          [Paper](https://arxiv.org/abs/1511.06853)           | Image |

### <span id = "d_SDD">3. Surface Defect Detection(SDD)</span>

|                            Name                            | Year | Pub. |                         Links                          | level |
| :--------------------------------------------------------: | :--: | :--: | :----------------------------------------------------: | :---: |
| [KolektorSDD](https://www.vicos.si/resources/kolektorsdd/) | 2019 | CVPR |       [Paper](https://arxiv.org/abs/1903.08536)        | Image |
|    [DAGM](https://hci.iwr.uni-heidelberg.de/node/3616)     |  -   |  -   | [Webpage](https://hci.iwr.uni-heidelberg.de/node/3616) | Image |

### <span id = "d_PS">4. Polyp Segmentation(PS)</span>

|                             Name                             | Year |              Pub.               |                            Links                             | level |
| :----------------------------------------------------------: | :--: | :-----------------------------: | :----------------------------------------------------------: | :---: |
| [LDPolypVideo](https://github.com/dashishi/LDPolypVideo-Benchmark) | 2021 |             MICCAI              | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_37) | Video |
|     [Kvasir-SEG](https://datasets.simula.no/kvasir-seg/)     | 2020 |               MMM               |          [Paper](https://arxiv.org/abs/1911.07069)           | Image |
|        [EndoScene](http://adas.cvc.uab.es/endoscene)         | 2017 |          J HEALTHC ENG          | [Paper](https://www.hindawi.com/journals/jhe/2017/4037190/)  | Image |
|                         CVC-ColonDB                          | 2016 |            IEEE TMI             |    [Paper](https://ieeexplore.ieee.org/document/7294676)     | Image |
| [CVC-ClinicDB](https://polyp.grand-challenge.org/CVCClinicDB/) | 2015 |              CMIG               | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611115000567?via%3Dihub) | Image |
|                             ETIS                             | 2013 | Int J Comput Assist Radiol Surg |      [Paper](https://pubmed.ncbi.nlm.nih.gov/24037504/)      | Image |
|    [ASU-Mayo](https://polyp.grand-challenge.org/AsuMayo/)    |  -   |                -                |    [Webpage](https://polyp.grand-challenge.org/AsuMayo/)     | Image |

### <span id = "d_LND">5. Lung Nodule Detection(LND)</span>

|                     Name                     | Year | Pub.  |                            Links                             | level |
| :------------------------------------------: | :--: | :---: | :----------------------------------------------------------: | :---: |
| [PN9](https://jiemei.xyz/publications/SANet) | 2021 | TPAMI | [Paper](https://mftp.mmcheng.net/Papers/21pami-lungNodule.pdf) | Image |

## <span id = "Recommended">Latest Works Recommended</span>

**Strategic Preys Make Acute Predators: Enhancing Camouflaged Object Detectors by Generating Camouflaged Objects**<br/>Chunming He, Kai Li*, Yachao Zhang, Yulun Zhang, Zhenhua Guo, Xiu Li*, Martin Danelljan, Fisher Yu<br/>
ICLR 2024. [Paper](https://arxiv.org/pdf/2308.03166.pdf)/[Code](https://github.com/ChunmingHe/Camouflageator)

## <span id = "Reference">Reference</span>

[SINet-V2/AWESOME_COD_LIST.md](https://github.com/GewelsJI/SINet-V2/blob/main/AWESOME_COD_LIST.md)

[visionxiang/awesome-camouflaged-object-detection](https://github.com/visionxiang/awesome-camouflaged-object-detection)
