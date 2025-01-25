# Video Instance Segmentation with YOLOv8

This project implements **video instance segmentation** using **YOLOv8**, allowing real-time object detection, segmentation, and tracking in video streams. The notebook includes **data preparation, training, inference, and model export for deployment**.

## Features
- **YOLOv8-based instance segmentation** for real-time multi-object tracking.  
- **Google Colab & Drive integration** for cloud-based training and dataset management.  
- **ONNX model export** for optimized inference and deployment.  
- **Custom dataset support** with flexible preprocessing options.  

## Requirements
- Python 3.8+  
- Google Colab or a local machine with GPU support.  
- Installed dependencies (see `Dependencies Imported in the Notebook`).  

## Dataset Preparation
1. Upload your dataset to **Google Drive** and mount it in the notebook.  
2. Ensure your dataset is in the YOLO format (images and annotation files).  
3. Update the dataset path in the notebook before training.  

## Usage
1. Clone this repository or download the notebook.  
2. Open the notebook in **Google Colab** or Jupyter Notebook.  
3. Follow the step-by-step instructions to train and evaluate the model.  

## Running the Notebook
- Run all cells sequentially to set up the environment, train the model, and perform inference.  
- For local execution, ensure you have all required dependencies installed.  

## Dependencies Imported in the Notebook
- `torch`, `torchvision` (Deep Learning framework)  
- `opencv-python` (Image processing)  
- `numpy` (Matrix operations)  
- `ultralytics` (YOLOv8 framework)  
- `onnxruntime` (ONNX model inference)  

## Results
- The trained YOLOv8 model can perform **real-time video instance segmentation**, detecting and tracking multiple objects simultaneously.  
- The model can be **exported to ONNX** for optimized inference and deployment.  

For further enhanceme
