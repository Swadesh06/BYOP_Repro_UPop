# BYOP_Repro_UPop
# What it does 
This study is aimed at replicating the results of a pruning algorithm, a description of which is shown in the below video:

# Description
A novel pruning algorithm , UPop is is shown implented in this paper:

My study primarily focuses on implementing UPop on a DeiT model performingimage classification on the CIFAR-10 Dataset, and will aim to examine the following claims and experiments:
-	Examine the feasibility of compression offered by Progressive Pruning at higher compression ratios
-	Aim to replicate the automatic adaptability of the Unified Search and Pruning algorithm over different structures of a model simultaneously 
-	The trade-off from the baseline accuracy/performance by applying both aspects of the algorithm separately and simultaneously.
-	Experiment with linear and non-linear scheduling as a function of the iterations in Progressive Pruning.
-	Experiments with normalisation and sparsity loss inclusion
-	Threshold fixing while binarizing 
-	Open ended final pruning ratio 
![image](https://github.com/Swadesh06/BYOP_Repro_UPop/assets/129365476/d858c432-e707-4f71-bc22-72bd5543aa50)
