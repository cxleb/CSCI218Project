## CSCI218 Group Project

This repository contains all Jupiter notebooks used for our CSCI218 Group Project.
| Group Member | Student ID |
| --- | --- |
| Anh Quan Tran | 7236475 |
| Huu Khang Nguyen | 7402909 |
| Caleb Wait | 6786352 |
| Hallam Roberts | 6799899 |

Each model was tested on a [face recognition dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset) over 100 epochs.

| Model | Accuracy | AUC | Precision | Recall |
| --- | --- | --- | --- | --- |
| [CNN](./face-expression-detection-from-scratch.ipynb) | 0.6 | 0.9 | 0.72 | 0.47 |
| [EfficientNetV2B0](./face-expression-detection-EfficientNet.ipynb) | 0.44 | 0.8 | 0.67 | 0.25 |
| [ResNet50](./face-expression-detection-ResNet50.ipynb) | 0.6244 | 0.8913 | 0.6627 | 0.5869 |
