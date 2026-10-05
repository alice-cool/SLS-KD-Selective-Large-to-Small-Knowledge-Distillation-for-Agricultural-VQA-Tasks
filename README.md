# SLS-KD-Selective-Large-to-Small-Knowledge-Distillation-for-Agricultural-VQA-Tasks
10k and 50k single-turn samples (corresponding to multi-turn dialogues ) for Agricultural VQA Tasks (AgMMU Benchmark)

## Overview
The AgMMU Benchmark is an evaluation framework designed for Agricultural Visual Question Answering tasks. It aims to enhance the generalization performance of vision language models in daily agricultural scenarios through small-sample training and advanced knowledge distillation techniques.
<img width="928" height="669" alt="image" src="https://github.com/user-attachments/assets/f7940223-5d29-491b-82a3-dbfc843db110" />

## Dataset Construction
The benchmark dataset is derived from the AgBase corpus. We extract specific dialogues to construct two common daily question-answering patterns. The dataset comprises (as shown in Fig.1):
* 10k single-turn samples corresponding to multi-turn dialogues.
* 50k single-turn samples corresponding to multi-turn dialogues.
<img width="1903" height="605" alt="image" src="https://github.com/user-attachments/assets/b097dce8-5dab-423f-9d07-bb88a43683b3" />

These two subsets represent distinct interaction modes frequently encountered in practical agricultural applications.

## Methodology
To improve model adaptability with limited data, we employ a small-sample training strategy. Furthermore, we introduce SLS-KD (Selective Large-to-Small Knowledge Distillation) to transfer robust agricultural knowledge from large foundational models to smaller models for deployment. This approach significantly boosts the generalization capability of the deployed models in real-world daily scenarios.

## System Deployment
We have deployed a dedicated web platform to facilitate practical application and dataset management. The platform provides two core functionalities:
* Question Answering Interface: Users can submit agricultural images and queries for real-time inference. Users can upload one or more images related to agricultural scenarios to obtain answers, Chain-of-Thought (CoT) sequences, and attention maps for interpretability.
* Question Management System: Administrators can monitor, categorize, and manage user queries to continuously refine the benchmark and model performance.

## Citation
The dataset presented in this repository is a curated subset systematically extracted and organized from the **AgBase** development corpus, which is part of the foundational **AgMMU** benchmark suite. 

Please cite our paper if you use the dataset in your research:
@misc{sls-kd-agricultural-vqa-2026,
  author       = {alice-cool},
  title        = {SLS-KD: Selective Large-to-Small Knowledge Distillation for Agricultural Multimodal Question Answering Tasks},
  year         = {2026},
  publisher    = {GitHub},
  url          = {https://github.com/alice-cool/SLS-KD-Selective-Large-to-Small-Knowledge-Distillation-for-Agricultural-VQA-Tasks}
}

[Insert Paper Title Here]  
[Insert Journal Name and DOI Here]
