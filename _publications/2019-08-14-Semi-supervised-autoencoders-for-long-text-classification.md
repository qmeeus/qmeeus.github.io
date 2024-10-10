---
title: "Semi-supervised Autoencoders for Long Text Classification"
collection: publications
category: books
permalink: /publication/2019-08-14-Semi-supervised-autoencoders-for-long-text-classification
date: 2019-08-14
venue: 'KU Leuven for the degree of Master in Artificial Intelligence (opt. Engineering and Computer Science)'
paperurl: '/files/Quentin_Meeus_Semi_supervised_AE.pdf'
excerpt: 'One major difficulty of text classification learning algorithms is the need of large labelled datasets to be able to reach good performances. In this work, we explore how supervised classifiers trained in conjunction with unsupervised autoencoders can create robust models that do not require much labelled examples to perform well.'
---

## Abstract

One major difficulty of text classification learning algorithms is the need of large labelled datasets to be able to reach good performances. In this work, we explore how supervised classifiers trained in conjunction with unsupervised autoencoders can create robust models that do not require much labelled examples to perform well. In particular, we focus on the processing of large text documents, on which traditional models such as LSTMs perform poorly. 

We propose four semi-supervised autoencoders that impose different constraints on the encodings and compare their performance on the 20Newsgroups dataset. We evaluate the predictions of the classifier as well as the quality of the representations learned by the autoencoder. We show that the joint optimisation of a supervised and unsupervised objective improves both the classification performances and the quality of the representations. Indeed, the semi-supervised autoencoders perform better than a supervised classifier with a matching architecture trained with the same amount of labelled data. Although the advantages provided by the unsupervised objective fade away as more labelled examples are available, the results of our models compare to state-of-the-art classifiers performing the same task. Further, we show that the representations produced by the autoencoders can be used for classification by a Linear SVM or for other related learning tasks such as clustering. Finally, we demonstrate that even when trained on only one label per class, the autoencoder manages to identify words that belong to the same topic, although this finding must be put into perspective, as some topics were ill-defined and some words appeared in multiple unrelated topics.


[Download PDF](/files/Quentin_Meeus_Semi_supervised_AE.pdf)
