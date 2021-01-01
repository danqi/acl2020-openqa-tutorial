# ACL2020 Tutorial: Open-Domain Question Answering

This ACL2020 tutorial ~~will be~~ was held on July 5th, 2020, by [Danqi Chen](https://www.cs.princeton.edu/~danqic/) `<danqic@cs.princeton.edu>` and [Scott Yih](http://scottyih.org/) `<scottyih@fb.com>`. You can find all the tutorial materials below and the video is [available](https://slideslive.com/38931668/t8-opendomain-question-answering) now.

<!-- The video is *NOT* pre-recorded and we will have a 3.5-hour live session at **3-6:30pm PST**. You can find more information below and hope to see you there! -->

<!-- [[ACL website portal]](https://virtual.acl2020.org/tutorial_T8.html) [[Google calendar]](https://calendar.google.com/calendar/r/eventedit?text=Open-Domain+Question+Answering&dates=20200705T220000/20200706T013000&ctz=UTC&details&location&sprop&sprop=name:) [[Countdown timer]](https://www.timeanddate.com/countdown/generic?p0=179&iso=20200705T18&year=2020&month=7&day=5&hour=18&min=0&sec=0&msg=ACL%202020%20Tutorial%3a%20Open-domain%20Question%20Answering) -->


## Overview
This tutorial provides a comprehensive and coherent overview of cutting-edge research in open-domain question answering (QA), the task of answering questions using a large collection of documents of diversified topics. We will start by first giving a brief historical background, discussing the basic setup and core technical challenges of the research problem, and then describe modern datasets with the common evaluation metrics and benchmarks. The focus will then shift to cutting-edge models proposed for open-domain QA, including two-stage retriever-reader approaches, dense retriever and end-to-end training, and retriever-free methods. Finally, we will cover some hybrid approaches using both text and large knowledge bases and conclude the tutorial with important open questions. We hope that the tutorial will not only help the audience to acquire up-to-date knowledge but also provide new perspectives to stimulate the advances of open-domain QA research in the next phase.

A more detailed introduction can be found [here](docs/acl2020-tutorial.pdf).

## Tutorial Slides

<!-- #### **NEW: All the slides are available now!** -->
<!-- We recommend reading our draft slides before the tutorial. We may have some minor last-minute changes, so please check out the latest version before the live session. -->

1. [Introduction & problem definition](slides/part1-introduction.pdf)
1. [A history of open-domain (textual) QA](slides/part2-history.pdf)
1. [Datasets & evaluation](slides/part3-dataset-evaluation.pdf)
1. [Two-stage retriever-reader approaches](slides/part4-retriever-reader.pdf)
1. [Dense retriever and end-to-end training](slides/part5-dense-retriever-e2e-training.pdf)
1. [Retrieval-free approaches](slides/part6-retrieval-free.pdf)
1. [Open-domain QA using KBs and text](slides/part7-kb-text.pdf)
1. [Conclusion](slides/part8-conclusion.pdf)

## Reading List

### Early QA work
1. [Answering English questions by computer: a survey](docs/simmons1965.pdf). R.F.Simmons. 1965
1. [The Structure and Performance of an Open-domain Question Answering System](https://www.aclweb.org/anthology/P00-1071.pdf). Dan Moldovan, Sanda Harabagiu, Marius Pasca, Rada Mihalcea, Roxana Girju, Richard Goodrum, Vasile Rus. ACL 2000
1. [An Analysis of the AskMSR Question-answering System](https://www.aclweb.org/anthology/W02-1033.pdf). Eric Brill, Susan Dumais and Michele Banko. EMNLP 2002.
1. [Open-Domain Question–Answering](https://wiki.eecs.yorku.ca/course_archive/2012-13/F/6328/_media/ibm-ai-qna.pdf). John Prage. 2007
1. [An Exploration of the Principles Underlying Redundancy-Based Factoid Question Answering](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.4576&rep=rep1&type=pdf). Jimmy Lin. 2007.
1. [Building Watson: An Overview of the DeepQA Project](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2303/2165). David Ferrucci, Eric Brown, Jennifer Chu-Carroll et al. 2010

### Recent work (2017+)
1. **[Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/pdf/1704.00051.pdf). Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes. ACL 2017.**
1. **[R^3: Reinforced Reader-Ranker for Open-Domain Question Answering](https://arxiv.org/pdf/1709.00023.pdf).
Shuohang Wang, Mo Yu, Xiaoxiao Guo, Zhiguo Wang, Tim Klinger, Wei Zhang, Shiyu Chang, Gerald Tesauro, Bowen Zhou, Jing Jiang. AAAI 2018.**
1. [Evidence Aggregation for Answer Re-Ranking in Open-Domain Question Answering](https://arxiv.org/pdf/1711.05116.pdf).
Shuohang Wang, Mo Yu, Jing Jiang, Wei Zhang, Xiaoxiao Guo, Shiyu Chang, Zhiguo Wang, Tim Klinger, Gerald Tesauro, Murray Campbell. ICLR 2018.
1. [Denoising Distantly Supervised Open-domain Question Answering](https://www.aclweb.org/anthology/P18-1161.pdf). Yankai Lin, Haozhe Ji, Zhiyuan Liu, Maosong Sun. ACL 2018.
1. **[Open Domain Question Answering Using Early Fusion of Knowledge Bases and Text](https://www.aclweb.org/anthology/D18-1455.pdf). Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William Cohen. EMNLP 2018.**
1. [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf). Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei, Ilya Sutskever. OpenAI 2019.
1. [End-to-end Open-domain Question Answering with BERTserini](https://arxiv.org/pdf/1902.01718.pdf). Wei Yang, Yuqing Xie, Aileen Lin, Xingyu Li, Luchen Tan, Kun Xiong, Ming Li, Jimmy Lin. NAACL 2019 (demonstration).
1. **[Latent Retrieval for Weakly Supervised Open Domain Question Answering](https://www.aclweb.org/anthology/P19-1612.pdf). Kenton Lee, Ming-Wei Chang, Kristina Toutanova. ACL 2019.**
1. **[Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index](https://arxiv.org/pdf/1906.05807.pdf). Minjoon Seo, Jinhyuk Lee, Tom Kwiatkowski, Ankur P. Parikh, Ali Farhadi, Hannaneh Hajishirzi. ACL 2019.**
1. [Improving Question Answering over Incomplete KBs with Knowledge-Aware Reader](https://www.aclweb.org/anthology/P19-1417.pdf). Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang. ACL 2019.
1. [A Discrete Hard EM Approach for Weakly Supervised Question Answering](https://arxiv.org/pdf/1909.04849.pdf). Sewon Min, Danqi Chen, Hannaneh Hajishirzi, Luke Zettlemoyer. EMNLP 2019.
1. [Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering](https://arxiv.org/pdf/1908.08167.pdf). Zhiguo Wang, Patrick Ng, Xiaofei Ma, Ramesh Nallapati, Bing Xiang. EMNLP 2019.
1. **[PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text](https://arxiv.org/pdf/1904.09537.pdf). Haitian Sun, Tania Bedrax-Weiss, William W. Cohen. EMNLP 2019.**
1. **[Knowledge Guided Text Retrieval and Reading for Open Domain Question Answering](https://arxiv.org/pdf/1911.03868.pdf). Sewon Min, Danqi Chen, Luke Zettlemoyer, Hannaneh Hajishirzi. arXiv 2019.**
1. [Contextualized Sparse Representations for Real-Time Open-Domain Question Answering](https://arxiv.org/pdf/1911.02896.pdf). Jinhyuk Lee, Minjoon Seo, Hannaneh Hajishirzi, Jaewoo Kang. ACL 2020.
1. [Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering](https://arxiv.org/pdf/1911.10470.pdf). Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong. ICLR 2020.
1. **[REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909.pdf).
Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat, Ming-Wei Chang. ICML 2020.**
1. **[Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/pdf/2004.04906.pdf).
Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih. EMNLP 2020.**
1. **[How Much Knowledge Can You Pack Into the Parameters of a Language Model?](https://arxiv.org/pdf/2002.08910.pdf). Adam Roberts, Colin Raffel, Noam Shazeer. EMNLP 2020.**
1. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401.pdf). Patrick Lewis, Ethan Perez, Aleksandara Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela. NeurIPS 2020.
1. [Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf). Tom B. Brown, Benjamin Mann, Nick Ryder et al. NeurIPS 2020.

We understand this is a long reading list :) In case you wonder where you should start with, we plan to discuss the papers in bold in depth during our tutorial.
