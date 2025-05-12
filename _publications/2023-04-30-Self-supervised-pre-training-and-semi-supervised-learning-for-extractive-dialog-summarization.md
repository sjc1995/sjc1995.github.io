---
title: "Self-supervised Pre-training and Semi-supervised Learning for Extractive Dialog Summarization"
collection: publications
category: conferences
permalink: /publication/2023-04-30-Self-supervised-pre-training-and-semi-supervised-learning-for-extractive-dialog-summarization
excerpt: 'This paper presents a novel approach for extractive dialogue summarization using self-supervised pre-training and semi-supervised learning. By leveraging unlabeled conversational data and minimal human supervision, the model significantly improves performance on summarization benchmarks, making it suitable for real-world customer service applications.'
date: 2023-04-30
venue: 'ACM Web Conference 2023'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3543873.3587680'
citation: "Yingying Zhuang, Jiecheng Song, Narayanan Sadagopan, and Anurag Beniwal. 2023. Self-supervised Pre-training and Semi-supervised Learning for Extractive Dialog Summarization. In Companion Proceedings of the ACM Web Conference 2023 (WWW '23 Companion). Association for Computing Machinery, New York, NY, USA, 1069–1076. https://doi.org/10.1145/3543873.3587680"
---
Abstract:
Language model pre-training has led to state-of-the-art performance in text summarization. While a variety of pre-trained transformer models are available nowadays, they are mostly trained on documents. In this study we introduce self-supervised pre-training to enhance the BERT model’s semantic and structural understanding of dialog texts from social media. We also propose a semi-supervised teacher-student learning framework to address the common issue of limited available labels in summarization datasets. We empirically evaluate our approach on extractive summarization task with the TWEETSUMM corpus, a recently introduced dialog summarization dataset from Twitter customer care conversations and demonstrate that our self-supervised pre-training and semi-supervised teacher-student learning are both beneficial in comparison to other pre-trained models. Additionally, we compare pre-training and teacher-student learning in various low data-resource settings, and find that pre-training outperforms teacher-student learning and the differences between the two are more significant when the available labels are scarce.