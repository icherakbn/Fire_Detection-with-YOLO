
# 🔥 Fire and Smoke Detection: YOLOv5 vs YOLOv8 vs YOLOv10

A comparative computer vision project evaluating three YOLO architectures for detecting **fire and smoke** in images.

---

## 📌 Project Overview

Early detection of fire and smoke is important for improving wildfire monitoring and reducing potential damage.

This project explores object detection using three versions of the YOLO family:

- YOLOv5
- YOLOv8
- YOLOv10

The models were trained using a Kaggle fire and smoke detection dataset. Their performance was evaluated using object-detection metrics to study their detection accuracy and overall performance.

---

## 🎯 Objectives

- Detect fire and smoke in images.
- Train and evaluate three YOLO architectures.
- Compare precision, recall, and mean Average Precision (mAP).
- Analyze model performance and detection results.
- Explore the strengths and limitations of different YOLO versions.

---

## 📂 Dataset

| Attribute | Description |
|---|---|
| Source | Kaggle |
| Task | Object Detection |
| Classes | Fire and Smoke |
| Annotation Format | YOLO-compatible |
| Input Image Size | 640 × 640 pixels |

*Add the original Kaggle dataset link and dataset split details here.*

---

## ⚙️ Methodology

The project follows these main steps:

1. Dataset preparation and configuration.
2. Model setup and training.
3. Validation and performance evaluation.
4. Visualization of training results.
5. Comparison of evaluation metrics.

### Model Configuration

| Parameter | Configuration |
|---|---|
| Image Size | 640 × 640 |
| Epochs | 50 |
| YOLOv5 Batch Size | 32 (first recorded run) |
| YOLOv10 Batch Size | 64 |
| Framework | Ultralytics |

*Training configurations may differ between experiments. Refer to the notebooks for the exact settings.*

---

## 📊 Evaluation Results

The following values were recovered from the available notebook validation outputs.

| Model | Precision | Recall | mAP@50 | mAP@50–95 |
|---|---:|---:|---:|---:|
| YOLOv5 | 0.647 | 0.417 | 0.477 | 0.233 |
| YOLOv8 | To be added | To be added | To be added | To be added |
| YOLOv10 | 0.550 | 0.391 | 0.412 | 0.229 |

The reported YOLOv5 and YOLOv10 validation outputs each contain **75 images and 156 object instances**.

**Note:** These results should be interpreted in the context of their individual training configurations. A controlled comparison requires consistent data splits, training settings, and evaluation conditions.

---

## 🖼️ Visual Results

The experiments include the following visualizations:

- Training and validation loss curves.
- Precision and recall curves.
- Confusion matrices.
- Predicted bounding boxes.
- Validation batch predictions.

*Add selected screenshots from the notebooks here.*

---

## 🧰 Technologies Used

- Python
- PyTorch
- Ultralytics
- YOLOv5, YOLOv8 and YOLOv10
- OpenCV
- Matplotlib
- Jupyter Notebook
- Kaggle

---

## 📁 Repository Structure

```text
Fire-Smoke-Detection-YOLO-Comparison/
│
├── notebooks/
│   ├── fire_detection_yolov5.ipynb
│   ├── fire_detection_yolov8.ipynb
│   └── fire_detection_yolov10.ipynb
│
├── results/
│   ├── metrics/
│   └── visualizations/
│
├── README.md
└── requirements.txt
```

*The structure above is the recommended organization for the repository.*

---

## 🚀 Future Improvements

- Standardize training configurations for a fairer comparison.
- Evaluate all models on the same independent test set.
- Include inference speed and model size comparisons.
- Improve detection performance in challenging lighting conditions.
- Explore real-time fire and smoke detection.

---

## 👩‍💻 Author

**Ichrak Benamara**  
AI Engineer | AI Trainer

- [GitHub Profile](https://github.com/icherakbn)

---

*Exploring computer vision for smarter and earlier fire detection.* 🔥
