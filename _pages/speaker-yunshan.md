---
layout: archive
title: "Talk Info: Yunshan Ma"
permalink: /speaker-yunshan
author_profile: true
---

## SimCBR: Simple Contrastive Learning for Bundle Recommendation

Abstract: Bundle recommendation aims to identify user preference at the granularity of bundle, which is composed of a group of correlated items. Scrutinize this task, it is of crucial importance to model three key patterns: user-bundle interactions, user-item interactions, and bundle-item affiliation. To exploit these structural patterns, graph neural networks (GNNs) prevail in incorporating them into the representations of users and bundles and delineating the user’s preference on bundles. However, these GNN-based models suffer from some deficiencies: ineffective model designs in GNNs, sparse and noisy interactions, which result in unsatisfactory representations and hinder the recommendation accuracy.

In this work, we seek a simple yet effective solution to alleviate these problems. Here we present a Simple Contrastive learning framework for Bundle Recommendation (SimCBR). At its core is the removal of the ineffective operations in GNNs and the incorporation of contrastive learning to overcome these challenges. In particular, by removing the nonlinear feature transformations and activation functions from GNNs, we establish a lighter but more effective backbone to perform the representation learning of users and bundles. Based on this new backbone, we explore contrastive learning to generate auxiliary supervisions from the three patterns and refine critical information that is stable against noises. Specifically, we create multiple views of nodes via simple data augmentations (i.e., edge dropout, message dropout, and original preservation), and conduct self-discrimination over these views. To demonstrate the effectiveness of SimCBR, we conduct extensive experiments on three benchmark datasets, namely Youshu, NetEase, and iFashion. The experimental results show that SimCBR is superior to state-of-the-art baselines (e.g., SGL, BundleNet, BGCN) by a large margin.

## Bio:

