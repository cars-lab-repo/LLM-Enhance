# LLM-Enhance

This repository contains various components related to the research paper and source codes of LLMEnhance. 

## Datasets

We have 3 files in the dataset folder
- LLM_base_data: This contains the base data for custom data finetuning.
- LLM_Custom_Data: This is the dataset that is derived from finetuning the LLM models on base data.
- LLM_pre_trained: this is the dataset which is derived from normal finetuning of LLM models.

## Source Code

We have 4 notebookss for different purposes

- ### LLM Data Finetuning:
    - This notebook consist of the source code to generate the custom finetuned data where you can change the custom data and also change different LLM's with different parameters

- ### Graph_Generation:
    - This notebook helps in converting the dataset into graph structure which would be used further for the model testing

- ### Model_Testing:
    - This notebook consists of processing the graph data and then applying machine learning models on it such as random forest, naive bayes, svc , GNN, CNN and transformer architecture

- ### Performance_Metrics:
    - This notebook helps in processing with getting the probabilistioc metrics such as Brier Score(BS) and Expected Calibration Error (ECE), and with decision metrics like accuracy, F-1 score, recall, ROC-AUC curve.

