---
title: "Graph Convolutional Topic Model for Data Streams"
collection: publications
permalink: /publication/2020-03-13-Graph-Convolutional-Topic-Model-for-Data-Streams
excerpt: 'N/A'
date: 2020-03-13
venue: 'arXiv preprint arXiv:2003.06112'
paperurl: 'https://arxiv.org/pdf/2003.06112.pdf'
citation: 'Van, L. N., Tran, B., & Than, K. (2020). Graph Convolutional Topic Model for Data Streams. arXiv preprint arXiv:2003.06112.'
---
Learning hidden topics in data streams has been paid a great deal of attention by researchers with a lot of proposed methods, but exploiting prior knowledge in general and a knowledge graph in particular has not been taken into adequate consideration in these methods. Prior knowledge that is derived from human knowledge (eg Wordnet) or a pre-trained model (eg Word2vec) is very valuable and useful to help topic models work better, especially on short texts. However, previous work often ignores this resource, or it can only utilize prior knowledge of a vector form in a simple way. In this paper, we propose a novel graph convolutional topic model (GCTM) which integrates graph convolutional networks (GCN) into a topic model and a learning method which learns the networks and the topic model simultaneously for data streams. In each minibatch, our method not only can exploit an external knowledge graph but also can balance between the external and old knowledge to perform well on new data. We conduct extensive experiments to evaluate our method with both human graph knowledge (Wordnet) and a graph built from pre-trained word embeddings (Word2vec). The experimental results show that our method achieves significantly better performances than the state-of-the-art baselines in terms of probabilistic predictive measure and topic coherence. In particular, our method can work well when dealing with short texts as well as concept drift.
