---
title: "KdTNet: Medical Image Report Generation via Knowledge-Driven Transformer"
collection: publications
permalink: /publication/dasfaa2022_2
excerpt: 'medical data mining'
date: 2022-04-08
venue: 'DASFAA, CCF B'
paperurl: 'https://dl.acm.org/doi/abs/10.1007/978-3-031-00129-1_8'
citation: 'Yiming Cao, Lizhen Cui, Fuqiang Yu, Lei Zhang, Zhen Li, Ning Liu, and Yonghui Xu. 2022. KdTNet: Medical Image Report Generation via Knowledge-Driven Transformer. In Database Systems for Advanced Applications: 27th International Conference, DASFAA 2022, Virtual Event, April 11–14, 2022, Proceedings, Part III. Springer-Verlag, Berlin, Heidelberg, 117–132. https://doi.org/10.1007/978-3-031-00129-1_8
'
---

Writing medical image reports is an inefficient and time-consuming task for doctors. Automatically generating medical reports is an essential task of medical data mining, which can alleviate the workload of doctors and improve the standardization of reports. However, the existing methods mainly adopt the CNN-RNN structure to align image features with text features. This structure has difficulty dealing with the dependencies between distant text locations, leading to inconsistent context and semantics in the generated report. In this paper, we propose a knowledge-driven transformer (KdTNet) model for generating coherent medical reports. First, the visual grid and graph convolutional modules are devised to extract fine-grained visual features. Second, we adopt the transformer decoder to generate the hidden semantic states. Subsequently, a BERT-based auxiliary language module is employed to obtain the context language features of reports from the pre-defined medical term knowledge. We design a multimodal information fusion module to adaptively calculate the contribution of visual and linguistic features to the report for report generation. Extensive experiments on two real datasets explicate that our KdTNet model has achieved superior performance in captioning metrics and human evaluation compared with the state-of-the-art methods.
[Download paper here]https://dl.acm.org/doi/abs/10.1007/978-3-031-00129-1_8)
