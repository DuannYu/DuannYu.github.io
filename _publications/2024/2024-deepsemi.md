---
title:          "Toward Balance Deep Semisupervised Clustering"
date:           2024-01-12 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  The goal of balanced clustering is partitioning data into distinct groups of equal size. Previous studies have attempted to address this problem by designing balanced regularizers or utilizing conventional clustering methods. However, these methods often rely solely on classic methods, which limits their performance and primarily focuses on low-dimensional data. Although neural networks exhibit effective performance on high-dimensional datasets, they struggle to effectively leverage prior knowledge for clustering with a balanced tendency. To overcome the above limitations, we propose deep semisupervised balanced clustering, which simultaneously learns clustering and generates balance-favorable representations. Our model is based on the autoencoder paradigm incorporating a semisupervised module. Specifically, we introduce a balance-oriented clustering loss and incorporate pairwise constraints into the penalty term as a pluggable module using the Lagrangian multiplier method. Theoretically, we ensure that the proposed model maintains a balanced orientation and provides a comprehensive optimization process. Empirically, we conducted extensive experiments on four datasets to demonstrate significant improvements in clustering performance and balanced measurements.
cover:          /assets/images/covers/deepsemi.png
authors:
  - Yu Duan
  - Zhoumin Lu
  - Rong Wang
  - Xuelong Li
  - Feiping Nie*
links:
  Paper: /assets/papers/Toward_Balance_Deep_Semisupervised_Clustering.pdf
  Code: https://github.com/DuannYu/BalancedSemi-TNNLS
---
