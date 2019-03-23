
# Transferable-Interactiveness-Knowledge-for-Human-Object-Interaction-Detection
Codes and Models for Transferable Interactiveness Knowledge for Human-Object Interaction Detection. (CVPR 2019 Poster). Notice that this repository is still under construction and subject to change.

Link: [[Paper]](https://arxiv.org/abs/1811.08264)  [Website]

## Citation
If you find our works useful in your research, please consider citing:
```
 @article{li2018transferable,
 title={Transferable Interactiveness Prior for Human-Object Interaction Detection},
  author={Li, Yong-Lu and Zhou, Siyuan and Huang, Xijie and Xu, Liang and Ma, Ze and Fang, Hao-Shu and Wang, Yan-Feng and Lu, Cewu},
  journal={arXiv preprint arXiv:1811.08264},
  year={2018}
}
```

## Introduction
*Human-Object Interaction (HOI)* Detection is an important problem to understand how humans interact with  objects. In this paper, we explore Interactiveness Knowledge which indicates whether human and object interact with each other or not. We found that interactiveness knowledge can be learned across HOI datasets, regardless of HOI category settings. Our core idea is to exploit an Interactiveness Network to learn the general interactiveness knowledge from multiple HOI datasets and perform Non-Interaction Suppression before HOI classification in inference. On account of the generalization of interactiveness, interactiveness network is a transferable knowledge learner and can be cooperated with any HOI detection models to achieve desirable results. We extensively evaluate the proposed method on HICO-DET and V-COCO datasets. Our framework outperforms state-of-the-art HOI detection results by a great margin, verifying its efficacy and flexibility.

![Overview of Our Framework](https://github.com/DirtyHarryLYL/Transferable-Interactiveness-Network/blob/master/images/overview.jpg?raw=true)

## Results on HICO-DET and V-COCO dataset
**Our Best Results on HICO-DET dataset**
Method| Full(def) | Rare(def) | None-Rare(def)| Full(ko) | Rare(ko) | None-Rare(ko) | 
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|   
RC<sub>D</sub>| 13.75 | 10.23 | 15.45 | 15.34| 10.98|17.02
RP<sub>D</sub>C<sub>D</sub>| **17.03** | **13.42**| **18.11**| **19.17**| **15.51**|**20.26**
RC<sub>T</sub>| 10.61  | 7.78 | 11.45 | 12.47 | 8.87|13.54
RP<sub>T1</sub>C<sub>D</sub>| 16.91   | 13.32 | 17.99 | 19.05 | 15.22|20.19
RP<sub>T2</sub>C<sub>D</sub>| **17.55**   | **13.81** | **18.67** | **19.79** | **15.71**|**21.01**

**Our Best Results on V-COCO dataset**
Method| Full(def) | 
|:---:|:---:|
RC<sub>D</sub>| 43.2| 
RP<sub>D</sub>C<sub>D</sub>| **47.8** |
RC<sub>T</sub>| 38.5 | 
RP<sub>T1</sub>C<sub>D</sub>| 48.3  | 
RP<sub>T2</sub>C<sub>D</sub>| **48.7**   |

## Getting Started

### Prerequisites

### Training

### Testing
