# M3I Pre-training

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-all-in-one-pre-training-via/object-detection-on-coco)](https://paperswithcode.com/sota/object-detection-on-coco?p=towards-all-in-one-pre-training-via)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-all-in-one-pre-training-via/object-detection-on-coco-minival)](https://paperswithcode.com/sota/object-detection-on-coco-minival?p=towards-all-in-one-pre-training-via)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-all-in-one-pre-training-via/object-detection-on-lvis-v1-0-minival)](https://paperswithcode.com/sota/object-detection-on-lvis-v1-0-minival?p=towards-all-in-one-pre-training-via)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-all-in-one-pre-training-via/semantic-segmentation-on-ade20k)](https://paperswithcode.com/sota/semantic-segmentation-on-ade20k?p=towards-all-in-one-pre-training-via) [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/towards-all-in-one-pre-training-via/image-classification-on-imagenet)](https://paperswithcode.com/sota/image-classification-on-imagenet?p=towards-all-in-one-pre-training-via)

This repository is an official implementation of the paper [Towards All-in-one Pre-training via Maximizing Multi-modal Mutual Information](https://arxiv.org/abs/2211.09807).

By [Weijie Su](https://scholar.google.com/citations?user=ECDe6IIAAAAJ&hl=en), [Xizhou Zhu](https://scholar.google.com/citations?user=02RXI00AAAAJ&hl=en), [Chenxin Tao](https://scholar.google.com/citations?user=sXHFIBkAAAAJ&hl=en), [Lewei Lu](https://scholar.google.com/citations?user=zdgKJXIAAAAJ&hl=en), [Bin Li](http://staff.ustc.edu.cn/~binli/), [Gao Huang](http://www.gaohuang.net/), [Yu Qiao](https://scholar.google.com/citations?user=gFtI-8QAAAAJ&hl=en), [Xiaogang Wang](https://scholar.google.com/citations?user=-B5JgjsAAAAJ&hl=en), [Jie Zhou](https://scholar.google.com/citations?user=6a79aPwAAAAJ&hl=en), [Jifeng Dai](https://jifengdai.org/).

Code will be available.

## Introduction

**M**aximizing **M**ulti-modal **M**utual **I**nformation Pre-training (**M3I Pre-training**), initially described in [arxiv](https://arxiv.org/abs/2211.09807), is a simple yet effective one-stage pre-training paradigm. It can integrate existing pre-training methods (supervised pre-training, weakly-supervised pre-training and self-supervised pre-training) under an unified mutual information perspective and maintain all desired properties through a single-stage pre-training. Notably, we successfully pre-train a 1B model ([InternImage-H](https://arxiv.org/abs/2211.05778)) with M3I Pre-training and achieve new record `65.4 mAP` on COCO detection test-dev, `62.5 mAP` on LVIS detection minival, and `62.9 mIoU` on ADE20k.

<p align="center">
  <img src="./figs/fig1-comparison.png" alt="m3i pre-training" width="600"/>
</p>

<!-- ## Main Results

**Results of InternImage-H**

| Method          | Model         | #param | ImageNet | COCO | LVIS | ADE20k |
|:---------------:|:-------------:|:------:|:--------:|:----:|:----:|:------:|
| M3I Pre-training| InternImage-H | 1B     |          |      |      |        |

**Results of ViT-B/16** -->


## Citation

If this work is helpful for your research, please consider citing the following BibTeX entry.

```
@article{su2022towards,
  title={Towards All-in-one Pre-training via Maximizing Multi-modal Mutual Information},
  author={Su, Weijie and Zhu, Xizhou and Tao, Chenxin and Lu, Lewei and Li, Bin and Huang, Gao and Qiao, Yu and Wang, Xiaogang and Zhou, Jie and Dai, Jifeng},
  journal={arXiv preprint arXiv:2211.09807},
  year={2022}
}
```

