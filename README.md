
# Enhancing Vision Transformers for Image Classification: A Study on Infused Adapters, Inhibition, and Amplification of Internal

## Authors:
- Sai Krishna Sangeetha
- Sricharan Maddena
- College of Engineering and Computer Science, University of Central Florida, Orlando, Florida 32816

## Overview:
This project focuses on the enhancement of Vision Transformers for image classification tasks. It explores the Infused Adapter by Inhibiting and Amplifying Inner Activations (IA3) technique for fine-tuning Vision Transformers, particularly for image classification.

## Description:
The project includes several Jupyter notebooks and Python scripts that demonstrate the application of the IA3 technique to Vision Transformers. These notebooks and scripts cover various aspects such as pre-training, siamese network training, and parameter-efficient fine-tuning (PEFT) methods.

## Notebooks:
- cub_fsl.ipynb: Demonstrates few-shot learning using the CUB dataset.
- miniimagenet_pretrain.ipynb: Covers pre-training on the MiniImageNet dataset.
- VIT_384-peft.ipynb: Illustrates PEFT on a Vision Transformer model.
- vit_siamese.ipynb: Shows the implementation of a siamese network with Vision Transformers.
- VIT.ipynb: General notebook for Vision Transformer training and evaluation.

## Scripts:
helpers_vit.py: Contains helper functions for training and evaluating Vision Transformers.
vision_transformer.py: The core script for the Vision Transformer model implementation.

## Dataset:
Our experiments are primarily conducted on the Caltech-UCSD Birds (CUB) and MiniImageNet datasets. You can download these datasets from their respective official sources.

## Results:
Our implementation demonstrates significant improvements in image classification tasks using the IA3 technique. The results section includes detailed performance metrics and comparative analysis with traditional fine-tuning methods.

## Conclusion:
The IA3 technique offers a promising direction for enhancing Vision Transformers in image classification. Our findings suggest notable improvements in both accuracy and computational efficiency.

## Future Work:
We propose further exploration into adaptive fine-tuning methods and extending our approach to other Transformer-based models in diverse applications.
