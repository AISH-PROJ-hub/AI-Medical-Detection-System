# AI-Medical-Detection-System
A CNN-based medical AI system that classifies brain tumors from MRI scans and detects bone fractures with fracture type identification from X-ray images through an interactive Gradio interface.
# 🧠🦴 AI Medical Detection System

An AI-powered medical image analysis system that detects and classifies:

- Brain Tumors from MRI images
- Bone Fractures from X-ray images
- Fracture Types using Deep Learning

The project uses Convolutional Neural Networks (CNNs) built with TensorFlow/Keras and provides an interactive web interface using Gradio.

---

## 📌 Features

### 🧠 Brain Tumor Detection
Classifies MRI scans into:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

### 🦴 Bone Fracture Detection
Detects whether an X-ray image contains:

- Fracture
- Normal Bone

### 🦴 Fracture Type Classification
If a fracture is detected, the system further classifies it into:

- Avulsion
- Comminuted
- Dislocation
- Greenstick
- Hairline
- Impacted
- Longitudinal
- Oblique
- Pathological
- Spiral

---

## 🚀 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pillow
- Gradio
- Google Colab

---

## 📂 Project Structure

```text
AI-Medical-Detection/
│
├── app.py
├── README.md
├── requirements.txt
│
├── models/
│   ├── brain_model.h5
│   ├── fracture_model.h5
│   └── fracture_type_model.h5
│
├── notebooks/
│   └── training.ipynb
│
├── screenshots/
│   └── demo.png
│
└── datasets/
```

---

## 🏥 Datasets Used

### Brain Tumor MRI Dataset
Classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor

Source:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

### Bone Fracture Dataset

Classes:

- Normal
- Fractured

Fracture Types:

- Avulsion
- Comminuted
- Dislocation
- Greenstick
- Hairline
- Impacted
- Longitudinal
- Oblique
- Pathological
- Spiral

Source:
https://www.kaggle.com

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Medical-Detection.git
cd AI-Medical-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

Or in Google Colab:

```python
!python app.py
```

A Gradio interface will launch where users can upload MRI or X-ray images for prediction.

---

## 🧪 Model Architecture

The project uses CNN-based architectures consisting of:

- Convolution Layers
- Max Pooling Layers
- Dense Layers
- Softmax Classification

Image Size:

```text
128 × 128
```

Activation Functions:

```text
ReLU
Softmax
```

Optimizer:

```text
Adam
```

Loss Function:

```text
Categorical Crossentropy
```

---

## 📊 Results

### Brain Tumor Model
- Multi-class classification
- Detects tumor type
- Validation accuracy dependent on dataset split

### Fracture Detection Model
- Detects fractured vs normal bones

### Fracture Type Model
- Classifies 10 different fracture types

---

## 🎯 Applications

- Early disease detection
- Medical image screening
- Educational and research purposes
- AI-assisted diagnosis support

---

## ⚠️ Disclaimer

This project is developed for academic and research purposes only.

It is not intended to replace professional medical diagnosis, treatment, or consultation.

Always seek advice from qualified healthcare professionals for medical decisions.

---

## 👩‍💻 Project Team

### Aishwarya R S — Team Lead
**Roles & Responsibilities:**
- Team Lead
- Bone Fracture AI Developer
- Model Development and Training
- Presentation Design and Delivery
- Project Planning and Coordination

### Bhuvanesh S — Coordinator
**Roles & Responsibilities:**
- Project Coordinator
- Brain Tumor AI Developer
- Model Development and Training
- Debugging and Testing
- Performance Optimization

---

## 🤝 Team Contribution

This project was collaboratively developed by **Aishwarya R S** and **Bhuvanesh S** as part of an AI-based healthcare solution for medical image analysis.

### Contributions

| Team Member | Contribution |
|------------|-------------|
| **Aishwarya R S** | Team Leadership, Bone Fracture Detection Model, Project Presentation, Documentation |
| **Bhuvanesh S** | Project Coordination, Brain Tumor Classification Model, Debugging, Testing, Model Optimization |

---
## ⭐ Future Improvements

- Confidence Score Prediction
- Grad-CAM Visualization
- PDF Report Generation
- Multi-Disease Detection
- Cloud Deployment
- Mobile Application Integration

---

## 📜 License

This project is licensed under the MIT License.
