# yolov8-helmet-detection
YOLOv8 object detection for traffic helmet detection. 92-98% accuracy after 100 epochs.
### README.md Content
```markdown
# YOLOv8 Helmet Detection

## Overview
Real-time object detection system trained to identify traffic helmets and compliance with safety regulations.

## Performance
- **Accuracy**: 92-96% after 20 epochs
- **Model**: YOLOv8 (custom-trained)
- **Dataset**: Custom helmet detection dataset

## Key Metrics
- mAP (Mean Average Precision): [Your score]
- IoU (Intersection over Union): [Your score]
- Precision: [Your score]
- Recall: [Your score]

## Tech Stack
- YOLOv8 (Ultralytics)
- Python, OpenCV
- TensorFlow/PyTorch

## Training Details
- **Framework**: YOLOv8
- **Epochs**: 20
- **Batch Size**: [Your batch size]
- **Learning Rate**: [Your LR]
- **Dataset Size**: [Number of images]

## Installation
```bash
pip install ultralytics opencv-python
```

## Usage
```python
from ultralytics import YOLO

model = YOLO('best.pt')
results = model.predict(source='video.mp4')
```

## Author
Varaha Venkat Karri | Quantum Robotics Internship (Jan-Apr 2025)
