---
title: "Fed-ANIDS: Federated learning for anomaly-based network intrusion detection systems"
category: articles
permalink: /articles/2023-08-30-fed-anids-anomaly-detection
excerpt: 'Meryem Janati Idrissi, Hamza Alami, Abdelkader El Mahdaouy, <b>Abdellah El Mekki</b>, Soufiane Oualil, Zakaria Yartaoui, Ismail Berrada'
date: 2023-08-30
venue: 'Expert Systems with Applications'
citation: 'Meryem Janati Idrissi, Hamza Alami, Abdelkader El Mahdaouy, Abdellah El Mekki, Soufiane Oualil, Zakaria Yartaoui, Ismail Berrada, Fed-ANIDS: Federated learning for anomaly-based network intrusion detection systems,
Expert Systems with Applications, Volume 234, 2023, 121000, ISSN 0957-4174, https://doi.org/10.1016/j.eswa.2023.121000.'
---

<a href='https://www.sciencedirect.com/science/article/pii/S0957417423015026'>Download PDF here</a>

Abstract: As computer networks and interconnected systems continue to gain widespread adoption, ensuring cybersecurity has become a prominent concern for organizations, regardless of their scale or size. Meanwhile, centralized machine learning-based Anomaly Detection (AD) methods have shown promising results in improving the accuracy and efficiency of Network Intrusion Detection Systems (NIDS). However, new challenges arise such as privacy concerns and regulatory restrictions that must be tackled. Federated Learning (FL) has emerged as a solution that allows distributed clients to collaboratively train a shared model while preserving the privacy of their local data. In this paper, we propose Fed-ANIDS, a NIDS that leverages AD and FL to address the privacy concerns associated with centralized models. To detect intrusions, we compute an intrusion score based on the reconstruction error of normal traffic using various AD models, including simple autoencoders, variational autoencoders, and adversarial autoencoders. We thoroughly evaluate Fed-ANIDS using various settings and popular datasets, including USTC-TFC2016, CIC-IDS2017, and CSE-CIC-IDS2018. The proposed method demonstrates its effectiveness by achieving high performance in terms of different metrics while preserving the data privacy of distributed clients. Our findings highlight that autoencoder-based models outperform other generative adversarial network-based models, achieving high detection accuracy coupled with fewer false alarms. In addition, the FL framework (FedProx), which is a generalization and re-parametrization of the standard method for FL (FedAvg), achieves better results.


 Recommended citation: Meryem Janati Idrissi, Hamza Alami, Abdelkader El Mahdaouy, Abdellah El Mekki, Soufiane Oualil, Zakaria Yartaoui, Ismail Berrada, Fed-ANIDS: Federated learning for anomaly-based network intrusion detection systems,
Expert Systems with Applications, Volume 234, 2023, 121000, ISSN 0957-4174, https://doi.org/10.1016/j.eswa.2023.121000.

{% raw %}
```bibtex
@inproceedings{el-mekki-etal-2021-domain,
    title = "Domain Adaptation for {A}rabic Cross-Domain and Cross-Dialect Sentiment Analysis from Contextualized Word Embedding",
    author = "El Mekki, Abdellah  and
      El Mahdaouy, Abdelkader  and
      Berrada, Ismail  and
      Khoumsi, Ahmed",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.226",
    doi = "10.18653/v1/2021.naacl-main.226",
    pages = "2824--2837",
    abstract = "Finetuning deep pre-trained language models has shown state-of-the-art performances on a wide range of Natural Language Processing (NLP) applications. Nevertheless, their generalization performance drops under domain shift. In the case of Arabic language, diglossia makes building and annotating corpora for each dialect and/or domain a more challenging task. Unsupervised Domain Adaptation tackles this issue by transferring the learned knowledge from labeled source domain data to unlabeled target domain data. In this paper, we propose a new unsupervised domain adaptation method for Arabic cross-domain and cross-dialect sentiment analysis from Contextualized Word Embedding. Several experiments are performed adopting the coarse-grained and the fine-grained taxonomies of Arabic dialects. The obtained results show that our method yields very promising results and outperforms several domain adaptation methods for most of the evaluated datasets. On average, our method increases the performance by an improvement rate of 20.8{\%} over the zero-shot transfer learning from BERT.",
}
{% endraw %}

