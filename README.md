# CDS525_group_asg_fakenews
## introduction
With social media becoming ubiquitous, information consumption from this media has also increased.However, this increased reliance on social media has also
given rise to a significant challenge: the proliferation of misinformation, commonly referred to as ”fake news.” This issue is not merely a matter of inconvenience; it poses serious threats to various critical aspects of society, including
the economy, democracy, public health, and safety. Therefore, the identification
and mitigation of fake news have become essential tasks that demand urgent
attention and innovative solutions.


In the realm of Natural Language Processing (NLP), the detection and combat of fake news have become focal points of research, leveraging a diverse array of Machine Learning (ML) and Deep Learning (DL) techniques. Recent
advancements in this field have seen the emergence of various models, including Convolutional Neural Networks (CNN), Bidirectional Long Short-Term Memory networks (BiLSTM), Bidirectional Gated Recurrent Units (BiGRU), hybrid
models combining CNN with two types of text-representation models—contextfree and context-aware, and advanced pre-trained transformer-based models such as BERTbase and RoBERTabase.


Recent studies by Alghamdi et al.[1] by conducting a benchmark study using a wide range of classical ML algorithms and Deep Learning transformer based models. They have highlighted the remarkable capabilities of advanced
Pre-trained Language Models (PLMs) in achieving state-of-the-art performance across numerous NLP tasks. Specifically, in the context of fake news detection using the FakeNewsNet dataset, BERTbase and RoBERTabase
demonstrated exceptional F1 scores of 0.9241 and 0.9085, respectively, for both PolitiFact and GossipCop news. Notably, BERTbase alone achieved accuracy results that were comparable to the best-performing models, underscoring its
effectiveness in extracting meaningful insights from short text samples. The findings also emphasized the superior ability of transformer-based models to handle noisy and sparse datasets, which are common characteristics of realworld fake news data.

## In this project, we use bert for fakenews recognition
we adjust the outlayer for two kind classcification
and use news data with lable 1 and 0 for model trainning
model achieve more than 70% accuracy on test data set after hyper-parameter adjustment

![image](https://github.com/user-attachments/assets/c53dbcdf-e82b-4dc7-882e-2ab455f9cf23)

![image](https://github.com/user-attachments/assets/0edd0cd0-4170-4bad-b05b-3d11f0e48913)

![image](https://github.com/user-attachments/assets/699b6d6f-6df1-42eb-a0e2-d4865ba51bac)

