# SLS-KD-Selective-Large-to-Small-Knowledge-Distillation-for-Agricultural-VQA-Tasks
10k and 50k single-turn samples (corresponding to multi-turn dialogues ) for Agricultural VQA Tasks (AgMMU Benchmark)

# AgMMU Benchmark for Agricultural Visual Question Answering

## Overview
The AgMMU Benchmark is an evaluation framework designed for Agricultural Visual Question Answering tasks. It aims to enhance the generalization performance of vision language models in daily agricultural scenarios through small-sample training and advanced knowledge distillation techniques.

## Dataset Construction
The benchmark dataset is derived from the AgBase corpus. We extract specific dialogues to construct two common daily question-answering patterns. The dataset comprises:
* 10k single-turn samples corresponding to multi-turn dialogues.
* 50k single-turn samples corresponding to multi-turn dialogues.

These two subsets represent distinct interaction modes frequently encountered in practical agricultural applications.

## Methodology
To improve model adaptability with limited data, we employ a small-sample training strategy. Furthermore, we introduce SLS-KD (Selective Large-to-Small Knowledge Distillation) to transfer robust agricultural knowledge from large foundational models to smaller models for deployment. This approach significantly boosts the generalization capability of the deployed models in real-world daily scenarios.

## System Deployment
We have deployed a dedicated web platform to facilitate practical application and dataset management. The platform provides two core functionalities:
* Question Answering Interface: Users can submit agricultural images and queries for real-time inference.
* Question Management System: Administrators can monitor, categorize, and manage user queries to continuously refine the benchmark and model performance.

## Citation
Please cite our paper if you use the AgMMU Benchmark in your research:

[Insert Paper Title Here]  
[Insert Journal Name and DOI Here]
