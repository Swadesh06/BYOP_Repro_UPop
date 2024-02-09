# BYOP_Repro_UPop 
# What it does ❓
This study is aimed at replicating the results of a pruning algorithm, a description of which is shown in the below video:
https://github.com/sdc17/UPop-Project/assets/47023705/7561f7a3-8f5c-4ab6-88b1-30dda533f3fe 

# Description 📝
A novel pruning algorithm , UPop is is shown implented in this paper: https://proceedings.mlr.press/v202/shi23e/shi23e.pdf
The main file for my code is : Main_UPop:DeiT_Implementation_v9.ipynb

This study primarily focuses on implementing UPop on a DeiT model performingimage classification on the CIFAR-10 Dataset, and will aim to examine the following claims and experiments:
-	Examine the feasibility of compression offered by Progressive Pruning at higher compression ratios
-	Aim to replicate the automatic adaptability of the Unified Search and Pruning algorithm over different structures of a model simultaneously 
-	The trade-off from the baseline accuracy/performance by applying both aspects of the algorithm separately and simultaneously.
-	Experiment with linear and non-linear scheduling as a function of the iterations in Progressive Pruning.
-	Experiments with normalisation and sparsity loss inclusion
-	Threshold fixing while binarizing 
-	Open ended final pruning ratio 

# Download Links: 🔗
* Pretrained DeiT model from hugging face: https://huggingface.co/facebook/deit-base-patch16-224 
* Model Description🤖:
DeiT, building on a Vision Transformer backbone, introduces two main features: a "distillation token" for knowledge distillation from a CNN teacher model to enhance data efficiency, and a specialized training approach with strong data augmentation and regularization. These strategies enable DeiT to excel on tasks like ImageNet without massive pre-training datasets.

* CIFAR-10 dataset📊 : https://pytorch.org/vision/main/generated/torchvision.datasets.CIFAR10.html
* Dataset Description:

  - Statistics and Label Distribution
    - Total number of examples: 60,000 images
    - Number of classes: 10
    - Examples per class: 6,000 images
    - Class labels: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck
  - Image size: 32x32 pixels, color (RGB channels)
  - Train / Dev (Validation) / Test Splits
  - Training set: 50,000 images
  - Test set: 10,000 images
 - Note: The CIFAR-10 dataset does not come with a predefined development (validation) set. Researchers often partition the training set to create a validation set for hyperparameter tuning and model evaluation during development. A common practice is to use 45,000 images for training and set aside 5,000 for validation.

- The Python codes provided in this repository download and implement the model and the dataset in the code itself, as they are directly callable. There is no requirement of setting paths in the code or placing files in specifc folders.
# Installation 🔧
  - Requiremnts:
    - Python : 3.11
    - Torch : 2.2.0
    - TQDM : 4.66.1
    - TorchVision:
    - HuggingFace library of Transformers : 4.17.0
    -  cuda : 11.8 (P100 GPU Accelerator)
    -  NumPy: 1.16.4 or higher

# Setup ⚙️

<img width="904" alt="Screenshot 2024-02-10 at 1 28 33 AM" src="https://github.com/Swadesh06/BYOP_Repro_UPop/assets/129365476/12635e40-da77-48b9-acd6-8d899511fc3d">

# Documentation 📑
 - HLD: BYOP_ReproducibilityTrack_2024_Report: https://docs.google.com/document/d/1RguUkhHiGCgGGspkQwgJ_yfFekhuNIvs/edit
   
