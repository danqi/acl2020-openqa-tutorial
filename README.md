# ACL2020 Tutorial: Open-Domain Question Answering

The ACL2020 tutorial will be held at **3-6:30pm PST**, July 5th, 2020, by [Danqi Chen](https://www.cs.princeton.edu/~danqic/) `<danqic@cs.princeton.edu>` and [Scott Yih](http://scottyih.org/) `<scottyih@fb.com>`.

## Overview
This tutorial provides a comprehensive and coherent overview of cutting-edge research in open-domain question answering (QA), the task of answering questions using a large collection of documents of diversified topics. We will start by first giving a brief historical background, discussing the basic setup and core technical challenges of the research problem, and then describe modern datasets with the common evaluation metrics and benchmarks. The focus will then shift to cutting-edge models proposed for open-domain QA, including two-stage retriever-reader approaches, dense retriever and end-to-end training, and retriever-free methods. Finally, we will cover some hybrid approaches using both text and large knowledge bases and conclude the tutorial with important open questions. We hope that the tutorial will not only help the audience to acquire up-to-date knowledge but also provide new perspectives to stimulate the advances of open-domain QA research in the next phase.

## Outline
1. Introduction
1. Problem definition & motivation
1. A history of open-domain (textual) QA
1. Datasets & evaluation
1. Two-stage retriever-reader approaches
1. Dense retriever and end-to-end training
1. Retriever-free approaches
1. Open-domain QA using KBs and text
1. Open problems and future directions

A more detailed document can be found [here](docs/acl2020-tutorial.pdf). We will also update the slides of each part before the tutorial day.

## Reading List
1. [Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/pdf/1704.00051.pdf). Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes. ACL 2017.
1. [R^3: Reinforced Reader-Ranker for Open-Domain Question Answering](https://arxiv.org/pdf/1709.00023.pdf).
Shuohang Wang, Mo Yu, Xiaoxiao Guo, Zhiguo Wang, Tim Klinger, Wei Zhang, Shiyu Chang, Gerald Tesauro, Bowen Zhou, Jing Jiang. AAAI 2018.
1. [Evidence Aggregation for Answer Re-Ranking in Open-Domain Question Answering](https://arxiv.org/pdf/1711.05116.pdf).
Shuohang Wang, Mo Yu, Jing Jiang, Wei Zhang, Xiaoxiao Guo, Shiyu Chang, Zhiguo Wang, Tim Klinger, Gerald Tesauro, Murray Campbell. ICLR 2018.
1. [Denoising Distantly Supervised Open-domain Question Answering](https://www.aclweb.org/anthology/P18-1161.pdf). Yankai Lin, Haozhe Ji, Zhiyuan Liu, Maosong Sun. ACL 2018.
1. [Open Domain Question Answering Using Early Fusion of Knowledge Bases and Text](https://www.aclweb.org/anthology/D18-1455.pdf). Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William Cohen. EMNLP 2018.
1. [End-to-end Open-domain Question Answering with BERTserini](https://arxiv.org/pdf/1902.01718.pdf). Wei Yang, Yuqing Xie, Aileen Lin, Xingyu Li, Luchen Tan, Kun Xiong, Ming Li, Jimmy Lin. NAACL 2019 (demonstration).
1. [Latent Retrieval for Weakly Supervised Open Domain Question Answering](https://www.aclweb.org/anthology/P19-1612.pdf). Kenton Lee, Ming-Wei Chang, Kristina Toutanova. ACL 2019.
1. [Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index](https://arxiv.org/pdf/1906.05807.pdf). Minjoon Seo, Jinhyuk Lee, Tom Kwiatkowski, Ankur P. Parikh, Ali Farhadi, Hannaneh Hajishirzi. ACL 2019.
1. [A Discrete Hard EM Approach for Weakly Supervised Question Answering](https://arxiv.org/pdf/1909.04849.pdf). Sewon Min, Danqi Chen, Hannaneh Hajishirzi, Luke Zettlemoyer. EMNLP 2019.
1. [PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text](https://arxiv.org/pdf/1904.09537.pdf). Haitian Sun, Tania Bedrax-Weiss, William W. Cohen. EMNLP 2019.
1. [Knowledge Guided Text Retrieval and Reading for Open Domain Question Answering](https://arxiv.org/pdf/1911.03868.pdf). Sewon Min, Danqi Chen, Luke Zettlemoyer, Hannaneh Hajishirzi. arXiv 2019.
1. [Contextualized Sparse Representations for Real-Time Open-Domain Question Answering](https://arxiv.org/pdf/1911.02896.pdf). Jinhyuk Lee, Minjoon Seo, Hannaneh Hajishirzi, Jaewoo Kang. ACL 2020.
1. [Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering](https://arxiv.org/pdf/1911.10470.pdf). Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong. ICLR 2020.
1. [REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909.pdf).
Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat, Ming-Wei Chang. ICML 2020.
1. [Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/pdf/2004.04906.pdf).
Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih. arXiv 2020.
1. [How Much Knowledge Can You Pack Into the Parameters of a Language Model?](https://arxiv.org/pdf/2002.08910.pdf). Adam Roberts, Colin Raffel, Noam Shazeer. arXiv 2020.
1. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401.pdf). Patrick Lewis, Ethan Perez, Aleksandara Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela. arXiv 2020.
