## Mining from Graph-Structured Data

With the advance of latent feature, observable and hybird models for mining from multi-relational datasets, the lack of an open toolchain or framework to graph-mining like TensorFlow/Pytorch to Deep Learning imposes unnecessary tool-coding tasks on researchers in the field, and due to the data structural inconsistency presented in graph-mining algorithms proposed by different research groups, the experiment reproducibility is often compromised and make it much harder to produce baseline models than our colleagues in Deep Learning.

This repository serves as a hub to curate tools/algorithms/datasets in Graph-Mining research, especially for reasoning on large-scale knowledge graph, in the hope to ease the difficulty of entering in this interesting research area.

### Tools and Algorithms

> Raw Benchmark Datasets

- [FreeBase15-237](https://www.dropbox.com/sh/afb9teiud7fkig2/AABrwCwQAZmasAQwPzGyNbCOa?dl=0)
- [NELL-995](https://www.dropbox.com/sh/ilvnhkrfv79nyvj/AACD6WhCHNEu_sechVEmg_Fma?dl=0)
- [UW-CSE](https://www.dropbox.com/sh/otz10mtam2xmjn8/AADgjYG2pks0lFN_8hbwF--aa?dl=0)

> Data Modelling/Graph Visualization

- [Python - Networkx](https://networkx.github.io/)
- [Java - GraphStream](http://graphstream-project.org/)
- [Apache TinkerPop](http://tinkerpop.apache.org/)

> Data Representation/Representation Learning

- [SNAP - Node2Vec](https://snap.stanford.edu/node2vec/):

  Node2Vec is an algorithmic framework for representational learning on graphs. Given any graph, it can learn continuous feature representations for the nodes, which can then be used for various downstream machine learning tasks. 

> Latent Feature Models

- [A Family of TransE derived Algorithms](https://github.com/thunlp/KB2E):

  Knowledge Graph Embeddings including TransE, TransH, TransR and PTransE

> Observable Models

- [CMU - Subgraph Feature Extraction](https://github.com/matt-gardner/pra)
- [CMU - Path Ranking Algorithm](https://github.com/noon99jaki/pra)
- [Max Planck - AMIE+](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/amie/)

> Hybird Models

> Feature Selection 

### Research Projects/Groups
- [UCSE - LINQS](https://linqs.soe.ucsc.edu/)
  
  Lead by Prof. Lise Getoor, on Statsitical Relational Learning.
- [Stanford - SNAP](http://snap.stanford.edu/index.html)
  
  Lead by Prof. Jure Leskovec, on general purpose network analysis and graph mining.
- [CMU - NELL](http://rtw.ml.cmu.edu/)
  
  CMU Read the web project, utilizing link-prediction for completing the never-ending language learning knowledge base. 
- [UT Dallas - StarLing](https://starling.utdallas.edu/)
  
  Relational Functional Gradient Boosting based algorithms for statistical relational learning.

### Researchers
- [CMU - TeamCohen](https://wwcohen.github.io/)
  
  Proposed ProPPR, PRA, SGE and TensorLog
- [UCL - Tim Rocktäschel](https://rockt.github.io/)
  
  End-to-End Differentiable Proving
- [MIT - Maximilian Nickel](https://mnick.github.io/)
  
  Tensor Factorization
- [Facebook - Antoine Bordes](https://research.fb.com/people/bordes-antoine/)
  
  Embedding Space


