# Awesome-Unsupervised-Semantic-Segmentation 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a summary of recent unsupervised semantic segmentation methods.

## PaperWithCode

[Unsupervised Semantic Segmentation](https://paperswithcode.com/task/unsupervised-semantic-segmentation)

[Large-Scale Unsupervised Semantic Segmentation](https://paperswithcode.com/paper/large-scale-unsupervised-semantic)

## Datasets

[ImageNet-S](https://github.com/LUSSeg/ImageNet-S/blob/main/README.md)

| Dataset | category | train   | val   | test  |
|------------------|----------|---------|-------|-------|
| ImageNet-S 50  | 50       | 64431   | 752   | 1682  |
| ImageNet-S 300 | 300      | 384862  | 4097  | 9088  |
| ImageNet-S        | 919      | 1183322 | 12419 | 27423 |

## 2023
Leveraging Hidden Positives for Unsupervised Semantic Segmentation


| Title| Abbreviation| Published | Dataset| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |
| Leveraging Hidden Positives for Unsupervised Semantic Segmentation | HP | CVPR2023 | COCO, Cityscapes, Potsdam | [pytorch](https://github.com/hynnsk/HP) | [paper](https://arxiv.org/pdf/2303.15014v1.pdf) |
| ACSeg: Adaptive Conceptualization for Unsupervised Semantic Segmentation | ACSeg | CVPR2023 | VOC, COCO | | [paper](https://arxiv.org/abs/2210.05944) |
| Unsupervised Semantic Segmentation with Self-supervised Object-centric Representation | COMUS | ICLR2023 | VOC, COCO | | [paper](https://arxiv.org/abs/2207.05027) |

## 2022

| Title| Abbreviation| Published | Dataset| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |
| Large-scale Unsupervised Semantic Segmentation | PASS | TPAMI2022 | ImageNet-S | [pytorch](https://github.com/LUSSeg/PASS) \| [jittor]() | [paper](https://arxiv.org/abs/2106.03149) |
| Discovering Object Masks with Transformers for Unsupervised Semantic Segmentation | MaskDistill | arxiv | VOC, COCO | | [paper](https://arxiv.org/abs/2206.06363) |
| Self-Supervised Learning of Object Parts for Semantic Segmentation | Leopart | CVPR2022 | VOC, COCO, ImageNet-100 | [pytorch](https://github.com/MkuuWaUjinga/leopart) | [paper](https://arxiv.org/abs/2204.13101) |
| Deep Spectral Methods: A Surprisingly Strong Baseline for Unsupervised Semantic Segmentation and Localization | - | CVPR2022 | VOC, COCO | [pytorch]() | [paper](https://arxiv.org/abs/2205.07839) |
| Unsupervised Hierarchical Semantic Segmentation with Multiview Cosegmentation and Clustering Transformer | HSG | CVPR2022 | VOC, COCO, Cityscapes, Potsdam, KITTI-STEP | [pytorch](https://github.com/twke18/HSG) | [paper](https://arxiv.org/abs/2204.11432) |
| TransFGU: A Top-down Approach to Fine-Grained Unsupervised Semantic Segmentation | TransFGU | ECCV2022 | VOC, COCO, Cityscapes, LIP | [pytorch](https://github.com/damo-cv/TransFGU) | [paper](https://arxiv.org/pdf/2112.01515.pdf) |
| Unsupervised Semantic Segmentation by Distilling Feature Correspondences | STEGO | ICLR2022 | COCO, Cityscapes | [pytorch](https://github.com/mhamilton723/STEGO) | [paper](https://arxiv.org/abs/2203.08414) |
| Unsupervised Image Semantic Segmentation through Superpixels and Graph Neural Networks | SGSeg | arxiv | COCO, Potsdam | | [paper](https://arxiv.org/abs/2210.11810) |
| Rethinking Alignment and Uniformity in Unsupervised Image Semantic Segmentation | SAN | arxiv | COCO, Cityscapes, Potsdam | | [paper](https://arxiv.org/abs/2211.14513) |
| Fully Self-Supervised Learning for Semantic Segmentation | FS4 | arxiv | COCO | | [paper](https://arxiv.org/abs/2202.11981) |

## 2021

| Title| Abbreviation| Published | Dataset| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |
| Unsupervised Semantic Segmentation by Contrasting Object Mask Proposals | MaskContrast | ICCV2021 | VOC | [pytorch](https://github.com/wvangansbeke/Unsupervised-Semantic-Segmentation) | [paper](https://arxiv.org/abs/2102.06191) |
| PiCIE: Unsupervised Semantic Segmentation using Invariance and Equivariance in Clustering | PICIE | CVPR2021 | COCO, Cityscapes | [pytorch](https://github.com/janghyuncho/PiCIE) | [paper](https://arxiv.org/abs/2103.17070) |
| InfoSeg: Unsupervised Semantic Image Segmentation with Mutual Information Maximization | InfoSeg | GCPR2021 | COCO, Potsdam | | [paper](https://arxiv.org/abs/2110.03477) |
| Unsupervised Image Segmentation by Mutual Information Maximization and Adversarial Regularization | InMARS | RA-L2021 | COCO, Potsdam | | [paper](https://arxiv.org/abs/2107.00691) |

## 2020

| Title| Abbreviation| Published | Dataset| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |
| Self-Supervised Visual Representation Learning from Hierarchical Grouping | - | NIPS2020 | VOC, COCO | | [paper](https://proceedings.neurips.cc/paper/2020/hash/c1502ae5a4d514baec129f72948c266e-Abstract.html) |
| Autoregressive Unsupervised Image Segmentation | AC | ECCV2020 | COCO, Potsdam | [pytorch](https://github.com/Max-Manning/autoregunsupseg) | [paper](https://arxiv.org/abs/2007.08247) |

## 2019

| Title| Abbreviation| Published | Dataset| CODE | PDF             |
| :---------| :------------------------------:| :----------------------: | :-------------------------------------------------------------------------:| :--------------------: |  :--------------- |
| Invariant Information Clustering for Unsupervised Image Classification and Segmentation | IIC | ICCV2019 | COCO, Potsdam | [pytorch](https://github.com/xu-ji/IIC) | [paper](https://arxiv.org/abs/1807.06653) |
| SegSort: Segmentation by Discriminative Sorting of Segments | SegSort | ICCV2019 | VOC | [tensorflow](https://github.com/jyhjinghwang/segsort) | [paper](https://arxiv.org/abs/1910.06962) |
