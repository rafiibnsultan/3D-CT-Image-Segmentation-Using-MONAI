Tumor segmentation of multi-organs from 3D medical images.

Image Modality: CT Images

Dataset: Amos: A large-scale abdominal multi-organ benchmark for versatile medical image segmentation, can be found at: https://zenodo.org/record/7262581

Framework: MONAI, an open-source, freely available collaborative framework built on PyTorch

Model: Swin UNETR, a transformer-based model that uses shifted windows for computing self-attention and is connected to an FCNN-based decoder at each resolution via skip connections

All the preprocessing and training-testing methods have been explained in the main file, other 3D segmentation models can also be used, just have to uncomment the command lines in the file

Result using Swin UNETR:
| Mean Dice Score | 0.86  | 
| ------------- | ------------- | 
| 95% HD| 13.91 |

Mean score on different organs:
| Organ | Mean Score |
| ------------- | ------------- | 
| Spleen | 0.9326725602149963 | 
| Right Kidney | 0.9482816457748413 | 
| Left Kidney | 0.9359169006347656 | 
| Gallbladder | 0.8265718221664429| 
| Esophagus | 0.7950014472007751 | 
| Liver | 0.9665778279304504 | 
| Stomach | 0.8874692916870117 | 
| Aorta | 0.934050440788269 | 
| Inferior Vena Cava | 0.8848044872283936 | 
| Pancreas | 0.8297500610351562 | 
| Right Adrenal Gland | 0.7409824132919312 | 
| left adrenal gland | 0.7365583181381226 | 
| Duodenum | 0.774817705154419 | 
| Bladder | 0.7977799773216248 | 
| Prostate/Uterus | 0.7930908203125 | 
