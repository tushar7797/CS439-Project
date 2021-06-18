This repository/folder contains the code written for the project of Optimization in Machine Learning course (CS-439).

# Deep-Latent-Variable-Models-for-Text-Generation

These are my implementations of [OPTIMUS](https://arxiv.org/abs/2004.04092) and [CARA](https://aaai.org/ojs/index.php/AAAI/article/view/6346/6202) both published by Microsoft. I also incorporated the [Prox-Policy Optimization](https://arxiv.org/abs/1707.06347) algorithm along with the above mentioned models

The results and detailed explanations for these models can be found in my report

I performed the experiments using Python version 3.6x.

## Overview of architecture

 - modules/ : Contains the model architectures of Optimus (VAE) and CARA
 - pytorch_transformers/ : Contains the configuration files for BERT and GPT2
 - trl/ : Contains functions and models for the Prox Policy Optimization Algorithm
 - Optimus+PPO.ipynb : contains the code to recreate the experiments related to Optimus and PPO
 - CARA.ipynb : contains the code to recreate the experiments related to CARA

## Instructions to run the colab files

We provide the preprocessed text data in the following files. Please download it and add it to the required variables in colab files

-[inputs.pth](https://drive.google.com/file/d/1-4zCan2ZPXBQxsi-au68lyg1OxLehwrz/view?usp=sharing)
-[labels.pth](https://drive.google.com/file/d/1-D4jQ10Igk2Q400yuld6OYRAmXd1Pdo4/view?usp=sharing)
-[polarity.pth](https://drive.google.com/file/d/15HZc-E2asy5NRHUWXGZ3XVD-8XAe324x/view?usp=sharing)

