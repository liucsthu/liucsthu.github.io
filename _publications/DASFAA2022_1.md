---
title: "Similarity-Aware Collaborative Learning for Patient Outcome Prediction"
collection: publications
permalink: /publication/dasfaa2022_1
excerpt: 'medical data mining'
date: 2022-04-08
venue: 'DASFAA, CCF B'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-00126-0_31'
citation: 'Yu, F., Cui, L., Cao, Y., Liu, N., Huang, W., Xu, Y. (2022). Similarity-Aware Collaborative Learning for Patient Outcome Prediction. In: Bhattacharya, A., et al. Database Systems for Advanced Applications. DASFAA 2022. Lecture Notes in Computer Science, vol 13246. Springer, Cham. https://doi.org/10.1007/978-3-031-00126-0_31'
---

The rapid growth in the use of electronic health records (EHR) offers promises for predicting patient outcomes. Previous works on this task focus on exploiting temporal patterns from sequential EHR data. Nevertheless, such approaches model patients independently, missing out on the similarities between patients, which are crucial for patients’ health risk assessment. Moreover, they fail to capture the fine-grained progression of patients’ status, which assist in inferring the patients’ future status. In this work, we propose a similarity-aware collaborative learning model SiaCo for patient outcome prediction. In particular, we design two similarity measurers and two global knowledge matrices to separately calculate the similarity of patients with different information levels and support collaborative learning between patients. To capture the more fine-grained progression of patients’ status, we design a parallelized LSTM to model the temporal-dependent patterns of patient status. Finally, SiaCo integrates the information learned from two measures and the parallelized LSTM to predict patient outcomes. Extensive experiments are conducted on two real disease datasets. The experimental results demonstrate that SiaCo outperforms the state-of-the-art models for two typical tasks of patient outcome prediction.

[Download paper here](https://link.springer.com/chapter/10.1007/978-3-031-00126-0_31)
