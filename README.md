## CVPR2021_Papers汇总，主要包括论文链接、代码地址、文章解读等等
### 关注公众号【深度学习技术前沿】后台回复 **CVPR2021** 获得百度云下载链接

------

- 官网链接：http://cvpr2021.thecvf.com<br>
- 时间：2021年6月19日-6月25日<br>
- 论文接收公布时间：2021年2月28日<br>
- CVPR2021官方接受论文列表：[http://cvpr2021.thecvf.com/sites/default/files/2021-03/accepted_paper_ids.txt](http://cvpr2021.thecvf.com/sites/default/files/2021-03/accepted_paper_ids.txt)
------

## 1.CVPR2021接受论文/代码分方向整理(持续更新)

# 分类目录：
## Low-Level-Vision(主要包括：超分辨率，图像恢复，去雨，去雾，去模糊，去噪，重建等方向)
- [1.超分辨率（Super-Resolution）](#1.超分辨率)
- [2.图像去雨（Image Deraining）](#2.图像去雨)
- [3.图像去雾（Image Dehazing）](#3.图像去雾)
- [4.去模糊（Deblurring）](#4.去模糊)
- [5.去噪（Denoising）](#5.去噪)
- [6.图像恢复（Image Restoration）](#6.图像恢复)
- [7.图像增强（Image Enhancement）](#7.图像增强)
- [8.图像去摩尔纹（Image Demoireing）](#8.图像去摩尔纹)
- [9.图像阴影去除(Image Shadow Removal)](#9.图像阴影去除)
- [10.图像翻译（Image Translation）](#10.图像翻译)
- [11.插帧（Frame Interpolation）](#11.插帧)
- [12.视频压缩（Video Compression）](#12.视频压缩)
- 

## High-Level-Vision（主要包括：图像分类，检测，分割，跟踪，GAN等方向）
### [检测](#detection)
* [图像目标检测(Image Object Detection)](#IOD)<br>
* [视频目标检测(Video Object Detection)](#VOD)<br>
* [三维目标检测(3D Object Detection)](#3DOD)<br>
* [动作检测(Activity Detection)](#ActivityDetection)<br>
* [异常检测(Anomally Detetion)](#AnomallyDetetion)<br>

### [图像分割(Image Segmentation)](#ImageSegmentation)
* [全景分割(Panoptic Segmentation)](#PanopticSegmentation)<br>
* [语义分割(Semantic Segmentation)](#SemanticSegmentation)<br>
* [实例分割(Instance Segmentation)](#InstanceSegmentation)<br>
* [抠图(Matting)](#Matting)<br>

### [人脸(Face)](#Face)

### [目标跟踪(Object Tracking)](#ObjectTracking)

### [重识别(Re-Identification)](#Re-Identification)

### [医学影像(Medical Imaging)](#MedicalImaging)

### [GAN/生成式/对抗式(GAN/Generative/Adversarial)](#GAN)

### [估计(Estimation)](#Estimation)
* [人体姿态估计(Human Pose Estimation)](#HumanPoseEstimation)
* [手势估计(Gesture Estimation)](#GestureEstimation)
* [光流/位姿/运动估计(Flow/Pose/Motion Estimation)](#Flow/Pose/MotionEstimation)

### [三维视觉(3D Vision)](#3DVision)
* [三维点云(3D Point Cloud)](#3DPC)<br>
* [三维重建(3D Reconstruction)](#3DReconstruction)<br>

## 模型架构与数据处理（主要包括：Transformer，Backbone，NAS，模型压缩，模型评估）

### [Transformer](#Transformer)<br>

### [神经网络架构(Neural Network Structure)](#NNS)
* [图神经网络(GNN)](#GNN)<br>

### [神经网络架构搜索(NAS)](#NAS)

### [数据处理(Data Processing)](#DataProcessing)
* [数据增广(Data Augmentation)](#DataAugmentation)<br>
* [归一化/正则化(Batch Normalization)](#BatchNormalization)<br>
* [图像聚类(Image Clustering)](#ImageClustering)<br>

### [模型压缩(Model Compression)](#ModelCompression)
* [知识蒸馏(Knowledge Distillation)](KnowledgeDistillation)<br>

### [模型评估(Model Evaluation)](#ModelEvaluation)

### [数据集(Database)](#Database)
<br>

## 其它方向
### [主动学习(Active Learning)](#ActiveLearning)

### [小样本学习/零样本(Few-shot Learning)](#Few-shotLearning)

### [持续学习(Continual Learning/Life-long Learning)](#ContinualLearning)

### [视觉推理(Visual Reasoning)](#VisualReasoning)

### [迁移学习/domain/自适应](#domain)

### [对比学习(Contrastive Learning)](#ContrastiveLearning)

### [图像/视频检索(Image Retrieval)](#ImageRetrieval)
<br>

## 3. CVPR2021的论文解读
 - [论文解读](#Reading)

<br><br>

<a name="1.超分辨率"></a>

## 1.超分辨率（Super-Resolution）

### Unsupervised Degradation Representation Learning for Blind Super-Resolution
- Paper：
- Code：[https://github.com/LongguangWang/DASR](https://github.com/LongguangWang/DASR)

### Data-Free Knowledge Distillation For Image Super-Resolution
### AdderSR: Towards Energy Efficient Image Super-Resolution
- Paper：[https://arxiv.org/abs/2009.08891](https://arxiv.org/abs/2009.08891)
- Code：

### Exploring Sparsity in Image Super-Resolution for Efficient Inference
- Paper：[https://arxiv.org/abs/2006.09603](https://arxiv.org/abs/2006.09603)
- Code：[https://github.com/LongguangWang/SMSR](https://github.com/LongguangWang/SMSR)

### ClassSR: A General Framework to Accelerate Super-Resolution Networks by Data Characteristic
- Code：[https://github.com/Xiangtaokong/ClassSR](https://github.com/Xiangtaokong/ClassSR)

### Cross-MPI: Cross-scale Stereo for Image Super-Resolution using Multiplane Images
- Paper：[https://arxiv.org/abs/2011.14631](https://arxiv.org/abs/2011.14631)
- Code：
- Homepage：[http://www.liuyebin.com/crossMPI/crossMPI.html](http://www.liuyebin.com/crossMPI/crossMPI.html)
- Analysis：[CVPR 2021，Cross-MPI以底层场景结构为线索的端到端网络，在大分辨率（x8）差距下也可完成高保真的超分辨率](https://zhuanlan.zhihu.com/p/354752197)
<a name="2.图像去雨"></a>
## 2.图像去雨（Image Deraining）

<a name="3.图像去雾"></a>
## 3.图像去雾（Image Dehazing）

<a name="4.去模糊"></a>
## 4.去模糊（Deblurring）
### DeFMO: Deblurring and Shape Recovery of Fast Moving Objects(快速移动物体的去模糊和形状恢复)<br>
- [paper](https://arxiv.org/abs/2012.00595)
- [code](https://github.com/rozumden/DeFMO)
- [video](https://www.youtube.com/watch?v=pmAynZvaaQ4)<br>

<a name="5.去噪"></a>
## 5.去噪（Denoising）

<a name="6.图像恢复"></a>
## 6.图像恢复（Image Restoration）
### Multi-Stage Progressive Image Restoration
- Paper：[https://arxiv.org/abs/2102.02808](https://arxiv.org/abs/2102.02808)
- Code：[https://github.com/swz30/MPRNet](https://github.com/swz30/MPRNet)

### CT Film Recovery via Disentangling Geometric Deformation and Illumination Variation: Simulated Datasets and Deep Models
- Paper：[https://arxiv.org/abs/2012.09491](https://arxiv.org/abs/2012.09491)
- Code：[https://github.com/transcendentsky/Film-Recovery](https://github.com/transcendentsky/Film-Recovery)

### Data-Free Knowledge Distillation For Image Super-Resolution(DAFL算法的SR版本)<br><br>

### AdderSR: Towards Energy Efficient Image Super-Resolution(将加法网路应用到图像超分辨率中)<br>
- 论文地址:[https://arxiv.org/pdf/2009.08891.pdf](https://arxiv.org/pdf/2009.08891.pdf)
- 代码地址:[https://github.com/huawei-noah/AdderNet](https://github.com/huawei-noah/AdderNet)<br>
- 解读：[华为开源加法神经网络](https://zhuanlan.zhihu.com/p/113536045)<br><br>

<a name="7.图像增强"></a>
## 7.图像增强（Image Enhancement）
### Auto-Exposure Fusion for Single-Image Shadow Removal
- Paper：[https://arxiv.org/abs/2103.01255](https://arxiv.org/abs/2103.01255)
- Code：[https://github.com/tsingqguo/exposure-fusion-shadow-removal](https://github.com/tsingqguo/exposure-fusion-shadow-removal)
### Learning Multi-Scale Photo Exposure Correction
- Paper：[https://arxiv.org/abs/2003.11596](https://arxiv.org/abs/2003.11596)
- Code：[https://github.com/mahmoudnafifi/Exposure_Correction](https://github.com/mahmoudnafifi/Exposure_Correction)
### DeFMO: Deblurring and Shape Recovery of Fast Moving Objects
- Paper：[hhttps://arxiv.org/abs/2012.00595](https://arxiv.org/abs/2012.00595)
- Code：[https://github.com/rozumden/DeFMO](https://github.com/rozumden/DeFMO)
<a name="8.图像去摩尔纹"></a>
## 8.图像去摩尔纹（Image Demoireing）

<a name="9.图像阴影去除"></a>
## 9.图像阴影去除(Image Shadow Removal)
### Auto-Exposure Fusion for Single-Image Shadow Removal(用于单幅图像阴影去除的自动曝光融合)
 - [论文地址](https://arxiv.org/abs/2103.01255)
 - [代码地址](https://github.com/tsingqguo/exposure-fusion-shadow-removal)<br><br>

<a name="10.图像翻译"></a>

## 10.图像翻译（Image Translation）
### Image-to-image Translation via Hierarchical Style Disentanglement
 - [paper](https://arxiv.org/abs/2103.01456)
 - [code](https://github.com/imlixinyang/HiSD)<br><br>

### Encoding in Style: a StyleGAN Encoder for Image-to-Image Translation(样式编码：用于图像到图像翻译的StyleGAN编码器)<br>
- [paper](https://arxiv.org/abs/2008.00951)
- [code](https://github.com/eladrich/pixel2style2pixel)
- [project](https://eladrich.github.io/pixel2style2pixel/)<br><br>

<a name="11.插帧"></a>
## 11.插帧（Frame Interpolation）
### FLAVR: Flow-Agnostic Video Representations for Fast Frame Interpolation
- Paper：[https://arxiv.org/abs/2012.08512](https://arxiv.org/abs/2012.08512)
- Code：[https://tarun005.github.io/FLAVR/Code](https://tarun005.github.io/FLAVR/Code)
- Homepage：[https://tarun005.github.io/FLAVR/](https://tarun005.github.io/FLAVR/)
### CDFI: Compression-driven Network Design for Frame Interpolation
- Code:[https://github.com/tding1/Compression-Driven-Frame-Interpolation](https://github.com/tding1/Compression-Driven-Frame-Interpolation)
### DeFMO: Deblurring and Shape Recovery of Fast Moving Objects
- Paper：[hhttps://arxiv.org/abs/2012.00595](https://arxiv.org/abs/2012.00595)
- Code：[https://github.com/rozumden/DeFMO](https://github.com/rozumden/DeFMO)

<a name="12.视频压缩"></a>
## 12.视频压缩（Video Compression）
### MetaSCI: Scalable and Adaptive Reconstruction for Video Compressive Sensing
- Paper：[https://arxiv.org/abs/2103.01786](https://arxiv.org/abs/2103.01786)
- Code：[https://github.com/xyvirtualgroup/MetaSCI-CVPR2021](https://github.com/xyvirtualgroup/MetaSCI-CVPR2021)

<a name="13.图像编辑"></a>
## 13.图像编辑(Image Edit)
### Anycost GANs for Interactive Image Synthesis and Editing(用于交互式图像合成和编辑的AnyCost Gans)<br>
- [paper](https://arxiv.org/abs/2103.03243)
- [code](https://github.com/mit-han-lab/anycost-gan)<br>

### Exploiting Spatial Dimensions of Latent in GAN for Real-time Image Editing（利用GAN中潜在的空间维度进行实时图像编辑）<br>


<a name="detection"/> 

## 检测

<a name="IOD"/> 

### 图像目标检测(Image Object Detection)

[1] [Semantic Relation Reasoning for Shot-Stable Few-Shot Object Detection(小样本目标检测的语义关系推理)](https://arxiv.org/abs/2103.01903)

[2] [UP-DETR: Unsupervised Pre-training for Object Detection with Transformers](https://arxiv.org/pdf/2011.09094.pdf)<br>
  - 解读：[无监督预训练检测器](https://www.zhihu.com/question/432321109/answer/1606004872)
  
[3] Positive-Unlabeled Data Purification in the Wild for Object Detection(野外检测对象的阳性无标签数据提纯)

[4] [General Instance Distillation for Object Detection(通用实例蒸馏技术在目标检测中的应用)](https://arxiv.org/abs/2103.02340)

[5] [Instance Localization for Self-supervised Detection Pretraining(自监督检测预训练的实例定位)](https://arxiv.org/pdf/2102.08318.pdf)
  - [code](https://github.com/limbo0000/InstanceLoc)

[6] Multiple Instance Active Learning for Object Detection（用于对象检测的多实例主动学习）<br>
[paper](https://github.com/yuantn/MIAL/raw/master/paper.pdf)|[code](https://github.com/yuantn/MIAL)

[7] Towards Open World Object Detection(开放世界中的目标检测)<br>
[paper](Towards Open World Object Detection)|[code](https://github.com/JosephKJ/OWOD)<br><br>

<a name="VOD"/> 

### 视频目标检测(Video Object Detection)

[3] Depth from Camera Motion and Object Detection(相机运动和物体检测的深度)<br>
[paper](https://arxiv.org/abs/2103.01468)<br><br>

[2] There is More than Meets the Eye: Self-Supervised Multi-Object Detection  and Tracking with Sound by Distilling Multimodal Knowledge(多模态知识提取的自监督多目标检测与有声跟踪)<br>
[paper](https://arxiv.org/abs/2103.01353)|[video](https://www.youtube.com/channel/UCRpM8k1GY3kD2TqCo_yKN3g)|[project](http://rl.uni-freiburg.de/research/multimodal-distill)<br><br>

[1] Dogfight: Detecting Drones from Drone Videos（从无人机视频中检测无人机）<br><br>
<a name="3DOD"/> 

### 三维目标检测(3D object detection)

[2] 3DIoUMatch: Leveraging IoU Prediction for Semi-Supervised 3D Object Detection(利用IoU预测进行半监督3D对象检测)<br>
[paper](https://arxiv.org/pdf/2012.04355.pdf)|[code](https://github.com/THU17cyz/3DIoUMatch)|[project](https://thu17cyz.github.io/3DIoUMatch/)|[video](https://youtu.be/nuARjhkQN2U)<br><br>

[1] Categorical Depth Distribution Network for Monocular 3D Object Detection(用于单目三维目标检测的分类深度分布网络)<br>
[paper](https://arxiv.org/abs/2103.01100)<br><br>

<a name="Activity Detection"/> 

### 动作检测(Activity Detection)

[1] Coarse-Fine Networks for Temporal Activity Detection in Videos<br>
[paper](https://arxiv.org/abs/2103.01302)<br><br>

<a name="AnomallyDetetionn"/> 

### 异常检测(Anomally Detetion)

[1] Multiresolution Knowledge Distillation for Anomaly Detection(用于异常检测的多分辨率知识蒸馏)<br>
[paper](https://arxiv.org/abs/2011.11108)<br><br>

<br>

<a name="ImageSegmentation"/> 

## 图像分割(Image Segmentation)

[2] Few-Shot Segmentation Without Meta-Learning: A Good Transductive Inference Is All You Need?<br>
[paper](https://arxiv.org/abs/2012.06166)|[code](https://github.com/mboudiaf/RePRI-for-Few-Shot-Segmentation)<br><br>

[1] PointFlow: Flowing Semantics Through Points for Aerial Image Segmentation(语义流经点以进行航空图像分割)<br><br>

<a name="PanopticSegmentation"/> 

### 全景分割(Panoptic Segmentation)

[2] Cross-View Regularization for Domain Adaptive Panoptic Segmentation(用于域自适应全景分割的跨视图正则化)<br>
[paper](https://arxiv.org/abs/2103.02584)<br><br>

[1] 4D Panoptic LiDAR Segmentation（4D全景LiDAR分割）<br>
[paper](https://arxiv.org/abs/2102.12472)<br><br>

<a name="SemanticSegmentation"/> 

### 语义分割(Semantic Segmentation)


[2] Towards Semantic Segmentation of Urban-Scale 3D Point Clouds: A Dataset, Benchmarks and Challenges(走向城市规模3D点云的语义分割：数据集，基准和挑战)<br>
[paper](https://arxiv.org/abs/2009.03137)|[code](https://github.com/QingyongHu/SensatUrban)<br><br>

[1] PLOP: Learning without Forgetting for Continual Semantic Segmentation（PLOP：学习而不会忘记连续的语义分割）<br>
[paper](https://arxiv.org/abs/2011.11390)<br><br>

<a name="InstanceSegmentation"/> 

### 实例分割(Instance Segmentation)

[1] End-to-End Video Instance Segmentation with Transformers(使用Transformer的端到端视频实例分割) <br>
[paper](https://arxiv.org/abs/2011.14503)
<br><br>

<a name="Matting"/> 

## 抠图(Matting)

[1] Real-Time High Resolution Background Matting<br>
[paper](https://arxiv.org/abs/2012.07810)|[code](https://github.com/PeterL1n/BackgroundMattingV2)|[project](https://grail.cs.washington.edu/projects/background-matting-v2/)|[video](https://youtu.be/oMfPTeYDF9g)<br><br>

<a name="Estimation"/> 

## 9. 估计(Estimation)

<a name="HumanPoseEstimation"/> 

### 人体姿态估计(Human Pose Estimation)


[2] CanonPose: Self-supervised Monocular 3D Human Pose Estimation in the Wild（野外自监督的单眼3D人类姿态估计）<br><br>

[1] PCLs: Geometry-aware Neural Reconstruction of 3D Pose with Perspective Crop Layers（具有透视作物层的3D姿势的几何感知神经重建）<br>
[paper](https://arxiv.org/abs/2011.13607)<br><br>

<a name="Flow/Pose/MotionEstimation"/> 

### 手势估计(Gesture Estimation)

[1] Camera-Space Hand Mesh Recovery via Semantic Aggregation and Adaptive  2D-1D Registration(基于语义聚合和自适应2D-1D配准的相机空间手部网格恢复)<br>
[paper](https://arxiv.org/pdf/2103.02845.pdf)|[code](https://github.com/SeanChenxy/HandMesh)<br><br>

<a name="Flow/Pose/MotionEstimation"/> 

### 光流/位姿/运动估计(Flow/Pose/Motion Estimation)

[3] GDR-Net: Geometry-Guided Direct Regression Network for Monocular 6D Object Pose Estimation(用于单眼6D对象姿态估计的几何引导直接回归网络)<br>
[paper](http://arxiv.org/abs/2102.12145)|[code](https://github.com/THU-DA-6D-Pose-Group/GDR-Net)<br><br>

[2] Robust Neural Routing Through Space Partitions for Camera Relocalization in Dynamic Indoor Environments(在动态室内环境中，通过空间划分的鲁棒神经路由可实现摄像机的重新定位)<br>
[paper](https://arxiv.org/abs/2012.04746)|[project](https://ai.stanford.edu/~hewang/)<br><br>

[1] MultiBodySync: Multi-Body Segmentation and Motion Estimation via 3D Scan Synchronization(通过3D扫描同步进行多主体分割和运动估计)<br>
[paper](https://arxiv.org/pdf/2101.06605.pdf)|[code](https://github.com/huangjh-pub/multibody-sync)<br><br>

<a name="Face"/> 

## 人脸(Face)

[5] Cross Modal Focal Loss for RGBD Face Anti-Spoofing(Cross Modal Focal Loss for RGBD Face Anti-Spoofing)
[paper](https://arxiv.org/abs/2103.00948)<br><br>

[4] When Age-Invariant Face Recognition Meets Face Age Synthesis: A  Multi-Task Learning Framework(当年龄不变的人脸识别遇到人脸年龄合成时：一个多任务学习框架)<br>
[paper](https://arxiv.org/abs/2103.01520)|[code](https://github.com/Hzzone/MTLFace)<br><br>

[3] Multi-attentional Deepfake Detection(多注意的深伪检测)<br>
[paper](https://arxiv.org/abs/2103.02406)<br><br>

[2] Image-to-image Translation via Hierarchical Style Disentanglement<br>
[paper](https://arxiv.org/abs/2103.01456)|[code](https://github.com/imlixinyang/HiSD)<br><br>

[1] A 3D GAN for Improved Large-pose Facial Recognition(用于改善大姿势面部识别的3D GAN)<br>
[paper](https://arxiv.org/pdf/2012.10545.pdf)<br><br>

<br>

<a name="ObjectTracking"/> 

## 目标跟踪(Object Tracking)

[4] HPS: localizing and tracking people in large 3D scenes from wearable sensors(通过可穿戴式传感器对大型3D场景中的人进行定位和跟踪)<br><br>

[3] Track to Detect and Segment: An Online Multi-Object Tracker(跟踪检测和分段：在线多对象跟踪器)<br>
[project](https://jialianwu.com/projects/TraDeS.html)|[video](https://www.youtube.com/watch?v=oGNtSFHRZJA)<br><br>

[2] Probabilistic Tracklet Scoring and Inpainting for Multiple Object Tracking(多目标跟踪的概率小波计分和修复)<br>
[paper](https://arxiv.org/abs/2012.02337)<br><br>

[1] Rotation Equivariant Siamese Networks for Tracking（旋转等距连体网络进行跟踪）<br>
[paper](https://arxiv.org/abs/2012.13078)<br><br>


<br>

<a name="Re-Identification"/> 

## 重识别

[1] Meta Batch-Instance Normalization for Generalizable Person Re-Identification(通用批处理人员重新标识的元批实例规范化)<br>
[paper](https://arxiv.org/abs/2011.14670)<br><br>

<br>

<a name="MedicalImaging"/> 

## 医学影像(Medical Imaging)

[5] DeepTag: An Unsupervised Deep Learning Method for Motion Tracking on  Cardiac Tagging Magnetic Resonance Images(一种心脏标记磁共振图像运动跟踪的无监督深度学习方法)<br>
[paper](https://arxiv.org/abs/2103.02772)<br><br>

[4] Multi-institutional Collaborations for Improving Deep Learning-based Magnetic Resonance Image Reconstruction Using Federated Learning(多机构协作改进基于深度学习的联合学习磁共振图像重建)<br>
[paper](https://arxiv.org/abs/2103.02148)|[code](https://github.com/guopengf/FLMRCM)<br><br>

[3] 3D Graph Anatomy Geometry-Integrated Network for Pancreatic Mass Segmentation, Diagnosis, and Quantitative Patient Management(用于胰腺肿块分割，诊断和定量患者管理的3D图形解剖学几何集成网络)<br><br>

[2] Deep Lesion Tracker: Monitoring Lesions in 4D Longitudinal Imaging Studies(深部病变追踪器：在4D纵向成像研究中监控病变)<br>
[paper](https://arxiv.org/abs/2012.04872)<br><br>

[1] Automatic Vertebra Localization and Identification in CT by Spine Rectification and Anatomically-constrained Optimization(通过脊柱矫正和解剖学约束优化在CT中自动进行椎骨定位和识别)<br>
[paper](https://arxiv.org/abs/2012.07947)<br><br>

<br>

<a name="NAS"/> 

## 神经网络架构搜索(NAS)

[3] AttentiveNAS: Improving Neural Architecture Search via Attentive(通过注意力改善神经架构搜索) <br>
[paper](https://arxiv.org/pdf/2011.09011.pdf)<br><br>

[2] ReNAS: Relativistic Evaluation of Neural Architecture Search(NAS predictor当中ranking loss的重要性)<br>
[paper](https://arxiv.org/pdf/1910.01523.pdf)<br><br>

[1] HourNAS: Extremely Fast Neural Architecture Search Through an Hourglass Lens（降低NAS的成本）<br>
[paper](https://arxiv.org/pdf/2005.14446.pdf)<br><br>

<br>

<a name="GAN"/> 

## GAN/生成式/对抗式(GAN/Generative/Adversarial)

[6] Anycost GANs for Interactive Image Synthesis and Editing(用于交互式图像合成和编辑的AnyCost Gans)<br>
[paper](https://arxiv.org/abs/2103.03243)|[code](https://github.com/mit-han-lab/anycost-gan)<br><br>

[5] Efficient Conditional GAN Transfer with Knowledge Propagation across Classes(高效的有条件GAN转移以及跨课程的知识传播)<br>
[paper](高效的有条件GAN转移以及跨课程的知识传播)|[code](http://github.com/mshahbazi72/cGANTransfer)<br><br>

[4] Exploiting Spatial Dimensions of Latent in GAN for Real-time Image Editing（利用GAN中潜在的空间维度进行实时图像编辑）<br><br>

[3] Hijack-GAN: Unintended-Use of Pretrained, Black-Box GANs(Hijack-GAN：意外使用经过预训练的黑匣子GAN)<br>
[paper](https://arxiv.org/pdf/2011.14107.pdf)<br><br>

[2] Encoding in Style: a StyleGAN Encoder for Image-to-Image Translation(样式编码：用于图像到图像翻译的StyleGAN编码器)<br>
[paper](https://arxiv.org/abs/2008.00951)|[code](https://github.com/eladrich/pixel2style2pixel)|[project](https://eladrich.github.io/pixel2style2pixel/)<br><br>

[1] A 3D GAN for Improved Large-pose Facial Recognition(用于改善大姿势面部识别的3D GAN)<br>
[paper](https://arxiv.org/pdf/2012.10545.pdf)<br><br>

<br>

<a name="3DVision"/> 

## 三维视觉(3D Vision)

[2] A Deep Emulator for Secondary Motion of 3D Characters(三维角色二次运动的深度仿真器)
[paper](https://arxiv.org/abs/2103.01261)

[1] 3D CNNs with Adaptive Temporal Feature Resolutions(具有自适应时间特征分辨率的3D CNN)<br>
[paper](https://arxiv.org/abs/2011.08652)<br><br>

<a name="3DPC"/> 

### 三维点云(3D Point Cloud)

[8] TPCN: Temporal Point Cloud Networks for Motion Forecasting(面向运动预测的时态点云网络)
[paper](https://arxiv.org/abs/2103.03067)|[code]()

[7] PointGuard: Provably Robust 3D Point Cloud Classification(可证明稳健的三维点云分类)<br>
[paper](https://arxiv.org/abs/2103.03046)<br><br>

[6] Towards Semantic Segmentation of Urban-Scale 3D Point Clouds: A Dataset, Benchmarks and Challenges(走向城市规模3D点云的语义分割：数据集，基准和挑战)<br>
[paper](https://arxiv.org/abs/2009.03137)|[code](https://github.com/QingyongHu/SensatUrban)<br><br>

[5] SpinNet: Learning a General Surface Descriptor for 3D Point Cloud Registration(SpinNet：学习用于3D点云注册的通用表面描述符)<br>
[paper](https://t.co/xIAWVGQeB2?amp=1)|[code](https://github.com/QingyongHu/SpinNet)<br><br>

[4] MultiBodySync: Multi-Body Segmentation and Motion Estimation via 3D Scan Synchronization(通过3D扫描同步进行多主体分割和运动估计)<br>
[paper](https://arxiv.org/pdf/2101.06605.pdf)|[code](https://github.com/huangjh-pub/multibody-sync)<br><br>

[3] Diffusion Probabilistic Models for 3D Point Cloud Generation(三维点云生成的扩散概率模型)<br>
[paper](https://arxiv.org/abs/2103.01458)|[code](https://github.com/luost26/diffusion-point-cloud)<br><br>

[2] Style-based Point Generator with Adversarial Rendering for Point Cloud Completion(用于点云补全的对抗性渲染基于样式的点生成器)<br>
[paper](https://arxiv.org/abs/2103.02535)

[1] PREDATOR: Registration of 3D Point Clouds with Low Overlap(预测器：低重叠的3D点云的注册)<br>
[paper](https://arxiv.org/pdf/2011.13005.pdf)|[code](https://github.com/ShengyuH/OverlapPredator)|[project](https://overlappredator.github.io/)<br><br>


<a name="3DReconstruction"/> 

### 三维重建(3D Reconstruction)

[1] PCLs: Geometry-aware Neural Reconstruction of 3D Pose with Perspective Crop Layers（具有透视作物层的3D姿势的几何感知神经重建）<br>
[paper](https://arxiv.org/abs/2011.13607)<br><br>

<br>

<a name="ModelCompression"/> 

## 模型压缩(Model Compression)

[2] Manifold Regularized Dynamic Network Pruning（动态剪枝的过程中考虑样本复杂度与网络复杂度的约束）<br><br>

[1] Learning Student Networks in the Wild（一种不需要原始训练数据的模型压缩和加速技术）<br>
[paper](https://arxiv.org/pdf/1904.01186.pdf)|[code](https://github.com/huawei-noah/DAFL)<br>
解读：[华为诺亚方舟实验室提出无需数据网络压缩技术](https://zhuanlan.zhihu.com/p/81277796)<br><br>

<a name="KnowledgeDistillation"/> 

### 知识蒸馏(Knowledge Distillation)

[3] General Instance Distillation for Object Detection(通用实例蒸馏技术在目标检测中的应用)<br>
[paper](https://arxiv.org/abs/2103.02340)<br><br>

[2] Multiresolution Knowledge Distillation for Anomaly Detection(用于异常检测的多分辨率知识蒸馏)<br>
[paper](https://arxiv.org/abs/2011.11108)<br><br>

[1] Distilling Object Detectors via Decoupled Features（前景背景分离的蒸馏技术） <br><br>

<br>

<a name="NNS"/> 

## 神经网络架构(Neural Network Structure)

[4] Coordinate Attention for Efficient Mobile Network Design(协调注意力以实现高效的移动网络设计)<br>
[paper](https://arxiv.org/abs/2103.02907)<br><br>

[3] Rethinking Channel Dimensions for Efficient Model Design(重新考虑通道尺寸以进行有效的模型设计)<br>
[paper](https://arxiv.org/abs/2007.00992)|[code](https://github.com/clovaai/rexnet)<br><br>

[2] Inverting the Inherence of Convolution for Visual Recognition（颠倒卷积的固有性以进行视觉识别）<br><br>

[1] RepVGG: Making VGG-style ConvNets Great Again<br>
[paper](https://arxiv.org/abs/2101.03697)|[code](https://github.com/megvii-model/RepVGG)<br>
解读：[RepVGG：极简架构，SOTA性能，让VGG式模型再次伟大](https://zhuanlan.zhihu.com/p/344324470)<br><br>

<a name="Transformer"/> 

### Transformer

[3] Transformer Interpretability Beyond Attention Visualization(注意力可视化之外的Transformer可解释性)<br>
[paper](https://arxiv.org/pdf/2012.09838.pdf)|[code](https://github.com/hila-chefer/Transformer-Explainability)<br><br>

[2] UP-DETR: Unsupervised Pre-training for Object Detection with Transformers<br>
[paper](https://arxiv.org/pdf/2011.09094.pdf)<br>
解读：[无监督预训练检测器](https://www.zhihu.com/question/432321109/answer/1606004872)<br><br>

[1] Pre-Trained Image Processing Transformer(底层视觉预训练模型)<br>
[paper](https://arxiv.org/pdf/2012.00364.pdf)<br><br>

<a name="GNN"/> 

### 图神经网络(GNN)

[2] Quantifying Explainers of Graph Neural Networks in Computational Pathology(计算病理学中图神经网络的量化解释器)<br>
[paper](https://arxiv.org/pdf/2011.12646.pdf)<br><br>

[1] Sequential Graph Convolutional Network for Active Learning(主动学习的顺序图卷积网络)<br>
[paper](https://arxiv.org/pdf/2006.10219.pdf)<br><br>


<br>

<a name="DataProcessing"/> 

## 数据处理(Data Processing)

<a name="DataAugmentation"/> 

### 数据增广(Data Augmentation)

[1] KeepAugment: A Simple Information-Preserving Data Augmentation(一种简单的保存信息的数据扩充)<br>
[paper](https://arxiv.org/pdf/2011.11778.pdf)<br><br>

<a name="BatchNormalization"/> 

### 归一化/正则化(Batch Normalization)

[3] Adaptive Consistency Regularization for Semi-Supervised Transfer Learning(半监督转移学习的自适应一致性正则化)<br>
[paper](https://arxiv.org/abs/2103.02193)|[code](https://github.com/SHI-Labs/Semi-Supervised-Transfer-Learning)

[2] Meta Batch-Instance Normalization for Generalizable Person Re-Identification(通用批处理人员重新标识的元批实例规范化)<br>
[paper](https://arxiv.org/abs/2011.14670)<br><br>

[1] Representative Batch Normalization with Feature Calibration（具有特征校准功能的代表性批量归一化）<br><br>

<a name="ImageClustering"/> 

### 图像聚类(Image Clustering)

[2] Improving Unsupervised Image Clustering With Robust Learning（通过鲁棒学习改善无监督图像聚类）<br>
[paper](https://arxiv.org/abs/2012.11150)|[code](https://github.com/deu30303/RUC)<br><br>

[1] Reconsidering Representation Alignment for Multi-view Clustering(重新考虑多视图聚类的表示对齐方式)<br><br>

<br>

<a name="ModelEvaluation"/> 

## 模型评估(Model Evaluation)

[1] Are Labels Necessary for Classifier Accuracy Evaluation?(测试集没有标签，我们可以拿来测试模型吗？)<br>
[paper](https://arxiv.org/abs/2007.02915)|[解读](https://zhuanlan.zhihu.com/p/328686799)<br><br>


<br>

<a name="Database"/> 

## 数据集(Database)


[2] Towards Semantic Segmentation of Urban-Scale 3D Point Clouds: A Dataset, Benchmarks and Challenges(走向城市规模3D点云的语义分割：数据集，基准和挑战)<br>
[paper](https://arxiv.org/abs/2009.03137)|[code](https://github.com/QingyongHu/SensatUrban)<br><br>

[1] Re-labeling ImageNet: from Single to Multi-Labels, from Global to Localized Labels（重新标记ImageNet：从单标签到多标签，从全局标签到本地标签）<br>
[paper](https://arxiv.org/abs/2101.05022)|[code](https://github.com/naver-ai/relabel_imagenet)<br><br>

<br>

<a name="ActiveLearning"/> 

## 主动学习(Active Learning)


[3] Vab-AL: Incorporating Class Imbalance and Difficulty with Variational Bayes for Active Learning<br>
[paper](https://github.com/yuantn/MIAL/raw/master/paper.pdf)|[code](https://github.com/yuantn/MIAL)<br><br>

[2] Multiple Instance Active Learning for Object Detection（用于对象检测的多实例主动学习）<br>
[paper](https://github.com/yuantn/MIAL/raw/master/paper.pdf)|[code](https://github.com/yuantn/MIAL)<br><br>

[1] Sequential Graph Convolutional Network for Active Learning(主动学习的顺序图卷积网络)<br>
[paper](https://arxiv.org/pdf/2006.10219.pdf)<br><br>

<br>

<a name="Few-shotLearning"/> 

## 小样本学习(Few-shot Learning)/零样本

[5] Few-Shot Segmentation Without Meta-Learning: A Good Transductive Inference Is All You Need?<br>
[paper](https://arxiv.org/abs/2012.06166)|[code](https://github.com/mboudiaf/RePRI-for-Few-Shot-Segmentation)<br><br>

[4] Counterfactual Zero-Shot and Open-Set Visual Recognition(反事实零射和开集视觉识别)<br>
[paper](https://arxiv.org/abs/2103.00887)|[code](https://github.com/yue-zhongqi/gcm-cf)<br><br>

[3] Semantic Relation Reasoning for Shot-Stable Few-Shot Object Detection(小样本目标检测的语义关系推理)<br>
[paper](https://arxiv.org/abs/2103.01903)<br><br>

[2] Few-shot Open-set Recognition by Transformation Consistency(转换一致性很少的开放集识别)<br><br>

[1] Exploring Complementary Strengths of Invariant and Equivariant Representations for Few-Shot Learning(探索少量学习的不变表示形式和等变表示形式的互补强度)<br>
[paper](https://arxiv.org/abs/2103.01315)|<br>

<br>

<a name="ContinualLearning"/> 

## 持续学习(Continual Learning/Life-long Learning)

[2] Rainbow Memory: Continual Learning with a Memory of Diverse Samples（不断学习与多样本的记忆）<br><br>

[1] Learning the Superpixel in a Non-iterative and Lifelong Manner(以非迭代和终身的方式学习超像素)<br><br>


<br><br>

<a name="VisualReasoning"/> 

## 视觉推理(Visual Reasoning)

[1] Transformation Driven Visual Reasoning(转型驱动的视觉推理)<br>
[paper](https://arxiv.org/pdf/2011.13160.pdf)|[code](https://github.com/hughplay/TVR)|[project](https://hongxin2019.github.io/TVR/)<br>


<br><br>

<a name="domain"/> 

## 迁移学习/domain/自适应](#domain)

[4] Continual Adaptation of Visual Representations via Domain Randomization and Meta-learning(通过域随机化和元学习对视觉表示进行连续调整)<br>
[paper](https://arxiv.org/abs/2012.04324)<br><br>

[3] Domain Generalization via Inference-time Label-Preserving Target Projections(基于推理时间保标目标投影的区域泛化)<br>
[paper](https://arxiv.org/abs/2103.01134)<br><br>

[2] MetaSCI: Scalable and Adaptive Reconstruction for Video Compressive  Sensing(可伸缩的自适应视频压缩传感重建)<br>
[paper](https://arxiv.org/abs/2103.01786)|[code](https://github.com/xyvirtualgroup/MetaSCI-CVPR2021)<br><br>

[1] FSDR: Frequency Space Domain Randomization for Domain Generalization(用于域推广的频域随机化)<br>
[paper](https://arxiv.org/abs/2103.02370)<br><br>

<br><br>

<a name="ContrastiveLearning)"/> 

## 对比学习(Contrastive Learning)

[1] Fine-grained Angular Contrastive Learning with Coarse Labels(粗标签的细粒度角度对比学习)<br>
[paper](https://arxiv.org/abs/2012.03515)<br><br>

<br><br>
<a name="ImageRetrieval"/> 

## 图像视频检索(Image Retrieval)

[1] QAIR: Practical Query-efficient Black-Box Attacks for Image Retrieval(实用的查询高效的图像检索黑盒攻击)<br>
[paper](https://arxiv.org/abs/2103.02927)<br><br>

<br><br>

<a name="100"/> 

## 暂无分类

Learning Asynchronous and Sparse Human-Object Interaction in Videos(视频中异步稀疏人-物交互的学习)<br>
[paper](https://arxiv.org/abs/2103.02758)<br><br>

Self-supervised Geometric Perception(自我监督的几何知觉)<br>
[paper](https://arxiv.org/abs/2103.03114)<br><br>

Quantifying Explainers of Graph Neural Networks in Computational Pathology(计算病理学中图神经网络的量化解释器)<br>
[paper](https://arxiv.org/pdf/2011.12646.pdf)<br><br>

Exploring Data-Efficient 3D Scene Understanding with Contrastive Scene Contexts(探索具有对比场景上下文的数据高效3D场景理解)<br>
[paper](http://arxiv.org/abs/2012.09165)|[project](http://sekunde.github.io/project_efficient)|[video](http://youtu.be/E70xToZLgs4)<br><br>

Data-Free Model Extraction(无数据模型提取)<br>
[paper](https://arxiv.org/abs/2011.14779)<br>

Patch-NetVLAD: Multi-Scale Fusion of Locally-Global Descriptors for Place Recognition(用于【位置识别】的局部全局描述符的【多尺度融合】)<br>
[paper](https://arxiv.org/pdf/2103.01486.pdf)|[code](https://github.com/QVPR/Patch-NetVLAD)<br><br>

Right for the Right Concept: Revising Neuro-Symbolic Concepts by Interacting with their Explanations(适用于正确概念的权利：通过可解释性来修正神经符号概念)<br>
[paper](https://arxiv.org/abs/2011.12854)<br><br>

Multi-Objective Interpolation Training for Robustness to Label Noise(多目标插值训练的鲁棒性)<br>
[paper](https://arxiv.org/abs/2012.04462)|[code](https://git.io/JI40X)<br><br>

VX2TEXT: End-to-End Learning of Video-Based Text Generation From Multimodal Inputs(【文本生成】VX2TEXT：基于视频的文本生成的端到端学习来自多模式输入)<br>
[paper](https://arxiv.org/pdf/2101.12059.pdf)<br><br>

Scan2Cap: Context-aware Dense Captioning in RGB-D Scans(【图像字幕】Scan2Cap：RGB-D扫描中的上下文感知密集字幕)
[paper](https://arxiv.org/abs/2012.02206)|[code](https://github.com/daveredrum/Scan2Cap)|[project](https://daveredrum.github.io/Scan2Cap/)|[video](https://youtu.be/AgmIpDbwTCY)<br><br>

Hierarchical and Partially Observable Goal-driven Policy Learning with  Goals Relational Graph(基于目标关系图的分层部分可观测目标驱动策略学习)<br>
[paper](https://arxiv.org/abs/2103.01350)<br><br>

ID-Unet: Iterative Soft and Hard Deformation for View Synthesis(视图合成的迭代软硬变形)<br>
[paper](https://arxiv.org/abs/2103.02264)<br><br>

PML: Progressive Margin Loss for Long-tailed Age Classification(【长尾分布】【图像分类】长尾年龄分类的累进边际损失)<br>
[paper](https://arxiv.org/abs/2103.02140)<br><br>

Diversifying Sample Generation for Data-Free Quantization（【图像生成】多样化的样本生成，实现无数据量化）<br>
[paper](https://arxiv.org/abs/2103.01049)<br><br>

Domain Generalization via Inference-time Label-Preserving Target Projections（通过保留推理时间的目标投影进行域泛化）<br>
[paper](https://arxiv.org/pdf/2103.01134.pdf)<br><br>

DeRF: Decomposed Radiance Fields（分解的辐射场）<br>
[project](https://ubc-vision.github.io/derf/)<br><br>

Densely connected multidilated convolutional networks for dense prediction tasks（【密集预测】密集连接的多重卷积网络，用于密集的预测任务）<br>
[paper](https://arxiv.org/abs/2011.11844)<br><br>

VirTex: Learning Visual Representations from Textual Annotations（【表示学习】从文本注释中学习视觉表示）<br>
[paper](https://arxiv.org/abs/2006.06666)|[code](https://github.com/kdexd/virtex)<br><br>

Weakly-supervised Grounded Visual Question Answering using Capsules（使用胶囊进行弱监督的地面视觉问答）<br><br>

FLAVR: Flow-Agnostic Video Representations for Fast Frame Interpolation（【视频插帧】FLAVR：用于快速帧插值的与流无关的视频表示）<br>
[paper](https://arxiv.org/pdf/2012.08512.pdf)|[code](https://tarun005.github.io/FLAVR/Code)|[project](https://tarun005.github.io/FLAVR/)<br><br>

Probabilistic Embeddings for Cross-Modal Retrieval（跨模态检索的概率嵌入）<br>
[paper](https://arxiv.org/abs/2101.05068)<br><br>

Self-supervised Simultaneous Multi-Step Prediction of Road Dynamics and Cost Map(道路动力学和成本图的自监督式多步同时预测)<br><br>

IIRC: Incremental Implicitly-Refined Classification(增量式隐式定义的分类)<br>
[paper](https://arxiv.org/abs/2012.12477)|[project](https://chandar-lab.github.io/IIRC/)<br><br>

Fair Attribute Classification through Latent Space De-biasing(通过潜在空间去偏的公平属性分类)<br>
[paper](https://arxiv.org/abs/2012.01469)|[code](https://github.com/princetonvisualai/gan-debiasing)|[project](https://princetonvisualai.github.io/gan-debiasing/)<br><br>

Information-Theoretic Segmentation by Inpainting Error Maximization(修复误差最大化的信息理论分割)<br>
[paper](https://arxiv.org/abs/2012.07287)<br><br>

UC2: Universal Cross-lingual Cross-modal Vision-and-Language Pretraining(【视频语言学习】UC2：通用跨语言跨模态视觉和语言预培训)<br><br>

Less is More: CLIPBERT for Video-and-Language Learning via Sparse Sampling(通过稀疏采样进行视频和语言学习)<br>
[paper](https://arxiv.org/pdf/2102.06183.pdf)|[code](https://github.com/jayleicn/ClipBERT)<br><br>

D-NeRF: Neural Radiance Fields for Dynamic Scenes(D-NeRF：动态场景的神经辐射场)<br>
[paper](https://arxiv.org/abs/2011.13961)|[project](https://www.albertpumarola.com/research/D-NeRF/index.html)<br><br>

Weakly Supervised Learning of Rigid 3D Scene Flow(刚性3D场景流的弱监督学习)<br>
[paper](https://arxiv.org/pdf/2102.08945.pdf)|[code](https://arxiv.org/pdf/2102.08945.pdf)|[project](https://3dsceneflow.github.io/)<br><br>

<br>

<a name="2"/> 

## 2. CVPR2021 Oral

[23] Self-supervised Geometric Perception(自我监督的几何知觉)<br>
[paper](https://arxiv.org/abs/2103.03114)<br><br>

[22] DeepTag: An Unsupervised Deep Learning Method for Motion Tracking on  Cardiac Tagging Magnetic Resonance Images(一种心脏标记磁共振图像运动跟踪的无监督深度学习方法)<br>
[paper](https://arxiv.org/abs/2103.02772)<br><br>

[21] Modeling Multi-Label Action Dependencies for Temporal Action Localization(为时间动作本地化建模多标签动作相关性)<br>
[paper](https://arxiv.org/pdf/2103.03027.pdf)<br><br>

[20] HPS: localizing and tracking people in large 3D scenes from wearable sensors(通过可穿戴式传感器对大型3D场景中的人进行定位和跟踪)<br><br>

[19] Real-Time High Resolution Background Matting(实时高分辨率背景抠像)<br>
[paper](https://arxiv.org/abs/2012.07810)|[code](https://github.com/PeterL1n/BackgroundMattingV2)|[project](https://grail.cs.washington.edu/projects/background-matting-v2/)|[video](https://youtu.be/oMfPTeYDF9g)<br><br>

[18] Exploring Data-Efficient 3D Scene Understanding with Contrastive Scene Contexts(探索具有对比场景上下文的数据高效3D场景理解)<br>
[paper](http://arxiv.org/abs/2012.09165)|[project](http://sekunde.github.io/project_efficient)|[video](http://youtu.be/E70xToZLgs4)<br><br>

[17] Robust Neural Routing Through Space Partitions for Camera Relocalization in Dynamic Indoor Environments(在动态室内环境中，通过空间划分的鲁棒神经路由可实现摄像机的重新定位)<br>
[paper](https://arxiv.org/abs/2012.04746)|[project](https://ai.stanford.edu/~hewang/)<br><br>

[16] MultiBodySync: Multi-Body Segmentation and Motion Estimation via 3D Scan Synchronization(通过3D扫描同步进行多主体分割和运动估计)<br>
[paper](https://arxiv.org/pdf/2101.06605.pdf)|[code](https://github.com/huangjh-pub/multibody-sync)<br><br>

[15] Categorical Depth Distribution Network for Monocular 3D Object Detection(用于单目三维目标检测的分类深度分布网络)<br>
[paper](https://arxiv.org/abs/2103.01100)<br><br>

[14] PatchmatchNet: Learned Multi-View Patchmatch Stereo(学习多视图立体声)<br>
[paper](https://arxiv.org/abs/2012.01411)|[code](https://github.com/FangjinhuaWang/PatchmatchNet)

[13] Continual Adaptation of Visual Representations via Domain Randomization and Meta-learning(通过域随机化和元学习对视觉表示进行连续调整)<br>
[paper](https://arxiv.org/abs/2012.04324)<br><br>

[12] Single-Stage Instance Shadow Detection with Bidirectional Relation Learning(具有双向关系学习的单阶段实例阴影检测)<br><br>

[11] Neural Geometric Level of Detail:Real-time Rendering with Implicit 3D Surfaces(神经几何细节水平：隐式3D曲面的实时渲染)<br>
[paper](https://arxiv.org/abs/2101.10994)|[code](https://github.com/nv-tlabs/nglod)|[project](https://nv-tlabs.github.io/nglod/)<br><br>

[9] PREDATOR: Registration of 3D Point Clouds with Low Overlap(预测器：低重叠的3D点云的注册)<br>
[paper](https://arxiv.org/pdf/2011.13005.pdf)|[code](https://github.com/ShengyuH/OverlapPredator)|[project](https://overlappredator.github.io/)<br><br>

[8] Domain Generalization via Inference-time Label-Preserving Target Projections(通过保留推理时间的目标投影进行域泛化)<br>
[paper](https://arxiv.org/abs/2103.01134)<br><br>

[7] Neural Deformation Graphs for Globally-consistent Non-rigid Reconstruction(全局一致的非刚性重建的神经变形图)<br>
[paper](https://arxiv.org/abs/2012.01451)|[project](https://aljazbozic.github.io/neural_deformation_graphs/)|[video](https://youtu.be/vyq36eFkdWo)<br><br>

[6] Fine-grained Angular Contrastive Learning with Coarse Labels(粗标签的细粒度角度对比学习)<br>
[paper](https://arxiv.org/abs/2012.03515)<br><br>

[5] Less is More: CLIPBERT for Video-and-Language Learning via Sparse Sampling(通过稀疏采样进行视频和语言学习)<br>
[paper](https://arxiv.org/pdf/2102.06183.pdf)|[code](https://github.com/jayleicn/ClipBERT)<br><br>

[4] Cross-View Regularization for Domain Adaptive Panoptic Segmentation(用于域自适应全景分割的跨视图正则化)<br>
[paper](https://arxiv.org/abs/2103.02584)<br><br>

[3] Image-to-image Translation via Hierarchical Style Disentanglement(通过分层样式分解实现图像到图像的翻译)<br>
[paper](https://arxiv.org/abs/2103.01456)|[code](https://github.com/imlixinyang/HiSD)<br><br>

[2] Towards Open World Object Detection(开放世界中的目标检测)<br>
[paper](Towards Open World Object Detection)|[code](https://github.com/JosephKJ/OWOD)<br><br>

[1] End-to-End Video Instance Segmentation with Transformers(使用Transformer的端到端视频实例分割) <br>
[paper](https://arxiv.org/abs/2011.14503)<br><br>

<br>

<a name="Reading"/> 
## 3. CVPR2021的论文解读

* [CVPR 2021 | GFLV2：目标检测良心技术，无Cost涨点!](https://zhuanlan.zhihu.com/p/313684358)
* [CVPR 2021 | 上交和国科大提出DCL：旋转目标检测新方法](https://zhuanlan.zhihu.com/p/354373013)
* [CVPR 2021 | 涨点神器！IC-Conv：使用高效空洞搜索的Inception卷积，全方位提升！]()
* [CVPR 2021 Oral | 层次风格解耦：人脸多属性篡改终于可控了！](https://zhuanlan.zhihu.com/p/354258056)
* [CVPR 2021 | Transformer进军low-level视觉！北大华为等提出预训练模型IPT]()
* 

<br>


