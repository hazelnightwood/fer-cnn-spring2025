# Facial Recognition Expression using CNNs

This repository contains our final project for Math 156, where we explore facial expression recognition using Convolutional Neural Networks (CNNs). We implement and compare a custom TinyCNN and a pretrained MobileNetV2 model.

## Notebooks

- `Math 156 Group Project (main).ipynb`: TinyCNN from scratch and fine-tuning MobileNetV2 on the primary dataset
- `CK+_final.ipynb`: Training TinyCNN and MobileNetV2 on the CK+ dataset
- `GradCAM-Group-Project.ipynb`: Using GradCAM to visualize regions that influenced the most


Each notebook includes model training, validation, and final test evaluation.

## Project Summary

- **Task**: Classify facial expressions (e.g., happy, sad, angry, etc.)
- **Datasets**:
- [Primary Dataset (Kaggle)](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset/data)
- [CK+ Dataset (Kaggle)](https://www.kaggle.com/datasets/davilsena/ckdataset)
  
- **Frameworks**: PyTorch

## How to Run

1. Open any notebook in Google Colab.
2. Ensure dataset paths match your environment:
   - for `Math 156 Group Project (main).ipynb` and `GradCAM-Group-Project.ipynb`: upload `kaggle.json` and run all the code.
   - for `CK+_final.ipynb`: the dataset is provided in `ckextended.csv`, make sure they are in the same path and run all the code.
4. Run all cells to train and evaluate.


