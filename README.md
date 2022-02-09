# MAE SSL for COVID-CT-SCANS
##  1. Experiment introduction

Masked Autoencoders (MAE) for self-supervised learning [(paper)](https://arxiv.org/abs/2111.06377). It belongs to the type of Generative (Predictive) pre-training.

Inspired by this method, a large amount of unlabeled data can be used to pre-train MAE model, and then fine-tune the model on the medical dataset COVID-CT.

### MAE MODEL

- ![model](./images/model.jpg)

  ### For CT-SCANS

  ![ct-1](./images/CT-1.png)



## 2 Result

![nopertrain](./result/nopertrain.png)

![pertrain](./result/pertrain.png)

The results of the MAE fine-tuning method and the pre-trained model of the EfficientNet supervised learning algorithm on the test set are almost the same
