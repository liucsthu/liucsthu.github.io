---
title: "Learning Interpretable Rules for Scalable Data Representation and Classification"
collection: publications
permalink: /publication/tpami2024
excerpt: 'Interpretable machine learning'
date: 2024-02-01
venue: 'IEEE TPAMI, CCF A'
paperurl: 'https://ieeexplore.ieee.org/document/10302393'
citation: 'Z. Wang, W. Zhang, N. Liu and J. Wang, "Learning Interpretable Rules for Scalable Data Representation and Classification," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 46, no. 2, pp. 1121-1133, Feb. 2024, doi: 10.1109/TPAMI.2023.3328881.'
---
Rule-based models, e.g., decision trees, are widely used in scenarios demanding high model interpretability for their transparent inner structures and good model expressivity. However, rule-based models are hard to optimize, especially on large data sets, due to their discrete parameters and structures. Ensemble methods and fuzzy/soft rules are commonly used to improve performance, but they sacrifice the model interpretability. To obtain both good scalability and interpretability, we propose a new classifier, named Rule-based Representation Learner (RRL), that automatically learns interpretable non-fuzzy rules for data representation and classification. To train the non-differentiable RRL effectively, we project it to a continuous space and propose a novel training method, called Gradient Grafting, that can directly optimize the discrete model using gradient descent. A novel design of logical activation functions is also devised to increase the scalability of RRL and enable it to discretize the continuous features end-to-end. Exhaustive experiments on ten small and four large data sets show that RRL outperforms the competitive interpretable approaches and can be easily adjusted to obtain a trade-off between classification accuracy and model complexity for different scenarios.
[Download paper here](https://ieeexplore.ieee.org/document/10302393)
