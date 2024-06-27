# YOLO (You Only Look Once) Project

## Overview
This project focuses on implementing and utilizing YOLO models for object detection. YOLO (You Only Look Once) is a state-of-the-art, real-time object detection system that is fast and accurate.

## Installation
1. Navigate to the `yolov10` folder.
2. Open a terminal and run the following command:
   ```bash
   pip install .
   ```

## Deployment
To deploy the model using Streamlit, run:
```bash
streamlit run .\deploy_model.py
```

## Model
This implementation is based on YOLOv10. The original repository for YOLOv10 can be found [here](https://github.com/THU-MIG/yolov10).

## Directory Structure
- `data`: Contains the datasets used for training and testing the models.
- `models`: Includes the model definitions and configurations.
- `predicts`: Stores the prediction results.
- `yolov10`: Main directory for the YOLOv10 implementation.
- `deploy_model.py`: Script to deploy the model using Streamlit.

## Example Usage
After setting up the environment and installing dependencies, you can start using the YOLO model for object detection on your images.

### Sample Image Predictions
<div align="center">
  <img src="./data/image.png">
  <img src="./data/image-1.png">
  <img src="./data/image-2.png">
</div>

## Acknowledgements
This project utilizes the YOLOv10 model from [THU-MIG](https://github.com/THU-MIG/yolov10).

