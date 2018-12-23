
# Deep Paper Gestalt

## Abstract

Recent years have witnessed a significant increase in the number of paper submissions to computer vision conferences. The sheer volume of paper submissions and the insufficient number of competent reviewers cause a considerable burden for the current peer review system. In this paper, we learn a classifier to predict whether a paper should be accepted or rejected based solely on the visual appearance of the paper (i.e., the gestalt of a paper). Experimental results show that our classifier can safely reject 50% of the bad papers while wrongly reject only 0.4% of the good papers, and thus dramatically reduce the workload of the reviewers. We also provide tools for providing suggestions to authors so that they can improve the gestalt of their papers.

### Technical report: 
[[arXiv]](https://arxiv.org/pdf/1812.08775.pdf)

<img src=http://filebox.ece.vt.edu/~jbhuang/project/gestalt/this_paper.png>

## Dataset

Computer Vision Paper Gastalt dataset 
- Low resolution (680 x 440) [[link]](http://filebox.ece.vt.edu/~jbhuang/project/gestalt/CVPG_Dataset_LowRes.zip) (930 MB)
- High resolution (3400 x 2200) - Coming soon

## Pre-trained weights

Pre-trained weight for good/bad paper classifier [[link]](http://filebox.ece.vt.edu/~jbhuang/project/gestalt/PaperNet.pth) (44 MB)
- See Section 3.3 and 3.4 of the [paper](https://arxiv.org/pdf/1812.08775.pdf).

Pre-trained weight for random CVPR/ICCV paper generator [[link]](http://filebox.ece.vt.edu/~jbhuang/project/gestalt/network-snapshot-011203.pkl) (270 MB)
- See Section 4.1: What does a good paper look like?

Pre-trained weight for bad-to-good paper generator [[link]](http://filebox.ece.vt.edu/~jbhuang/project/gestalt/latest_net_G_A.pth) (44 MB)
- See Section 4.2: Learning bad-to-good paper translation

## Latent space interpolation of accepted CVPR/ICCV papers
[[link]](https://www.youtube.com/watch?v=yQLsZLf02yg)

## (To-Do) Instructions for running the pre-trained models on your own papers.

Stay tuned! 
