---
layout: page
title: Imbalanced Data Clustering
description: A simple k-means type algorithm for clustering imbalanced data
img: assets/img/imbalanced_data_clustering.jpg
importance: 3
category: work
---
## Introduction
<hr>
Centroid-based clustering algorithms, such as hard K-means (HKM) and fuzzy K-means (FKM), have suffered from learning bias towards large clusters. Their centroids tend to be crowded in large clusters, compromising performance when the true underlying data groups vary in size (i.e., imbalanced data). To address this, we propose a novel K-means type clustering algorithm, called **equilibrium K-means (EKM)**, with a new objective function mitigating the large cluster learning bias. Besides robust to imbalanced data, EKM also has the following advantages:

- **Simplicity**: Iterating between just two steps.
- **Resource-Saving**: Time complexity proportional to the data/instance number.
- **Scalability**: scalable to large datasets via batch learning.

We have uploaded the [original paper](https://arxiv.org/abs/2402.14490v3) on arXiv.

## Example
<hr>

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-12 mt-md-0">
        {% include figure.html path="assets/img/EKM_example.png" title="ekm_example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Implementation
<hr>

Matlab code is available [here](https://github.com/ydcnanhe/Imbalanced-Data-Clustering-using-Equilibrium-K-Means).
