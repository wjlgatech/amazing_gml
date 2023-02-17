# Graph Machine Learning Resource

**Credits & References**
- [Nikiter Iserson](https://www.linkedin.com/in/nikita-iserson/)'s [Linkedin blogpost](https://www.linkedin.com/feed/update/urn:li:activity:6997487239664410624/)

## Graph ML Intro

Introduction to Graph Neural Networks by Distill.pub with nice animations
https://distill.pub/2021/understanding-gnns/
https://distill.pub/2021/gnn-intro/

Basics of Graph Neural Networks Course by Zak Jost
https://www.graphneuralnets.com/p/basics-of-gnns/?src=cta

End-to-end DGL Tutorials for GNN from George Karypis Vassilis N. Ioannidis and Da Zheng
https://github.com/dglai/WWW20-Hands-on-Tutorial
https://github.com/dglai/dgl_winter_school
https://github.com/dglai/KDD20-Hands-on-Tutorial

End-to-end ML Pipelines for GNN:
https://engineering.rappi.com/an-approach-for-implementing-and-deploying-production-graph-deep-learning-models-ad52c6b7a481
https://awslabs.github.io/realtime-fraud-detection-with-gnn-on-dgl/en/

## Popular GNN applications

GNN for Fraud Detection:
https://ytongdou.com/files/GNN_Fraud_Talk.pdf
https://github.com/safe-graph/DGFraud

GNN for Misinformation Detection:
https://github.com/safe-graph/GNN-FakeNews

GNN for Anomaly Detection:
https://github.com/pygod-team/pygod

By Yingtong Dou

GNN for Traffic Forecasting by Weiwei Yang
https://arxiv.org/abs/2101.11174
https://github.com/jwwthu/GNN4Traffic

GNN for Routing Problems by Chaitanya Joshi
https://www.chaitjo.com/post/deep-learning-for-routing-problems/

GNN for RecSys:
https://github.com/tsinghua-fib-lab/GNN-Recommender-Systems

## Future of GNNs

GraphML in 2022: Where are we now?
https://towardsdatascience.com/graph-ml-in-2022-where-are-we-now-f7f8242599e0

GraphML at ICML 2022
https://towardsdatascience.com/graph-machine-learning-icml-2022-252f39865c70

By Michael Galkin Anton Tsitsulin

What does hold 2022 for Geometric and Graph ML by Michael Bronstein
https://towardsdatascience.com/predictions-and-hopes-for-geometric-graph-ml-in-2022-aa3b8b79f5cc

Hannes Stärk Reading Group for Graph ML:
https://hannes-stark.com/logag-reading-group

Graph Machine Learning Channel by Sergey Ivanov Michael Galkin
https://t.me/graphML

Tutorial - Graph Self-Supervised Learning
https://sites.google.com/asu.edu/kdd2022-tutorial-gmsl/)
Data Augmentation for Deep Graph Learning: A Survey
https://arxiv.org/abs/2202.08235

By Kaize Ding


## Efficiency and Scalability of GNNs

Recent Advances in Efficient GNN training by Chaitanya Joshi
https://www.chaitjo.com/post/efficient-gnns/

Awesome GNN Systems in Production
https://github.com/chwan1016/awesome-gnn-systems

Nimble GNN Embedding with Tensor-Train Decomposition
https://dl.acm.org/doi/pdf/10.1145/3534678.3539423

Distributed Hybrid CPU and GPU training for Graph Neural Networks on Billion-Scale Heterogeneous Graphs
https://assets.amazon.science/8e/01/c90c5c894771a5de766cbbba2b7e/distributed-hybrid-cpu-and-gpu-training-for-graph-neural-networks-on-billion-scale-heterogeneous-graphs.pdf

## Competition Top Solutions

RecSys 2022 - 1st Place, LightGBM + GNN for Fashion Sequential Recommendation

https://dl.acm.org/doi/abs/10.1145/3556702.3556850

# nbdev_colab

### Why
- to develop your package, to test code, to write documentation from 1 source of truth: your colab notebooks
- no beefy local computer needed, everything is computed with a colab notebook and stored on your Google drive

### How

Step0: clone this template to your github account.

Step1: create a new repo (e.g. name it 'my_amazing_project') using this template. 

Step2: to clone your newly created repo in your Google drive, use colab to open this notebook [git_clone_my_amazing_project_to_gdrive.ipynb](https://github.com/wjlgatech/nbdev_colab/blob/master/git_clone_my_amazing_project_to_gdrive.ipynb) and run it through.

Step3: to learn what to do next, start at notebook `nb/00_core.ipynb` from your Google Drive


Known bugs that need to be sorted (any help is welcome):

* ReadMe not updating after updating `index.ipynb`
* Tests are not passing


