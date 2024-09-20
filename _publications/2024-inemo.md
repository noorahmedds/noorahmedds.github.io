---
title: "iNeMo: Incremental Neural Mesh Models for Robust Class-Incremental Learning"
collection: publications
permalink: /publication/2024-inemo
excerpt: 'We propose incremental neural mesh models that can be extended with new meshes over time'
date: 2024-07-03
venue: 'ECCV'
paperurl: 'https://arxiv.org/pdf/2407.09271'
citation: 'Fischer, T., Liu, Y., Jesslen, A., Ahmed, N., Kaushik, P., Wang, A., ... & Ilg, E. (2024). iNeMo: Incremental Neural Mesh Models for Robust Class-Incremental Learning. arXiv preprint arXiv:2407.09271.'
---

Different from human nature, it is still common practice today for vision tasks to train deep learning models only initially and on fixed datasets. A variety of approaches have recently addressed handling continual data streams. However, extending these methods to manage out-of-distribution (OOD) scenarios has not effectively been investigated. On the other hand, it has recently been shown that non-continual neural mesh models exhibit strong performance in generalizing to such OOD scenarios. To leverage this decisive property in a continual learning setting, we propose incremental neural mesh models that can be extended with new meshes over time. In addition, we present a latent space initialization strategy that enables us to allocate feature space for future unseen classes in advance and a positional regularization term that forces the features of the different classes to consistently stay in respective latent space regions. We demonstrate the effectiveness of our method through extensive experiments on the Pascal3D and ObjectNet3D datasets and show that our approach outperforms the baselines for classification by 2−6% in the in-domain and by 6−50% in the OOD setting. Our work also presents the first incremental learning approach for pose estimation. Our code and model can be found (at this https URL)[https://github.com/Fischer-Tom/iNeMo].