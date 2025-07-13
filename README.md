 Landslide Detection using Deep Learning

This project focuses on detecting landslide-prone areas using deep learning techniques. Leveraging semantic segmentation on satellite imagery, the model aims to accurately identify regions affected by or vulnerable to landslides.

 📌 Project Highlights

- Utilizes U-Net and U-Net++ architecture for semantic segmentation
- Trained on satellite image datasets with pixel-level annotations
- Implements custom metrics: **F1 Score**, **Precision**, and **Recall**
- Built using **TensorFlow/Keras** and image preprocessing tools
- Visualizes predictions to compare ground truth and output masks

 Model Overview

- **Architecture**: U-Net and U-Net++
- **Input**: Preprocessed satellite images
- **Output**: Binary mask indicating landslide vs. non-landslide
- **Loss Function**: Binary Cross-Entropy + Dice Loss
- **Metrics**: F1 Score, Precision, Recall



