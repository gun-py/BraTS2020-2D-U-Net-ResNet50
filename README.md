# BraTS2020
A Light & Scalable Solution to BraTS2020 | Medical Brain Tumor Segmentation (2D Segmentation)

- Developed the segmentation models for segregating and detecting Brain Tumours
- Used stacked-segmentation method on flair, mask, t1, t1ce, t2 mask using 2-D U-Nets with ResNet50 encoder and ImageNet weights with Dice Loss
- Achieved a CV-score of dice loss - 0.009851, iou score - 0.7358, fscore - 0.8207

Dataset link:
https://www.kaggle.com/awsaf49/brats20-dataset-training-validation
