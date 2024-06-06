# BEnQA Dataset

This repository contains the dataset for the paper "BEnQA: A Question Answering and Reasoning Benchmark for Bengali and English" (Accepted to ACL 2024 Findings)

## Abstract

In this study, we introduce BEnQA, a dataset comprising parallel Bengali and English exam questions for middle and high school levels in Bangladesh. Our dataset consists of approximately 5K questions covering several subjects in science with different types of questions, including factual, application, and reasoning-based questions. We benchmark several Large Language Models (LLMs) with our parallel dataset and observe a notable performance disparity between the models in Bengali and English. We also investigate some prompting methods, and find that Chain-of-Thought prompting is beneficial mostly on reasoning questions, but not so much on factual ones. We also find that appending English translation helps to answer questions in Bengali. Our findings point to promising future research directions for improving the performance of LLMs in Bengali and more generally in low-resource languages.


## Dataset Structure

The dataset is provided in csv format and can be found in data folder. We also provide few shot examples used in the paper.

## Citation

If you find this dataset useful in your research, please cite the following paper:

```
@misc{shafayat2024benqa,
  title={BEnQA: A Question Answering and Reasoning Benchmark for Bengali and English}, 
  author={Sheikh Shafayat and H M Quamran Hasan and Minhajur Rahman Chowdhury Mahim and Rifki Afina Putri and James Thorne and Alice Oh},
  year={2024},
  eprint={2403.10900},
  archivePrefix={arXiv},
  primaryClass={cs.CL}
}
```
