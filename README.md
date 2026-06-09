# LLM-Enhance: Fine-Tuning Large Language Models for Enhanced Detection of Common Weakness Enumerations
This repository contains source codes and datasets related to hardware and software Common Weakness Enumeration (CWE) detection. </br>
[Shrey Modi](https://github.com/shrey1608) & [Amin Rezaei](https://github.com/r3zaei) </br>

## Datasets
We have 3 files in the dataset folder
- LLM_base_data: This contains the base data for custom data finetuning. The base data is in the form of instructions/prompt and output.
- LLM_Custom_Data: This is the dataset that is derived from finetuning the LLM models on base data after running in the LLM data finetuning notebook.
- LLM_pre_trained: this is the dataset which is derived from normal finetuning of LLM models without the use of base data.

## Source Code
We have 4 notebooks for different purposes
- ### 1) LLM Data Finetuning:
    - This notebook consist of the source code to generate the custom finetuned data where you can change the custom data and also change different LLM's with different parameters to meet the need. If you want to get the LLM_pre_trained dataset then you can just include the LLM and eliminate the custom data.

- ### 2) Graph_Generation:
    - This notebook helps in converting the dataset into graph structure which would be used further for the model testing.This notebook consist of the AST parsing of converting the tabular data into the graph data with CLang.

- ### 3) Model_Testing:
    - This notebook consists of processing the graph data and then applying machine learning models on it such as random forest, naive bayes, svc , GNN, CNN and transformer architectures.

- ### 4) Performance_Metrics:
    - This notebook helps in processing with getting the probabilistic metrics such as Brier Score(BS) and Expected Calibration Error (ECE), and with decision metrics like accuracy, F-1 score, recall, ROC-AUC curve.

- ### 5) Prompts:
    - Prompts include all the different type of prompts that worked and the prompts which gave different kind of outputs.
 
## Citation
```
@INPROCEEDINGS{LLM-Enhance,
  author={Modi, Shrey and Vishwakarma, Rahul and Rezaei, Amin},
  title={LLM-Enhance: Fine-Tuning Large Language Models for Enhanced Detection of Common Weakness Enumerations}, 
  booktitle={2016 IEEE 19th Dallas Circuits and Systems Conference (DCAS)}, 
  year={2026},
  volume={},
  number={},
  pages={1-4},
  doi={10.1109/DCAS69364.2026.11544941}
}
```
      

