# Overview
This project contains the source code used for training and evaluation of the MaskDINO model for instance segmentaion task on the TTPLA dataset: An Aerial-Image Dataset for Detection and Segmentation of Transmission Towers and Power Lines [Y. Lu et al., 2021]. 

# Results
The 220M model was trained on a P100 GPU on Kaggle for a total of 17000 iterations, using data-agumentation techinques such as fixed crop, resize, varying saturation to address the limited size of the training set , while also enhancing the model's robustness to noise in the data.

| **Task**           | **AVG Precision @50 IOU** |
|---------------------|---------------------------|
| Object Detection   | 0.700                    |
| Segmentation       | 0.626                    |
