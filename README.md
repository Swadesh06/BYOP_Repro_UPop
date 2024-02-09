# BYOP_Repro_UPop
# What it does 
This study is aimed at replicating the results of a pruning algorithm, a description of which is shown in the below video:
https://github.com/sdc17/UPop-Project/assets/47023705/7561f7a3-8f5c-4ab6-88b1-30dda533f3fe 

# Description
A novel pruning algorithm , UPop is is shown implented in this paper: https://proceedings.mlr.press/v202/shi23e/shi23e.pdf

This study primarily focuses on implementing UPop on a DeiT model performingimage classification on the CIFAR-10 Dataset, and will aim to examine the following claims and experiments:
-	Examine the feasibility of compression offered by Progressive Pruning at higher compression ratios
-	Aim to replicate the automatic adaptability of the Unified Search and Pruning algorithm over different structures of a model simultaneously 
-	The trade-off from the baseline accuracy/performance by applying both aspects of the algorithm separately and simultaneously.
-	Experiment with linear and non-linear scheduling as a function of the iterations in Progressive Pruning.
-	Experiments with normalisation and sparsity loss inclusion
-	Threshold fixing while binarizing 
-	Open ended final pruning ratio 
![image](https://github.com/Swadesh06/BYOP_Repro_UPop/assets/129365476/d858c432-e707-4f71-bc22-72bd5543aa50)

# Download Links:
-Pretrained DeiT model from hugging face: https://huggingface.co/facebook/deit-base-patch16-224 
- CIFAR-10 dataset : https://pytorch.org/vision/main/generated/torchvision.datasets.CIFAR10.html

  The Python codes provided in this repository download and implement the model and the dataset in the code itself, as they are directly callable.
