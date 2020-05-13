# My Paper Title

This repository is the official implementation of [My Paper Title](https://arxiv.org/abs/2030.12345). 

## Requirements

Experiments were done with the following package versions for Python 3.6:
 - PyTorch (`torch`) v1.2.0 with CUDA 9.0;
 - Torchvision (`torchvision`) v0.4.0;
 - Numpy (`numpy`) v1.14.5;
 - Imblearn (`imblearn`) v0.5.0;
 - Cnn_finetune (`cnn_finetune`) v0.6.0;
 - PIL (`PIL`) v6.1.0;
 - Scikit-learn (`sklearn`) v0.21.3;
 - Scipy (`scipy`) v1.1.0;
 - Csv (`csv`) v1.0.
 - math, os, collections, pylab.
 
## Datasets

The datasets manipulated in this code can be downloaded on the following locations:
1. LFWface:
  - Baiduyun: https://pan.baidu.com/s/1QIM8ZVbitRopECfGCKTaZg,    Extraction code: 39t9;

2. animal:
  - Baiduyun: https://pan.baidu.com/s/1dTd80kqvT7TnSZZcVdeVZA,    Extraction code: ixqe.


## Training

To train the model(s) in the paper, run this command:
1. For training baseline model: 
 - LFWface
```train
cd /focus/code_face
python train_baseline.py
```
 - animal
 ```train
cd /focus/code_animal
python train_baseline.py
```
2. 



## Evaluation

To evaluate my model on ImageNet, run:

```eval
python eval.py --model-file mymodel.pth --benchmark imagenet
```

> 📋Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).

## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 

> 📋Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

> 📋Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

> 📋Pick a licence and describe how to contribute to your code repository. 
