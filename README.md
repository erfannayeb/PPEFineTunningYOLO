# PPE Detection with YOLOv8s

This project focuses on training a **YOLOv8s model** to detect **Personal Protective Equipment (PPE)** such as helmets, gloves, and safety vests in images. The model has been fine-tuned on a custom dataset to detect various types of PPE in different scenarios.

## Project Details

- **Base Model**: YOLOv8s
- **Fine-tuning Method**: Training YOLOv8s on a custom PPE dataset.
- **Framework**: Ultralytics YOLO (using the `ultralytics` package)
- **Image Processing Library**: OpenCV, Matplotlib
- **Purpose**: Train a model to detect PPE in images.

## Features

- **Model Training**: Fine-tune YOLOv8 on a custom PPE dataset.
- **Custom Dataset**: The model is trained specifically for PPE detection, improving its performance on PPE-related tasks.
- **Visualization**: During inference, the detected PPE items are visualized with bounding boxes and labels.

## Files
- **PPE_YOLO.ipynb**
- **README.md**
