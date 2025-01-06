# FL-Attention-CDSS
## Attention on Personalized Clinical Decision Support System: Federated Learning Approach

* Paper: https://ieeexplore.ieee.org/document/9373264 OR https://arxiv.org/abs/2401.11736

- System Overview

  We present the design and implementation of an edge-based personalized clinical decision support system that integrates federated learning and AI technologies for enhanced medical diagnosis.

- Key Features:

  Designed to leverage edge devices for personalized clinical decision support.

  Incorporates the attention mechanism within a sequence-to-sequence network for medical diagnosis on edge devices.

  Exploits the federated learning framework to collaboratively train personalized models in a distributed manner, on datasets with non-IID symptom-disease relationships.

  Employs a centralized global model to aggregate gradients from personalized models, capturing shared knowledge while preserving privacy.

  Designed with adaptability in mind, allowing models to handle new symptoms and diseases without requiring complete re-training.

- Original Dataset: https://github.com/Aniruddha-Tapas/Predicting-Diseases-From-Symptoms/tree/master/Manual-Data

## Citation
If you find this code helpful in your work, please consider citing our paper. Your support is greatly appreciated!
```
@INPROCEEDINGS{9373264,
  author={Thwal, Chu Myaet and Thar, Kyi and Tun, Ye Lin and Hong, Choong Seon},
  booktitle={2021 IEEE International Conference on Big Data and Smart Computing (BigComp)}, 
  title={Attention on Personalized Clinical Decision Support System: Federated Learning Approach}, 
  year={2021},
  volume={},
  number={},
  pages={141-147},
  keywords={Decision support systems;Training;Neural networks;Collaborative work;Data models;Medical diagnostic imaging;Diseases;clinical decision support system;healthcare;artificial intelligence;sequence-to-sequence network;attention mechanism;federated learning},
  doi={10.1109/BigComp51126.2021.00035}}
```
