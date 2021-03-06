# A Survey on 3D Deep Learning

* Dataset
* Paper
* Tutorial
* Packages

## Background

#### Data Representation
The 3D data can be represented in the following forms:
* multi-view RGB(D) images
* volumetric
* polygonal mesh
* point cloud
* primitive-based CAD models

## Dataset

* [Princeton Segmentation Benchmark dataset (PSB)](http://segeval.cs.princeton.edu/)

* [Labeled PSB dataset (L-PSB)](https://people.cs.umass.edu/~kalo/papers/LabelMeshes/)

* [Shape COSEG dataset](http://irc.cs.sdu.edu.cn/~yunhai/public_html/ssl/ssd.htm)

## Packages

* Geometric Deep Learning Extension Library for PyTorch ([Github](https://github.com/rusty1s/pytorch_geometric))

* Pytorch implementation of Graph Convolution Networks & Graph Attention Convolutional Networks ([Github](https://github.com/meliketoy/graph-cnn.pytorch))

* PyTorch implementation of Graph Convolutional Networks for semi-supervised classification ([Github](https://github.com/tkipf/pygcn), [paper](https://arxiv.org/abs/1609.02907), [blog](http://tkipf.github.io/graph-convolutional-networks/))

* Point cloud semantic segmentation via Deep 3D Convolutional Neural Network ([Github](https://github.com/nsavinov/semantic3dnet), [slides](https://drive.google.com/file/d/0B2SXn94m2RhEbnFMbHVZNVJ3bzA/view))

## Tutorial

* A Tutorial on 3D Deep Learning (CVPR 2017) ([web](http://3ddl.stanford.edu/), [video](https://www.youtube.com/watch?v=8CenT_4HWyY))

* Machine Learning for 3D Data (Stanford CS468 - Spring 2017) ([web](http://graphics.stanford.edu/courses/cs468-17-spring/schedule.html))

* Machine Learning for 3D Data (CSE291-I00 - Winter 2018)([web](https://cse291-i.github.io/schedule.html))

* Data-Driven Shape Analysis and Processing ([original version](https://people.cs.umass.edu/~kalo/papers/EGstar16/data_driven_shape.pdf), [latest version](https://people.cs.umass.edu/~kalo/datadrivenshape/data_driven_shape.pdf))

* Polygon Mesh Processing ([web](http://www.pmp-book.org/))

  A free online book about mesh representation

* Udacity Interactive 3D Graphics [web](https://classroom.udacity.com/courses/cs291)

## Papers
  
### Feature based methods
  
* [2015] 3D Mesh Labeling via Deep Convolutional Neural Networks ([paper](https://dl.acm.org/citation.cfm?id=2835487))
  
* 3D Shape Segmentation via Shape Fully Convolutional Networks ([paper](https://arxiv.org/abs/1702.08675))
  
* 3D Mesh Segmentation via Multi-branch 1D Convolutional Neural Networks ([paper](https://arxiv.org/abs/1705.11050))

### Octree
  
* [2017] O-CNN: Octree-based Convolutional Neural Networks for 3D Shape Analysis ([paper](https://wang-ps.github.io/O-CNN.html), [code](https://github.com/Microsoft/O-CNN))

### Projection

* [2017] 3D Shape Segmentation with Projective Convolutional Networks ([paper](https://arxiv.org/abs/1612.02808), [web](https://people.cs.umass.edu/~kalo/papers/shapepfcn/), [code](https://github.com/kalov/ShapePFCN))
