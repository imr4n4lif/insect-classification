# Insect Classification using Deep Learning

A comparative study evaluating four deep learning architectures for agricultural insect pest classification using the IP102 dataset.

## Project Overview

This project compares the performance of CNN-based and Transformer-based models for classifying 15 species of agricultural insect pests.

## Insect Classes

1. Mango flat beak leafhopper
2. Alfalfa plant bug
3. Alfalfa weevil
4. Army worm
5. Asiatic rice borer
6. Beet fly
7. Brown plant hopper
8. Corn borer
9. Green bug
10. Paddy stem maggot
11. Rice leaf roller
12. Rice shell pest
13. Tarnished plant bug
14. White margined moth
15. Yellow rice borer

## Models Evaluated

- **EfficientNetV2** (CNN)
- **MobileViT-S** (Hybrid CNN-Transformer)
- **Swin Transformer V2 Tiny** (Vision Transformer)
- **EfficientFormer-L1** (Vision Transformer)

## Results

| Model | Accuracy |
|-------|----------|
| MobileViT-S | 83.00% |
| Swin V2 Tiny | 83.64% |
| EfficientNetV2 | 84.00% |
| **EfficientFormer-L1** | **86.49%** |

**Best Performing Model:** EfficientFormer-L1 with 86.49% accuracy

