# Awesome-Graph-Learning-Papers
A curated list of graph learning papers, articles, tutorials, slides and projects


# Table of Contents
+ [Book](#book)
+ [Researcher](#researcher)
+ [Survey](#survey)
+ [Tutorial](#tutorial)

## Book
+ **Graph Representation Learning**
  + **Authors:** William L. Hamilton
  + **Affiliation:** McGill University
  + **Publisher:** Morgan & Claypool
  + **Year of Publication:** 2020
  + **Download:** [PDF](https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf)
  + **Keywords:** Node Embedding, Graph Neural Network, Generative Graph Models
  + **Abstract:** This book
    + provides a brief but comprehensive introduction to graph representation learning, including methods for embedding graph data, graph neural networks, and deep generative models of graphs.

## Researcher
+ Jian Tang
  + Assistant Professor
  + HEC Montreal
  + Email: tangjianpku@gmail.com
  + HomePage: https://jian-tang.com/
+ William L. Hamilton
  + Assistant Professor
  + McGill University
  + Email: wlh@cs.mcgill.ca
  + HomePage: https://williamleif.github.io/
+ Xiangnan He (何向南)
  + Professor
  + School of Data Science, School of Information Science and Technology, University of Science and Technology of China
  + Email: xiangnanhe@gmail.com
  + HomePage: http://staff.ustc.edu.cn/~hexn/
+ Yizhou Sun (孙怡舟)
  + Associate Professor
  + Department of Computer Science, University of California, Los Angeles
  + Email: yzsun@cs.ucla.edu
  + HomePage: http://web.cs.ucla.edu/~yzsun/index.html

## Survey
+ **A Comprehensive Survey of Graph Embedding: Problems, Techniques and Applications**
  + **Authors:** Hongyun Cai, Vincent W. Zheng, and Kevin Chen-Chuan Chang
  + **Affiliation:** Advanced Digital Sciences Center, University of Illinois
  + **Publiser:** IEEE
  + **Year of Publication:** 2018
  + **Download:** [PDF](https://ieeexplore.ieee.org/document/8294302)
  + **Keywords:** Graph Embedding, Graph Analytics, Graph Embedding Survey, Network Embedding
  + **Abstract:** This paper
    +  introduces the formal definition of graph embedding as well as the related concepts.
    +  proposes two taxonomies of graph embedding which correspond to what challenges exist in different graph embedding problem settings and how the existing work address these challenges in their solutions.
    +  summarizes the applications that graph embedding enables and suggests four promising future research directions in terms of computation efficiency, problem settings, techniques and application scenarios.
+ **A Comprehensive Survey on Graph Neural Networks**
  + **Authors:** Zonghan Wu, Shirui Pan, Fengwen Chen, et al.
  + **Affiliation:** University Of Technology Sydney, Monash University, University of Illinois at Chicago
  + **Publisher:** IEEE
  + **Year of Publication:** 2019
  + **Download:** [PDF](https://ieeexplore.ieee.org/document/9046288)
  + **Keywords:** Deep Learning, Graph Neural Networks, Graph Convolutional Networks, Graph Representation Learning, Graph Autoencoder, Network Embedding
  + **Abstract:** This paper
    + provides a comprehensive overview of graph neural networks in data mining and machine learning fields.
    + proposes a new taxonomy to divide the state-of-the-art graph neural networks into four categories, namely recurrent graph neural networks, convolutional graph neural networks, graph autoencoder, and spatial-temporal graph neural networks.
    + discusses the applications of graph neural networks across various domains.
    + summarizes the open source codes, benchmark data sets, and model evaluation of graph neural networks.
    + proposes potential research directions in this rapidly growing field.
+ **A Survey on Knowledge Graph-Based Recommender Systems**
  + **Authors:** Qingyu Guo, Fuzhen Zhuang, et al.
  + **Affiliation:** Chinese Academy of Sciences (CAS), Hong Kong University of Science and Technology, University of Science and Technology of China, Baidu Talent Intelligence Center, Baidu Research, Microsoft Research Asia
  + **Publisher:** arXiv
  + **Year of Publication:** 2020
  + **Download:** [PDF](https://arxiv.org/pdf/2003.00911.pdf)
  + **Keywords:** Knowledge Graph, Recommender System, Explainable Recommendation
  + **Abstract:** This paper
    + conducts a systematical survey of knowledge graph-based recommender systems.
    + investigates the proposed algorithms by focusing on how the papers utilize the knowledge graph for accurate and explainable recommendation.
    + introduces datasets used in these works.
    + proposes several potential research directions in this field.
+ **Graph Neural Networks: A Review of Methods and Applications**
  + **Authors:** Jie Zhou, Ganqu Cui, Zhengyan Zhang, et al.
  + **Affiliation:** Tsinghua University, Tencent
  + **Publisher:** arXiv
  + **Year of Publication:** 2019
  + **Download:** [PDF](https://arxiv.org/pdf/1812.08434.pdf)
  + **Keywords:** Deep Learning, Graph Neural Network 
  + **Abstract:** This paper
    + provides a detailed review over existing graph neural network models and their varients in terms of graph types(directed graphs, heterogeneous graphs, graphs with edge information, dynamic graphs), propagation types(convolution, gate, attention, skip connection, hierarchical pooling), and training methods(sampling, receptive field control, data augmentation, unsupervised training). Moreover, serveral general frameworks(MPNN, NLNN, GN) are introduced in this paper.
    + systematically categorizes the applications and divides the applications into structural scenarios, non-structural scenarios and other scenarios.
    + proposes four open problems(shallow structure, dynamic graphs, non-structural scenarios, scalability) for future research.
+ **Representation Learning on Graphs: Methods and Applications**
  + **Authors:** William L. Hamilton, Rex Ying, Jure Leskovec
  + **Affiliation:** Stanford University
  + **Publisher:** IEEE
  + **Year of Publication:** 2017
  + **Download:** [PDF](https://arxiv.org/pdf/1709.05584.pdf)
  + **Keywords:** Representation Learning, Deep Learning, Node Embedding
  + **Abstract:** This paper
    + provides a conceptual review of key advancedments in this area of representation learning on graphs, including matrix factorization-based methods, random-walk based algorithms, and graph neural networks.
    + reviews methods to embed individual nodes as well as approaches to embed entire(sub) graphs.
    + develops a unified framework(an encoder-decoder perspective) to describe these recent approaches.
    + highlights a number of important applications and directions for future work.

## Tutorial
+ **Deep Graph Learning: Foundations, Advances and Applications**
  + **Authors:** Yu Rong, Tingyang Xu, et al.
  + **Affiliation:** Tencent AI Lab, Tsinghua University, Michigan State University, Vanderbilt University, IBM Research AI
  + **Download:** [Link](https://ai.tencent.com/ailab/ml/KDD-Deep-Graph-Learning.html)
  + **Keywords:** Deep Graph Learning
  + **Abstract:**
    + Many real data come in the form of non-grid objects, i.e. graphs, from social networks to molecules. Adaptation of deep learning from grid-alike data (e.g. images) to graphs has recently received unprecedented attention from both machine learning and data mining communities, leading to a new cross-domain field---Deep Graph Learning (DGL). Instead of painstaking feature engineering, DGL aims to learn informative representations of graphs in an end-to-end manner. It has exhibited remarkable success in various tasks, such as node/graph classification, link prediction, etc.
    + In this tutorial, we aim to provide a comprehensive introduction to deep graph learning. We first introduce the theoretical foundations on deep graph learning with a focus on describing various Graph Neural Network Models (GNNs). We then cover the key achievements of DGL in recent years. Specifically, we discuss the four topics: 1) training deep GNNs; 2) robustness of GNNs; 3) scalability of GNNs; and 4) self-supervised and unsupervised learning of GNNs. Finally, we will introduce the applications of DGL towards various domains, including but not limited to drug discovery, computer vision, medical image analysis, social network analysis, natural language processing and recommendation.
