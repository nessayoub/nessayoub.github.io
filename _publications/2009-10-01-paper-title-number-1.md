---
title: "SimProx: A Similarity-Based Aggregation in Federated Learning with Client Weight Optimization"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: " introducing SimProx, a novel federated learning aggregation approach that addresses data heterogeneity and outperforms traditional methods."
date: 2024-10-01
venue: "IEEE Open Journal of The Communications Society"
# slidesurl: "http://academicpages.github.io/files/slides1.pdf"
paperurl: "http://academicpages.github.io/files/IEEE_OJCOMM.pdf"
citation: "Ayoub El-Niss, Ahmad Alzu’bi, Abdelrahman Abuarqoub, Mohammad Hammoudeh, Ammar Muthanna (2024). SimProx: A Similarity-Based Aggregation in Federated Learning with Client Weight Optimization; <i>IEEE Open Journal of The Communications Society</i>."
---

Federated Learning (FL) enables decentralized training of machine learning models across multiple clients, preserving data privacy by aggregating locally trained models without sharing raw data. Traditional aggregation methods, such as Federated Averaging (FedAvg), often assume uniform client contributions, leading to suboptimal global models in heterogeneous data environments. This article introduces SimProx, a novel FL approach for aggregation that addresses heterogeneity in data through three key improvements. First, SimProx employs a composite similarity-based weighting mechanism, integrating cosine and Gaussian similarity measures to dynamically optimize client contributions. Then, it incorporates a proximal term in the client weighting scheme, using gradient norms to prioritize updates closer to the global optimum, thereby enhancing model convergence and robustness. Finally, a dynamic parameter learning technique is introduced, which adapts the balance between similarity measures based on data heterogeneity, refining the aggregation process. Extensive experiments on standard benchmarking datasets and real-world multimodal data demonstrate that SimProx significantly outperforms traditional methods like FedAvg in terms of accuracy. SimProx offers a scalable and effective solution for decentralized deep learning in diverse and heterogeneous environments.
