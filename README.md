                                           IIAU2019  High-Resolution Salient Object Detection
---------------------------------------------------------------------------------
This repo provides the works on High-Resolution Salient Object Detection (HRSOD).

1) Towards High-Resolution Salient Object Detection (ICCV2019)
This paper pushes forward high-resolution saliency detection, and contributes a new dataset, named High-Resolution Salient Object Detection (HRSOD) dataset. To our best knowledge, HRSOD is the first high-resolution saliency detection dataset to date. As another contribution, it also provides a novel approach, which incorporates both global semantic information and local high-resolution details, to address this challenging task. 

2) End-to-end framework for High-Resolution Salient Object Detection (HRSOD).

(To be continue .........)

Two HRSOD benchmarks for evaluation. Please check the following link:

DAVIS-SOD Benchmark
---------------------------------------------------------------------------------
The DAVIS-SOD benchmark contains 950 densely annotated images with a 1920x1080 resolution, which are suitable for HRSOD. Images in this dataset are collected from the public DAVIS benchmark, which is a video object segmentation dataset. We select consecutive frames with large motion and conspicuous objects. We ignore the class labels and generate binary ground truth masks for this dataset. Due to the limited images, we only use this dataset as a test set. Please check the following links for downloading.

Divided by Classes:

https://pan.baidu.com/s/1JB8UUcTI6EtCrOjSxm40BQ

Reduced by Classs Fusion: 

https://pan.baidu.com/s/115R45cw2KMri85Tx2p4vIQ

DUT-HRSOD Benchmark
---------------------------------------------------------------------------------
This benchmark is a very recent dataset for HRSOD. In total, it contains 2010 images, including 1610/400 images for training and test, respectively. All images are collected from the website of Flickr. High-quality pixel-level masks are manually annotated by 40 subjects. The shortest edge of each image in this dataset is more than 1200 pixels. Please check the following links for downloading.

Training data

Part1: https://pan.baidu.com/s/1b9PZYIFIVAngqUWJK8Tmew

Part2: https://pan.baidu.com/s/1M8yAFlqk9EYn-5ygTEd3sQ

Part3: https://pan.baidu.com/s/1_AaK9ECk1Sx12aAxT2HVYA

Part4: https://pan.baidu.com/s/1t88YqNMAjZrn1xTUZwqgjg

Part5: https://pan.baidu.com/s/1RKrKKBwESmin9KlGXwskNA

Mask: https://pan.baidu.com/s/106OqhpK1X26ufOE9BTDikA

Test Data

Image: https://pan.baidu.com/s/1q83Kgn_VG2zqNc3NUsNKaw

Mask: https://pan.baidu.com/s/1A_ii221PfrFU60rCgr_I6w

Citing
-------------------------------------------------------------------------------
If you find above benchmarks useful in your work, please cite the following papers:

@InProceedings{Zeng_2019_ICCV,
author = {Zeng, Yi and Zhang, Pingping and Zhang, Jianming and Lin, Zhe and Lu, Huchuan},
title = {Towards High-Resolution Salient Object Detection},
booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
} 
