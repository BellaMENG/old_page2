---
layout: archive
title: "References"
permalink: /paper-list/
author_profile: true
---


## Weekly Report
links here: [Jan 25th - Jan 31st](https://github.com/BellaMENG/bellameng.github.io/blob/master/_pages/paperlist.md#jan-25th---jan-31st)


## GitHub Code
[Source Code](https://github.com/BellaMENG/Bitcoin-Blockchain-DataMining)


## Dataset
[MIT dataset](https://senseable2015-6.mit.edu/bitcoin/)

This page contains processed bitcoin data of first 508241 blocks.

## VLDB
Subgraphs and Communities: [Vertex Priority Based Butterfly Counting for Large-scale Bipartite Networks](http://www.vldb.org/pvldb/vol12/p1139-wang.pdf)\
Graph Analytics: [Efficient Algorithms for Densest Subgraph Discovery](http://www.vldb.org/pvldb/vol12/p1719-fang.pdf)

## Network

[Network structure and minimum degree](https://ucilnica.fri.uni-lj.si/pluginfile.php/1212/course/section/1202/Seidman%20-%20Network%20structure%20and%20minimum%20degree%2C%201983.pdf)

## Bitcoin

[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)\
[An Analysis of Anonymity in the Bitcoin System](https://arxiv.org/abs/1107.4524)\
[The Unreasonable Effectiveness of Address Clustering](https://arxiv.org/pdf/1605.06369.pdf)\
[A Bayesian approach to identify Bitcoin users](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0207000)\
[Quantitative Analysis of the Full Bitcoin Transaction Graph](https://eprint.iacr.org/2012/584.pdf)\
[Bitcoin Transaction Graph Analysis](https://people.csail.mit.edu/spillai/data/papers/bitcoin-transaction-graph-analysis.pdf)\
[Inferring the Interplay of Network Structure and Market Effects in Bitcoin](https://arxiv.org/abs/1412.4042)\
[Do the Rich Get Richer? An Empirical Analysis of the Bitcoin Transaction Network](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0086197)\
[BlockSci: Design and Applications of a Blockchain Analysis Platform](https://arxiv.org/abs/1709.02489)\
[Oracle Presentation: Analyzing Blockchain and Bitcoin Transaction Data as Graph](https://www.youtube.com/watch?v=w8OEVobyhFE)\
[An Evaluation of Bitcoin Address Classification based on Transaction History Summarization](https://arxiv.org/abs/1903.07994)\
[Breaking Bad: De-Anonymising Entity Types on the Bitcoin Blockchain Using Supervised Machine Learning](https://core.ac.uk/download/pdf/143481278.pdf)

## Subgraph matching

[In-Memory Subgraph Matching: An In-depth Study](https://dl.acm.org/doi/10.1145/3318464.3380581)\
[Efficient Subgraph Matching on Billion Node Graphs](https://arxiv.org/abs/1205.6691)\
[Taming Verification Hardness: An Efficient Algorithm for Testing Subgraph Isomorphism](https://dl.acm.org/doi/10.14778/1453856.1453899)\
[Managing and Mining Large Graphs: Systems and Implementations](http://www.cs.albany.edu/~jhh/courses/readings/shao.sigmod12.graph_dbs.pdf)

## Graph Clustering

[Introduction of Graph Clustering - Springer](https://link.springer.com/referenceworkentry/10.1007%2F978-0-387-30164-8_348#:~:text=Definition,edge%20weights%20or%20edge%20distances.)\
[An Algorithm for Subgraph Isomorphism](https://dl.acm.org/doi/10.1145/321921.321925)

## Series of Research of [Damiano Di Francesco Maesa](https://scholar.google.com/citations?hl=en&user=9u78kdMAAAAJ&view_op=list_works&sortby=pubdate)

2020 - [Leveraging the Users Graph and Trustful Transactions for the Analysis of Bitcoin Price](https://ieeexplore.ieee.org/abstract/document/9138785)\
2019 - [The bow tie structure of the Bitcoin users graph](https://link.springer.com/article/10.1007/s41109-019-0163-y)\
2018 - [Data Driven Analysis of Bitcoin Properties: Exploiting the Users Graph](https://www.researchgate.net/profile/Damiano_Maesa/publication/320026355_Data-driven_analysis_of_Bitcoin_properties_exploiting_the_users_graph/links/5ac4c4feaca27218eabcb770/Data-driven-analysis-of-Bitcoin-properties-exploiting-the-users-graph.pdf)


## Weekly Reports

### Jan 25th - Jan 31st
- Processed the dataset and stored the data into CSR format. [Code](https://github.com/BellaMENG/Bitcoin-Blockchain-DataMining)\
- Functions to implement: according to the original bitcoin blockchain data, form a adjacency matrix, where each element on the matrix represent an edge between corresponding address i and address j. According to i and j, unique ids for the edges are generated and generate a file that contains timestamp information and transaction amount information of that edge.\
- Implementing the following algorithms on the graph:\
https://arxiv.org/pdf/1308.0971.pdf Page 43-45\
[The unreasonable effectiveness of address clustering](https://arxiv.org/pdf/1605.06369.pdf), 2 heuristics: Common spending and One-time change\
Implement another datastructure to represent the transaction network of Blockchain and link it to the address transaction network

