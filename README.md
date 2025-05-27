Drone Detection Model Comparison
This repository contains implementations and comparisons of three popular object detection models (YOLOv5, Faster R-CNN, and RetinaNet) for drone detection.

Project Overview
This project aims to compare the performance of three different object detection architectures on drone detection tasks:

YOLOv5
Faster R-CNN
RetinaNet
Dataset
The dataset used in this project is from Roboflow:

Project: drones-oddbp
Version: 3
Format: Compatible with all three models
Repository Structure
Model Training
Each model was trained using the same dataset with the following configurations:

YOLOv5: 50 epochs, img size 640, batch size 16
Faster R-CNN: Default configurations
RetinaNet: Default configurations
Results Visualization
The comparison notebook includes:

Visual comparisons of all three models on the same test images
Different colored bounding boxes for each model's predictions
Performance metrics comparison
Installation & Usage
Clone the repository:
Install required dependencies:
Download the trained models (if provided) or train your own using the training notebooks.

Run the comparison notebook to visualize results.

Requirements
Python 3.8+
PyTorch
YOLOv5
Detectron2 (for Faster R-CNN)
Torchvision
OpenCV
Roboflow
Results
The visual results and performance metrics can be found in the comparison notebook, showing how each model performs on the same test dataset with different colored bounding boxes for easy comparison.

License
This project is open-source and available under the MIT License.

Acknowledgements
Roboflow for providing the drone dataset
Ultralytics for YOLOv5
Facebook AI Research for Detectron2
For detailed implementation and results, please refer to the individual notebooks in the repository.

![0292_jpg rf 9a0c16a589235c98f16ced7cc4f81606](https://github.com/user-attachments/assets/1c5fb61b-7ccc-4528-8103-bec594e93359)
![output](https://github.com/user-attachments/assets/d5e2c6c2-1110-41e3-8027-ab397837e4e4)
