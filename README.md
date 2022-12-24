Tumor segmentation of multi-organs from 3D medical images.

Image Modality: CT Images

Dataset: Amos: A large-scale abdominal multi-organ benchmark for versatile medical image segmentation, can be found at: https://zenodo.org/record/7262581

Framework: MONAI, an open-source, freely available collaborative framework built on PyTorch

Model: Swin UNETR, a transformer-based model that uses shifted windows for computing self-attention and is connected to an FCNN-based decoder at each resolution via skip connections

All the preprocessing and training-testing methods have been explained in the main file, other 3D segmentation models can also be used, just have to uncomment the command lines in the file

Result using Swin UNETR:
| Mean Dice Score | 0.88  | 
| ------------- | ------------- | 
| 95% HD| 3.81 |
