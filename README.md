# Object Detection & Segmentation For Autonomous Vehicles

## Project Overview
This Jupyter Notebook is designed to facilitate object detection tasks for self-driving cars using the YOLOv8 model. It involves setting up the environment, handling datasets, and preparing the necessary files and directories for training and evaluation.

## Contents
- **Environment Setup**: Ensures the system has the required GPU resources available for training.
- **Data Exploration**: Lists and verifies the contents of the dataset directory, specifically targeting images and labels required for object detection.
- **Directory Configuration**: Creates necessary directories for storing model outputs and other related files.

## Prerequisites
- **Python**: Ensure you have Python 3.x installed.
- **Jupyter Notebook**: This project is designed to be run in a Jupyter Notebook environment.
- **YOLOv8**: Ensure that YOLOv8 is installed and available within your environment.
- **CUDA**: Required for GPU acceleration.

## How to Run
1. **Clone the Repository**: 
   ```
   git clone <repository-url>
   cd <repository-folder>
   ```
2. **Launch Jupyter Notebook**:
   ```
   jupyter notebook machvis1.ipynb
   ```
3. **Execute the Cells**: Follow the sequence of cells in the notebook, starting with environment checks, data loading, and subsequent training processes.

## Dataset
The dataset used in this project should be placed in the `/kaggle/input/self-driving-cars` directory, containing images and corresponding label files in CSV format.

## Outputs
- **Trained Model**: YOLOv8 model files will be saved in the `/kaggle/working/yolov8` directory.
- **Logs and Metrics**: Output from training, including logs and performance metrics, will be stored within the notebook.

## Visualizations
![image](https://github.com/user-attachments/assets/b615ff2c-95dc-49b2-bdd5-b1bf4a49a8d9)


## Results
![image](https://github.com/user-attachments/assets/ce507ffa-55c9-4aa1-86cd-989c8394a96d)

## Acknowledgements
- **YOLOv8**: For the object detection model.
- **Kaggle**: For providing the dataset and computational resources.
