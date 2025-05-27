
# YOLOv8 Brain Tumor Segmentation

This repository provides a Jupyter notebook for performing **brain tumor segmentation** using the **YOLOv8** model from the Ultralytics framework.

## Features

- Implements YOLOv8 for precise tumor segmentation in medical images.
- Covers data preparation, model training, and inference.
- Includes visualization of predictions and evaluation metrics.

## Requirements

Install the required dependencies:

```bash
pip install ultralytics
```

## Dataset Structure

The dataset should follow this directory structure (YOLO format):

```
datasets/
├── images/
│   ├── train/
│   ├── val/
│   └── test/
├── labels/
│   ├── train/
│   ├── val/
│   └── test/
```

Each image should have a corresponding `.txt` label file in YOLO format.

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/brain-tumor-yolov8.git
cd brain-tumor-yolov8
```

2. Open the Jupyter notebook:

```bash
jupyter notebook segmentationwithyoyo.ipynb
```

3. Follow the steps to train and evaluate the model.

## Training Results

*The notebook includes real-time plots of training metrics such as loss, mAP, precision, and recall.*

Example output:

- Training mAP: 0.87
- Validation Accuracy: 0.84
- IOU score: 0.79

*(Note: These results are for illustration and may vary depending on the dataset used.)*

## Visualization

The notebook visualizes model predictions overlayed on MRI images for clear interpretation of tumor regions.

## Acknowledgments

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- Jupyter for interactive experimentation

---
