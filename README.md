# Pomegranate Disease Detection Using YOLOv12

## Overview

This project presents a deep learning-based approach for detecting pomegranate diseases using the YOLOv12 object detection model. The objective is to assist farmers and agricultural researchers in identifying diseases at an early stage, enabling timely intervention and improved crop management.

The model was trained and evaluated on annotated images of pomegranate fruits across multiple disease categories. Different YOLOv12 variants were compared to identify the best-performing model in terms of detection accuracy and efficiency.

---

## Problem Statement

Manual identification of pomegranate diseases is time-consuming and depends on expert knowledge. This project aims to automate disease detection using computer vision and deep learning techniques to provide fast and accurate predictions.

---

## Dataset

The dataset contains **5,099 annotated images** belonging to five classes:

- Healthy
- Bacterial Blight
- Anthracnose
- Cercospora Fruit Spot
- Alternaria Fruit Spot

Due to GitHub file size limitations, the dataset is not included in this repository.

---

## Model

- YOLOv12
- Variants Evaluated:
  - YOLOv12n
  - YOLOv12s
  - YOLOv12m
  - YOLOv12l
  - YOLOv12x

---

## Training Configuration

- Image Size: 640 × 640
- Epochs: 100
- Batch Size: 16
- Optimizer: Adam
- Learning Rate: 0.001
- Learning Rate Scheduler: Cosine Annealing

---

## Performance

| Model | Precision | Recall | mAP@0.5 | mAP@0.5:0.95 |
|--------|----------:|-------:|---------:|-------------:|
| YOLOv12n | 91.53% | 93.45% | 96.98% | 85.85% |
| YOLOv12s | 93.00% | 93.57% | 96.95% | 86.20% |
| YOLOv12m | 92.38% | 91.45% | 96.56% | 85.66% |
| YOLOv12l | 92.80% | 93.40% | 96.90% | 86.00% |
| YOLOv12x | 90.40% | 89.80% | 94.80% | 81.80% |

The YOLOv12s model achieved the best balance between accuracy and computational efficiency.

---

## Technologies Used

- Python
- YOLOv12
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## Repository Structure

```
pomegranate-disease-detection-yolov12/
│
├── YOLOv12s.ipynb
├── pome.yaml
├── requirements.txt
├── README.md
├── research-paper.pdf
└── mini-project-report.pdf
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/kavanagowdaa/pomegranate-disease-detection-yolov12.git
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook or Google Colab.

---

## Future Enhancements

- Real-time disease detection
- Mobile application integration
- Edge device deployment
- Support for additional crop diseases
- Cloud-based prediction service

---

## Publication

This project was presented at the **3rd International Conference on Emerging Computation and Information Technologies (ICECIT 2025)**.

**Title:**  
**Pomegranate Disease Detection Using YOLOv12**

---

## Author

**Kavana B A**

B.Tech Computer Science and Engineering (Artificial Intelligence & Machine Learning)

Presidency University
