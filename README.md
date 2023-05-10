# CS678
# Reproducibility Study of On the Importance of Data Size in Probing Fine-tuned Models

## Introduction
In this project, we attempt to reproduce the experiments presented in a research paper by testing a model on multiple languages. 

Most likely, the model/paper you reproduced has only been tested on one language (or just a handful of them). What if we attempted to perform the same task on other languages or domains? Make the appropriate modifications to the code (e.g. if you have an English-only BERT-based model, substitute the English BERT with i.e. CamemBERT or FlauBERT to perform experiments in French, or substitute with the multilingual mBERT or XLM-R models to perform experiments in many languages). You can try to find datasets in other languages (beyond those the paper explores) or you can simply translate the existing datasets with the methods you used in Homework 2 (or both!). You may also explore the usage of Multilingual Checklist to perform behavioral testing on all languages you work with.

## Getting Started
1. Clone the repository to your local machine
2. Install the necessary libraries by running `pip install -r requirements.txt` in the command line.
3. Download the pre-trained BERT-based model and the dataset used in the original paper.
4. If you want to experiment with languages other than the ones included in the original paper, you can find datasets in other languages or translate the existing dataset with the methods you used in Homework 2.

## Reproducing the Experiments
1. Load the pre-trained BERT-based model and tokenizer.
2. Fine-tune the model on the dataset.
3. Evaluate the performance of the model on the test set.
4. If you want to perform experiments on languages other than the ones included in the original paper, translate the dataset and evaluate the performance of the model on the translated test set.

## Multilingual Checklist
The Multilingual Checklist can be used to perform behavioral testing on multiple languages. The checklist includes various tests that can be performed to evaluate the performance of a model on different languages. The tests are designed to evaluate the model's sensitivity to data perturbation, language transferability, and cross-lingual performance.

## Conclusion
In this project, we have demonstrated how to reproduce experiments presented in a research paper and how to extend the experiments to multiple languages. By following the steps outlined in this README, you can reproduce the experiments presented in the original paper and test the performance of the model on languages beyond those included in the paper.
