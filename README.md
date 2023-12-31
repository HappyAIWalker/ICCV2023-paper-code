# ICCV2023-paper-code
![](./assets/aiwalker.png)

持续更新ICCV2023论文、代码等信息，欢迎关注AIWalker。主要聚焦以下几个方向，更多CV/AI资料可添加AIWalker助手【AIWalker-zhushou】获取(可扫描底部二维码)。


- [Backbone](#Backbone)
- [Detection](#detection)
- [Segmentation](#segmentation)
- [Knowledge Distillation](#knowledge-distillation)
- [Diffusion](#Diffusion)
- [Restoration](#Restoration)
- [Super-Resolution](#super-resolution)
- [Deblurring](#deblurring)
- [低光图像增强](#low-light-image-enhance)
- [IQA/IAA](#iqaiaa)
- [数据集](#dataset)
- ....


## Backbone
ElasticViT: Conflict-aware Supernet Training for Deploying Fast Vision
Transformer on Diverse Mobile Devices
- Paper: https://arxiv.org/pdf/2303.09730.pdf


Rethinking Mobile Block for Efficient Attention-based Models  
- Paper: https://arxiv.org/abs/2301.01146
- Code: https://github.com/zhangzjn/EMO

UniFormerV2: Spatiotemporal Learning by Arming Image ViTs with Video UniFormer
- Paper: https://arxiv.org/abs/2211.09552
- Code: https://github.com/OpenGVLab/UniFormerV2

Unmasked Teacher: Towards Training-Efficient Video Foundation Models
- Paper: https://arxiv.org/abs/2303.16058
- Code: https://github.com/OpenGVLab/unmasked_teacher

A Unified Continual Learning Framework with General Parameter-Efficient Tuning
- Paper: https://arxiv.org/abs/2303.10070
- Code: https://github.com/gqk/LAE

Scale-Aware Modulation Meet Transformer
- Paper: https://arxiv.org/abs/2307.08579
- Code: https://github.com/AFeng-x/SMT

Improving Zero-Shot Generalization for CLIP with Synthesized Prompts
- Paper: https://arxiv.org/abs/2307.07397
- Code: https://github.com/mrflogs/SHIP

DreamTeacher: Pretraining Image Backbones with Deep Generative Models
- Paper: https://arxiv.org/abs/2307.07487
- Home: https://research.nvidia.com/labs/toronto-ai/DreamTeacher/

ShiftNAS: Improving One-shot NAS via Probability Shift
- Paper: https://arxiv.org/abs/2307.08300
- Code: https://github.com/bestfleer/ShiftNAS

MULLER: Multilayer Laplacian Resizer for Vision
- Paper: https://arxiv.org/pdf/2304.02859.pdf

FLatten Transformer: Vision Transformer with Focused Linear Attention
- Paper: TODO
- Code: https://github.com/LeapLabTHU/FLatten-Transformer

Not All Features Matter:Enhancing Few-shot CLIP with Adaptive Prior 
- Paper: https://arxiv.org/abs/2304.01195
- Code: https://github.com/yangyangyang127/APE

Tuning Pre-trained Model via Moment Probing
- Paper: https://arxiv.org/abs/2307.11342
- Code: https://github.com/mingzeG/Moment-Probing

Strip-MLP: Efficient Token Interaction for Vision MLP
- Paper: https://arxiv.org/pdf/2307.11458.pdf
- Code: https://github.com/Med-Process/Strip_MLP

Adaptive Frequency Filters As Efficient Global Token Mixers
- Paper: https://arxiv.org/abs/2307.14008

Learning Concise and Descriptive Attributes for Visual Recognition
- Paper: https://arxiv.org/abs/2308.03685

## Detection 
FemtoDet: an object detection baseline for energy versus performance tradeoffs
- Paper: https://arxiv.org/pdf/2301.06719.pdf
- Code: https://github.com/yh-pengtu/FemtoDet

Group DETR: Fast DETR Training with Group-Wise One-to-Many Assignment
- Paper: https://arxiv.org/pdf/2207.13085.pdf
- Code: https://github.com/Atten4Vis/GroupDETR

Large Selective Kernel Network for Remote Sensing Object Detection
- Paper: https://arxiv.org/abs/2303.09030
- Code: https://github.com/zcablii/LSKNet

DiffusionDet: Diffusion Model for Object Detection
- Paper: https://arxiv.org/abs/2211.09788
- Code: https://github.com/ShoufaChen/DiffusionDet

DETRs with Collaborative Hybrid Assignments Training
- Paper: https://arxiv.org/pdf/2211.12860.pdf
- Code: https://github.com/Sense-X/Co-DETR

MIMDet: Unleashing Vanilla Vision Transformer with Masked Image Modeling for Object Detection
- Paper: https://arxiv.org/abs/2204.02964
- Code: https://github.com/hustvl/MIMDet

Detection Transformer with Stable Matching
- Paper: https://arxiv.org/abs/2304.04742
- Code: https://github.com/IDEA-Research/Stable-DINO

Random Boxes Are Open-world Object Detectors
- Paper: https://arxiv.org/abs/2307.08249
- Code: https://github.com/scuwyh2000/RandBox

AlignDet: Aligning Pre-training and Fine-tuning in Object Detection
- Paper: https://arxiv.org/abs/2307.11077
- Home: https://liming-ai.github.io/AlignDet

Cascade-DETR: Delving into High-Quality Universal Object Detection
- Paper: https://arxiv.org/abs/2307.11035
- Code: https://github.com/SysCV/cascade-detr

Deep Directly-Trained Spiking Neural Networks for Object Detection
- Paper: https://arxiv.org/abs/2307.11411

COCO-O: A Benchmark for Object Detectors under Natural Distribution Shifts
- Paper: https://arxiv.org/abs/2307.12730
- Code: https://github.com/alibaba/easyrobust/tree/main/benchmarks/coco_o

Less is More: Focus Attention for Efficient DETR
- Ppaer: https://arxiv.org/abs/2307.12612
- Code: https://github.com/huawei-noah/noah-research/tree/master/Focus-DETR

Spatial Self-Distillation for Object Detection with Inaccurate Bounding Boxes
- Paper: https://arxiv.org/abs/2307.12101
- Code: https://github.com/ucas-vg/PointTinyBenchmark/tree/SSD-Det

RecursiveDet: End-to-End Region-based Recursive Object Detection
- Paper: https://arxiv.org/abs/2307.13619
- Code: https://github.com/bravezzzzzz/RecursiveDet

## Segmentation
Segment Anything  
- Home: https://segment-anything.com/
- Paper: https://arxiv.org/abs/2304.02643
- Code: https://github.com/facebookresearch/segment-anything

SegGPT: Segmenting Everything in Context
- Paper: https://arxiv.org/abs/2304.03284
- Code: https://github.com/baaivision/Painter

VLPart: Going Denser with Open-Vocabulary Part Segmentation
- Paper: https://arxiv.org/abs/2305.11173
- Code: https://github.com/facebookresearch/VLPart

Referring Image Segmentation Using Text Supervision
- Paper:
- Code: https://github.com/fawnliu/WRIS_ICCV2023

EfficientViT: Lightweight Multi-Scale Attention for On-Device Semantic Segmentation 
- Paper: https://arxiv.org/pdf/2205.14756.pdf
- Code: https://github.com/mit-han-lab/efficientvit

A Simple Framework for Open-Vocabulary Segmentation and Detection
- Paper: https://arxiv.org/pdf/2303.08131.pdf
- Code: https://github.com/IDEA-Research/OpenSeeD

Multi-granularity Interaction Simulation for Unsupervised Interactive Segmentation
- Paper: https://arxiv.org/abs/2303.13399

Dynamic Snake Convolution based on Topological Geometric Constraints for Tubular Structure Segmentation
- Paper: https://arxiv.org/abs/2307.08388

OnlineRefer: A Simple Online Baseline for Referring Video Object Segmentation
- Paper: https://arxiv.org/abs/2307.09356
- Code: https://github.com/wudongming97/OnlineRefer

Bridging Vision and Language Encoders: Parameter-Efficient Tuning for Referring Image Segmentation
- Paper: https://arxiv.org/abs/2307.11545
- Code: https://github.com/kkakkkka/ETRIS

Exploring Transformers for Open-world Instance Segmentation
- Code: https://arxiv.org/abs/2308.04206


## Knowledge Distillation
From Knowledge Distillation to Self-Knowledge Distillation: A Unified Approach with Normalized Loss and Customized Soft Labels
- Paper: https://arxiv.org/abs/2303.13005
- Code: https://github.com/yzd-v/cls_KD

DOT: A Distillation-Oriented Trainer
- Paper: https://arxiv.org/abs/2307.08436

Cumulative Spatial Knowledge Distillation for Vision Transformers
- Paper: https://arxiv.org/abs/2307.08500

Class-relation Knowledge Distillation for Novel Class Discovery
- Paper: https://arxiv.org/abs/2307.09158
- Code: https://github.com/kleinzcy/Cr-KD-NCD

EMQ: Evolving Training-free Proxies for Automated Mixed Precision Quantization
- Code: https://github.com/lilujunai/EMQ-series

Rethinking Data Distillation: Do Not Overlook Calibration
- Paper: https://arxiv.org/abs/2307.12463

## Diffusion
MasaCtrl: Tuning-Free Mutual Self-Attention Control for Consistent Image Synthesis and Editing
- Paper: https://arxiv.org/abs/2304.08465
- Home: https://ljzycmd.github.io/projects/MasaCtrl/

Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation
- Paper: https://arxiv.org/abs/2212.11565
- Code: https://github.com/showlab/Tune-A-Video

FateZero: Fusing Attentions for Zero-shot Text-based Video Editing
- Paper: https://arxiv.org/abs/2303.09535
- Code: https://github.com/ChenyangQiQi/FateZero

Expressive Text-to-Image Generation with Rich Text
- Paper: https://arxiv.org/abs/2304.06720
- Home: https://rich-text-to-image.github.io/

Ablating Concepts in Text-to-Image Diffusion Models
- Paper: https://arxiv.org/abs/2303.13516
- Home: https://www.cs.cmu.edu/~concept-ablation/
- Code: https://github.com/nupurkmr9/concept-ablation

Evaluating Data Attribution for Text-to-Image Models
- Paper: https://arxiv.org/abs/2306.09345
- Home: https://peterwang512.github.io/GenDataAttribution/
- Code: https://github.com/peterwang512/GenDataAttribution

Masked Diffusion Transformer is a Strong Image Synthesizer
- Paper: TODO
- Code: TODO

SVDiff: Compact Parameter Space for Diffusion Fine-tuning
- paper: https://arxiv.org/abs/2303.11305

BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion
- Paper: https://arxiv.org/abs/2307.10816

TF-ICON: Diffusion-Based Training-Free Cross-Domain Image Composition
- Code: https://github.com/Shilin-LU/TF-ICON



## Depth 
Neural Video Depth Stabilizer
- Paper: https://arxiv.org/abs/2307.08695

Kick Back & Relax: Learning to Reconstruct the World by Watching SlowTV
- Paper: https://arxiv.org/abs/2307.10713
- Code: https://github.com/jspenmar/slowtv_monodepth

MAMo: Leveraging Memory and Attention for Monocular Video Depth Estimation
- Paper: https://arxiv.org/abs/2307.14336

Uncertainty Guided Adaptive Warping for Robust and Efficient Stereo Matching
- Paper: https://arxiv.org/abs/2307.14071

VideoFlow: Exploiting Temporal Cues for Multi-frame Optical Flow Estimation
- Paper: https://arxiv.org/abs/2303.08340
- Code: https://github.com/XiaoyuShi97/VideoFlow

Learning Depth Estimation for Transparent and Mirror Surfaces
- Paper: https://arxiv.org/pdf/2307.15052.pdf

## Restoration
Adaptive Nonlinear Latent Transformation for Conditional Face Editing
- Paper: https://arxiv.org/abs/2307.07790
- Code: https://github.com/Hzzone/AdaTrans

Towards Authentic Face Restoration with Iterative Diffusion Models and Beyond
- Paper: https://arxiv.org/abs/2307.08996

Diffir: Efficient diffusion model for image restoration
- Paper: https://arxiv.org/abs/2303.09472
- Code: https://github.com/Zj-BinXia/DiffIR

Physics-Driven Turbulence Image Restoration with Stochastic Refinement
- Paper: https://arxiv.org/pdf/2307.10603
- Code: https://github.com/VITA-Group/PiRN

Learning Image-Adaptive Codebooks for Class-Agnostic Image Restoration
- Paper: https://arxiv.org/abs/2306.06513
- Code: https://github.com/kechunl/AdaCode

Under-Display Camera Image Restoration with Scattering Effect
- Paper: https://arxiv.org/abs/2308.04163
- Code: https://github.com/NamecantbeNULL/SRUDC

From Sky to the Ground: A Large-scale Benchmark and Simple Baseline Towards Real Rain Removal
- Paper: https://arxiv.org/abs/2308.03867

GlowGAN: Unsupervised Learning of HDR Images from LDR Images in the Wild
-Paper: https://arxiv.org/pdf/2211.12352.pdf


## Super-Resolution
SRFormer: Permuted Self-Attention for Single Image Super-Resolution
- Paper: https://arxiv.org/abs/2303.09735
- Code: https://github.com/HVision-NKU/SRFormer

SAFMN: Spatially-Adaptive Feature Modulation for Efficient Image Super-Resolution
- Paper: https://arxiv.org/pdf/2302.13800.pdf
- Code: https://github.com/sunny2109/SAFMN

DLGSANet: Lightweight Dynamic Local and Global Self-Attention Network for Image Super-Resolution
- Paper: https://arxiv.org/pdf/2301.02031.pdf
- Code: https://github.com/NeonLeexiang/DLGSANet

Dual Aggregation Transformer for Image Super-Resolution
- Paper: https://arxiv.org/abs/2308.03364
- Code: https://github.com/zhengchen1999/DAT

A Benchmark for Chinese-English Scene Text Image Super-resolution
- Paper: https://arxiv.org/abs/2308.03262
- Code:https://github.com/mjq11302010044/Real-CE

## Deblurring
Multi-scale Residual Low-Pass Filter Network for Image Deblurring
- Paper: TODO
- Code: TODO


## Low-light Image Enhance
Implicit Neural Representation for Cooperative Low-light Image Enhancement  
- Paper: https://arxiv.org/abs/2303.11722
- Code: https://github.com/Ysz2022/NeRCo

Iterative Prompt Learning for Unsupervised Backlit Image Enhancement
- Paper: https://arxiv.org/abs/2303.17569
- Home: https://zhexinliang.github.io/CLIP_LIT_page/

ExposureDiffusion: Learning to Expose for Low-light Image Enhancement
- Paper: https://arxiv.org/abs/2307.07710

## IQA/IAA
Delegate Transformer for Image Color Aesthetics Assessment
- Paper: TODO
- Code: https://github.com/woshidandan/Image-Color-Aesthetics-Assessment

Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives
- Paper: https://arxiv.org/abs/2211.04894
- Code: https://github.com/VQAssessment/DOVER

On the Effectiveness of Spectral Discriminators for Perceptual Quality Improvement
- Paper: https://arxiv.org/abs/2307.12027
- Code: https://github.com/Luciennnnnnn/DualFormer

## Other
Fast Full-frame Video Stabilization with Iterative Optimization
- Paper: https://arxiv.org/abs/2307.12774


## Dataset
LPFF: A Portrait Dataset for Face Generators Across Large Poses
- Paper: https://arxiv.org/abs/2303.14407
- Code: https://github.com/oneThousand1000/LPFF-dataset


## AIWalker-小助手
![](./assets/zhushou.png)