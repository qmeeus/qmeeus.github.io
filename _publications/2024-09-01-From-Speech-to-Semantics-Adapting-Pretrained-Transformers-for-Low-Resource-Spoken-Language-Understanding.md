---
title: "From Speech to Semantics: Adapting Pretrained Transformers for Low Resource Spoken Language Understanding"
collection: publications
category: books
permalink: /publication/2024-09-01-From-Speech-to-Semantics-Adapting-Pretrained-Transformers-for-Low-Resource-Spoken-Language-Understanding
date: 2024-09-01
venue: 'KU Leuven for the degree of Doctor of Engineering Science (PhD): Electrical Engineering'
paperurl: '/files/Quentin_Meeus_PhD_thesis_Speech_to_Semantics.pdf'
excerpt: 'This thesis focuses on Spoken Language Understanding (SLU) in low-resource settings. It introduces a novel approach using Bidirectional Transformers with masked language modeling to learn expressive speech representations and train lightweight SLU models effectively. Additionally, it explores pretrained model adaptation, and multitask and multilingual learning to further enhance performance. It also addresses the challenges of limited labeled data with various techniques. Overall, the thesis contributes to the development of efficient and adaptable SLU systems for low-resource environments.'
---

## Abstract

This thesis investigates Spoken Language Understanding (SLU) within low-resource scenarios, focusing on enhancing efficiency and adaptability. We introduce a novel approach for learning expressive speech representations using Bidirectional Transformers with masked language modeling. This approach allows us to train lightweight downstream SLU models effectively, even with limited labeled data. We also explore multitask learning, combining SLU tasks with speech recognition to further boost performance in low-resource settings. Our experiments with intent recognition and sentiment analysis demonstrate the effectiveness of these methods on Dutch and English datasets.

Building upon these findings, we adapt a pretrained speech-to-text model (Whisper) for more complex SLU tasks like slot filling and Spoken Named Entity Recognition (Spoken NER). We explore techniques such as task-specific decoder modules, parameter freezing, and embedding pruning to maintain low data and computational requirements. Our multilingual Spoken NER model, trained on the MSNER dataset we created, showcases the benefits of shared representations across languages and tackles the issue of catastrophic forgetting through strategies like embedding reset and experience replay.

To address the scarcity of labeled data for multilingual SLU, we investigate the use of text-based NLU models to generate silver-quality annotations. We analyze the MSNER dataset, highlighting the potential of this approach while cautioning against potential biases. Finally, we explore the advantages of multilingual Spoken NER models over monolingual counterparts, demonstrating improved performance and generalization, particularly in low-resource scenarios.

Overall, this thesis contributes to the development of efficient and adaptable SLU systems for low-resource contexts. Our work underscores the potential of bidirectional attention, multitask learning, pretrained model adaptation, and multilingual approaches in advancing the field of SLU. We also highlight the challenges and potential solutions for catastrophic forgetting in multilingual settings.

[Download PDF](/files/Quentin_Meeus_PhD_thesis_Speech_to_Semantics.pdf)

[Online Access](https://lirias.kuleuven.be/retrieve/774709){:target="_blank"}
