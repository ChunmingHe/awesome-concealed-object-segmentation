# Awesome Concealed Object Segmentation

A curated list of awesome **Concealed Object Segmentation** (COS) works. 

We will keep updating it.

**Last updated at 2024/01/16.**

---

## Contributing

Please feel free to send us pull requests or email us(issja_hu@163.com) to add links.

## Contents

* [Papers](#Papers)
  * [Camouflaged Object Detection(COD)](#1)
    * [Normal](#1.1)
    * [Video(VCOD)](#1.2)
    * [Reference-Based](#1.3)
    * [Open-Vocabulary](#1.4)
  * [Transparent Object Segmentation(TOS)](#2)
  * [Surface Defect Detection(SDD)](#3)
  * [Polyp Segmentation(PS)](#4)
  * [Lung Nodule Detection(LND)](#5)
* [Datasets](#Datasets)
* [Latest Works Recommended](#Latest)
* [Reference](#Reference)

## <span id = "Papers">Papers</span>

### <span id = "1">1. Camouflaged Object Detection(COD)</span>

#### <span id = "1.1">1.1 Normal</span>

|  when   |    what    | title                                                        |       pub.        |                             link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2023/12 | **GenSAM** | **Relax Image-Specific Prompt Requirement in SAM: A Single Generic Prompt for Segmenting Camouflaged Objects**<br/><sup><sub>*Jian Hu, Jiayi Lin, Weitong Cai, Shaogang Gong*</sub></sup> |   AAAI<br/>2024   | [Paper](https://arxiv.org/abs/2311.07374)/[Code](https://github.com/jyLin8100/GenSAM)/[Demo](https://lwpyh.github.io/GenSAM/) |
| 2023/08 | **FPNet**  | **Frequency Perception Network for Camouflaged Object Detection**<br/><sup><sub>*Runmin Cong, Mengyao Sun, Sanyi Zhang, Xiaofei Zhou, Wei Zhang, Yao Zhao*</sub></sup> | ACM MM<br />2023  | [Paper](https://arxiv.org/abs/2308.08924)/[Code](https://github.com/rmcong/FPNet_ACMMM23) |
| 2023/05 |     -      | **Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping**<br/><sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup> | NeurIPS<br />2023 | [Paper](https://arxiv.org/abs/2305.11003)/[Code](https://github.com/ChunmingHe/WS-SAM) |

#### <span id = "1.2">1.2 Video(VCOD)</span>

|  when   |    what     | title                                                        |       pub.        |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :---------------: | :----------------------------------------------------------: |
| 2023/04 |      -      | **EM-driven unsupervised learning for efficient motion segmentation**<br /><sup><sub>*Etienne Meunier, Ana¨ıs Badoual, and Patrick Bouthemy.*</sub></sup> |  TPAMI<br />2022  | [Paper](https://ieeexplore.ieee.org/document/9855882)/[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation) |
| 2022/07 |  **OCLR**   | **Segmenting Moving Objects via an Object-Centric Layered Representation**<br /><sup><sub>*Junyu Xie, Weidi Xie, Andrew Zisserman.*</sub></sup> | NeurIPS<br />2022 |      [Paper](https://openreview.net/pdf?id=tUH1Or4xblM)      |
| 2022/03 | **SLT-Net** | **Implicit Motion Handling for Video Camouflaged Object Detection** (`MoCA-Mask dataset`)<br/><sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> |  CVPR<br />2022   | [Paper](https://dengpingfan.github.io/Papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)/[Code](https://github.com/XuelianCheng/SLT-Net) |

#### <span id = "1.3">1.3 Reference-Based</span>

|  when   |    what     | title                                                        | pub. |                             link                             |
| :-----: | :---------: | ------------------------------------------------------------ | :--: | :----------------------------------------------------------: |
| 2023/11 |  **MLKG**   | **Large Model Based Referring Camouflaged Object Detection**<br/><sup><sub>*Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu*</sub></sup> |  -   |          [Paper](https://arxiv.org/abs/2311.17122)           |
| 2023/06 | **Ref-COD** | **Referring Camouflaged Object Detection**<br/><sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup> |  -   | [Paper](https://arxiv.org/abs/2306.07532)/[Code](https://github.com/zhangxuying1004/RefCOD) |

#### <span id = "1.4">1.4 Open-Vocabulary(OVD)</span>

|  when   |     what     | title                                                        |      pub.      |                             link                             |
| :-----: | :----------: | ------------------------------------------------------------ | :------------: | :----------------------------------------------------------: |
| 2021/11 | **Grad-OVD** | **Open Vocabulary Object Detection with Pseudo Bounding-Box Labels**<br /><sup><sub>Mingfei Gao, Chen Xing, Juan Carlos Niebles, Junnan Li, ran Xu, Wenhao Liu, Caiming Xiong</sub></sup> | ECCV<br />2022 | [Paer](https://arxiv.org/abs/2111.09452v3)/[Code](https://github.com/salesforce/pb-ovd) |
| 2022/11 |  **VLDet**   | **Learning Object-Language Alignments for Open-Vocabulary Object Detection**<br /><sup><sub>Chuang Lin, Peize Sun, Yi Jiang, Ping Luo, Lizhen Qu, Gholamreza Haffari, Zehuan Yuan, Jianfei Cai</sub></sup> | ICLR<br />2023 | [Paper](https://arxiv.org/abs/2211.14843)/[Code](https://github.com/clin1223/VLDet) |

### <span id = "2">2. Transparent Object Segmentation(TOS)</span>

|  when   |     what      | title                                                        |      pub.       |                             link                             |
| :-----: | :-----------: | ------------------------------------------------------------ | :-------------: | :----------------------------------------------------------: |
| 2022/04 |       -       | **Glass Segmentation with RGB-Thermal Image Pairs**<br /><sup><sub>Dong Huo, Jian Wang, Yiming Qian, Yee-Hong Yang</sub></sup> | CVPR<br />2022  | [Paper](https://arxiv.org/abs/2204.05453)/[Code](https://github.com/Dong-Huo/RGB-T-Glass-Segmentation) |
| 2022/03 | **ClearPose** | **ClearPose: Large-scale Transparent Object Dataset and Benchmark**(`ClearPose dataset`)<br /><sup><sub>Xiaotong Chen, Huijie Zhang, Zeren Yu, Anthony Opipari, Odest Chadwicke Jenkins</sub></sup> | ECCV <br />2022 | [Paper](https://arxiv.org/abs/2203.03890)/[Code](https://github.com/opipari/ClearPose) |
| 2021/01 | **Trans2Seg** | **Segmenting Transparent Object in the Wild with Transformer** (`Trans10K-v2 dataset`)<br /><sup><sub>Enze Xie, Wenjia Wang, Wenhai Wang, Peize Sun, Hang Xu, Ding Liang, Ping Luo</sub></sup> | IJCAI<br />2021 | [Paper](https://arxiv.org/abs/2101.08461v3)/[Code](https://github.com/xieenze/Trans2Seg) |
| 2020/06 |   **GDNet**   | **Don’t Hit Me! Glass Detection in Real-world Scenes** (`GDD dataset`)<br /><sup><sub>Haiyang Mei, Xin Yang, Yang Wang, Yuanyuan Liu, Shengfeng He, Qiang Zhang, Xiaopeng Wei, Rynson W.H. Lau</sub></sup> | CVPR<br />2020  | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mei_Dont_Hit_Me_Glass_Detection_in_Real-World_Scenes_CVPR_2020_paper.pdf)/[Code](https://github.com/Mhaiyang/CVPR2020_GDNet) |
| 2020/03 | **TransLab**  | **Segmenting Transparent Objects in the Wild**(`Trans10K dataset`)<br /><sup><sub>Enze Xie, Wenjia Wang, Wenhai Wang, Mingyu Ding, Chunhua Shen, Ping Luo</sub></sup> | ECCV<br />2020  | [Paper](https://arxiv.org/abs/2003.13948)/[Code](https://github.com/xieenze/Segment_Transparent_Objects) |
| 2018/03 |  **TOM-Net**  | **TOM-Net: Learning Transparent Object Matting from a Single Image**(`TOM-Net dataset`)<br /><sup><sub>Guanying Chen, Kai Han, Kwan-Yee K. Wong</sub></sup> | CVPR<br />2018  | [Paper](https://guanyingc.github.io/TOM-Net/files/tom-net_cvpr18.pdf)/[Code](https://github.com/guanyingc/TOM-Net) |
| 2015/11 | **TransCut**  | **TransCut: Transparent Object Segmentation from a Light-Field Image**(`TransCut dataset`)<br /><sup><sub>Yichao Xu, Hajime Nagahara, Atsushi Shimada, Rin-ichiro Taniguchi</sub></sup> | ICCV<br />2015  |          [Paper](https://arxiv.org/abs/1511.06853)           |

### <span id = "3">3. Surface Defect Detection(SDD)</span>

|  when   | what | title                                                        |      pub.      |                   link                    |
| :-----: | :--: | ------------------------------------------------------------ | :------------: | :---------------------------------------: |
| 2019/03 |  -   | **Segmentation Based Deep-Learning Approach for Surface DefectDetection**(`KolektorSDD dataset`)<br /><sup><sub>Domen Tabernik, Samo Šela, Jure Skvarč, Danijel Skočaj</sub></sup> | CVPR<br />2019 | [Paper](https://arxiv.org/abs/1903.08536) |

### <span id = "4">4. Polyp Segmentation(PS)</span>

|  when   |    what    | title                                                        |        pub.         |                             link                             |
| :-----: | :--------: | ------------------------------------------------------------ | :-----------------: | :----------------------------------------------------------: |
| 2022/09 | **LDNet**  | **Lesion-aware Dynamic Kernel for Polyp Segmentation**<br /><sup><sub>Ruifei Zhang, Peiwen Lai, Xiang Wan, De-Jun Fan, Feng Gao, Xiao-Jian Wu & Guanbin Li</sub></sup> |  MICCAI<br />2022   | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_10)/[Code](https://github.com/ReaFly/LDNet) |
| 2022/08 | **BCNet**  | **Boundary Constraint Network With Cross Layer Feature Integration for Polyp Segmentation**<br/><sup><sub>*Guanghui Yue, Wanwan Han, Bin Jiang, Tianwei Zhou, Runmin Cong, Tianfu Wang*</sub></sup> | IEEE JHBI<br />2022 | [Paper](https://ieeexplore.ieee.org/document/9772424/authors#authors) |
| 2022/05 | **TGANet** | **TGANet: Text-Guided Attention for Improved Polyp Segmentation**<br /><sup><sub>*Nikhil Kumar Tomar, Debesh Jha, Ulas Bagci, Sharib Ali*</sub></sup> |  MICCAI<br />2022   | [Paper](https://arxiv.org/abs/2205.04280)/[Code](https://github.com/nikhilroxtomar/TGANet) |

### <span id = "5">5. Lung Nodule Detection(LND)</span>

|  when   |    what     | title                                                        |       pub.       |                             link                             |
| :-----: | :---------: | :----------------------------------------------------------- | :--------------: | :----------------------------------------------------------: |
| 2022/08 | **LSSANet** | **LSSANet: A Long Short Slice-Aware Network for Pulmonary Nodule Detection**<br /><sup><sub>*Rui Xu, Yong Luo, Bo Du, Kaiming Kuang, Jiancheng Yang*</sub></sup> | MICCAI<br />2022 | [Paper](https://arxiv.org/abs/2208.02122)/[Code](https://github.com/Ruixxxx/LSSANet) |
| 2021/03 |  **SANet**  | **SANet: A Slice-Aware Network for Pulmonary Nodule Detection**(`PN9 dataset`)<br /><sup><sub>Domen Tabernik, Samo Šela, Jure Skvarč, Danijel Skočaj</sub></sup> | TPAMI<br />2021  | [Paper](https://mftp.mmcheng.net/Papers/21pami-lungNodule.pdf)/[Code](https://github.com/mj129/SANet) |

## <span id = "Datasets">Datasets</span>

|                             Name                             | Year |              Pub.               |                            Links                             | task | level |
| :----------------------------------------------------------: | :--: | :-----------------------------: | :----------------------------------------------------------: | :--: | :---: |
| [NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 |              CVPR               | [Paper](https://openaccess.thecvf.com/content/CVPR2021/Papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_Paper.pdf) | COD  | Image |
| [CAMO++](https://sites.google.com/view/ltnghia/research/camo_plus_plus?authuser=0) | 2021 |               TIP               |          [Paper](https://arxiv.org/abs/2103.17123)           | CIS  | Image |
|            [COD10K](http://dpfan.net/camouflage/)            | 2020 |              CVPR               | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/Papers/Fan_Camouflaged_Object_Detection_CVPR_2020_Paper.pdf) | COD  | Image |
| [CAMO](https://sites.google.com/view/ltnghia/research/camo)  | 2019 |              CVIU               | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) | COD  | Image |
| [CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2018 |               SPL               |    [Paper](https://ieeexplore.ieee.org/document/8336933)     | COD  | Image |
| [CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 |                -                | [Webpage](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | COD  | Image |
| [MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 |              CVPR               |          [Paper](https://arxiv.org/abs/2203.07363)           | VCOD | Video |
|     [MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/)      | 2020 |              ACCV               | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_Paper.html) | VCOD | Video |
| [Camouflaged Animal](http://vis-www.cs.umass.edu/motionSegmentation/) | 2016 |              ECCV               | [Paper](http://vis-www.cs.umass.edu/motionSegmentation/ECCV16Paper/1698.pdf) | VCOS | Video |
| [ClearPose](https://github.com/opipari/ClearPose?tab=readme-ov-file) | 2022 |              ECCV               |          [Paper](https://arxiv.org/abs/2203.03890)           | TOS  | Image |
| [Trans10K-v2](https://github.com/xieenze/Trans2Seg?tab=readme-ov-file) | 2021 |              IJCAI              |         [Paper](https://arxiv.org/abs/2101.08461v3)          | TOS  | Image |
|    [GDD](https://mhaiyang.github.io/CVPR2020_GDNet/index)    | 2020 |              CVPR               | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mei_Dont_Hit_Me_Glass_Detection_in_Real-World_Scenes_CVPR_2020_paper.pdf) | TOS  | Image |
| [Trans10K](https://xieenze.github.io/projects/TransLAB/TransLAB.html) | 2020 |              ECCV               |          [Paper](https://arxiv.org/abs/2003.13948)           | TOS  | Image |
|       [TOM-Net](https://guanyingc.github.io/TOM-Net/)        | 2018 |              CVPR               | [Paper](https://guanyingc.github.io/TOM-Net/files/tom-net_cvpr18.pdf) | TOS  | Image |
|                           TransCut                           | 2015 |              ICCV               |          [Paper](https://arxiv.org/abs/1511.06853)           | TOS  | Image |
|  [KolektorSDD](https://www.vicos.si/resources/kolektorsdd/)  | 2019 |              CVPR               |          [Paper](https://arxiv.org/abs/1903.08536)           | SDD  | Image |
|     [DAGM](https://hci.iwr.uni-heidelberg.de/node/3616)      |  -   |                -                |    [Webpage](https://hci.iwr.uni-heidelberg.de/node/3616)    | SDD  | Image |
| [LDPolypVideo](https://github.com/dashishi/LDPolypVideo-Benchmark) | 2021 |             MICCAI              | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_37) |  PS  | Video |
|     [Kvasir-SEG](https://datasets.simula.no/kvasir-seg/)     | 2020 |               MMM               |          [Paper](https://arxiv.org/abs/1911.07069)           |  PS  | Image |
|        [EndoScene](http://adas.cvc.uab.es/endoscene)         | 2017 |          J HEALTHC ENG          | [Paper](https://www.hindawi.com/journals/jhe/2017/4037190/)  |  PS  | Image |
|                         CVC-ColonDB                          | 2016 |            IEEE TMI             |    [Paper](https://ieeexplore.ieee.org/document/7294676)     |  PS  | Image |
| [CVC-ClinicDB](https://polyp.grand-challenge.org/CVCClinicDB/) | 2015 |              CMIG               | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611115000567?via%3Dihub) |  PS  | Image |
|                             ETIS                             | 2013 | Int J Comput Assist Radiol Surg |      [Paper](https://pubmed.ncbi.nlm.nih.gov/24037504/)      |  PS  | Image |
|    [ASU-Mayo](https://polyp.grand-challenge.org/AsuMayo/)    |  -   |                -                |    [Webpage](https://polyp.grand-challenge.org/AsuMayo/)     |  PS  | Image |
|         [PN9](https://jiemei.xyz/publications/SANet)         | 2021 |              TPAMI              | [Paper](https://mftp.mmcheng.net/Papers/21pami-lungNodule.pdf) | LND  | Image |

## <span id = "Latest">Latest Works Recommended</span>

**Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping**. <br/>
*Chunming He†, Kai Li†, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*<br/>
NeurIPS 2023. [[Paper](https://arxiv.org/abs/2305.11003)] [[Code](https://github.com/ChunmingHe/WS-SAM)]<br/>
May 2023

## <span id = "Reference">Reference</span>

[AWESOME_COD_LIST](https://github.com/GewelsJI/SINet-V2/blob/main/AWESOME_COD_LIST.md)
