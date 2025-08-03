# 🚀 YOLOv5 Face Detection – MLOps Phase 1

This repository showcases a **real-time face detection pipeline** using a custom-trained [YOLOv5](https://github.com/ultralytics/yolov5) model. It’s part of a larger **AI + Cloud + DevOps** initiative demonstrating how models are developed, versioned, and deployed from local to production environments.

## 📦 Project Overview

- ✅ Trained YOLOv5 face detection model
- 🎞️ Sample demo video: `face-detect.webm`
- 🗂️ Face dataset (labeled with Roboflow)
- 🧠 Inference and training setup
- 📁 YOLOv5 source code included for reproducibility

## 🧩 Directory Structure

face-detection-repo/
├── face-dataset/ # Labeled images and dataset.yaml
├── yolov5/ # YOLOv5 codebase (Ultralytics clone)
├── face-detect.webm # Sample inference video
├── command_to_train_model.txt # Training command used
├── README.md
└── .gitignore


## ⚙️ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/face-detection-repo.git
2. **Install Dependencies:**
cd yolov5
pip install -r requirements.txt
3. **Run Inference:**
python detect.py --weights ../best.pt --source ../face-detect.webm

☁️ MLOps & DevOps Context
While this is a computer vision project at its core, it's designed with DevOps principles in mind:
    🐳 Can be containerized with Docker for portable inference
    🛠️ Future plans include deployment on Jetson Nano and AWS EC2
    📈 Scalable monitoring and visualization using Grafana & Prometheus
    ⚙️ Will be CI/CD integrated in upcoming phases (model updates & edge deployments)

📹 Demo
✍️ Author
Angad Bandal
Cloud & DevOps Engineer | AI Enthusiast
LinkedIn • GitHub

📜 Credits
    YOLOv5: Ultralytics
    Dataset Labeling: Roboflow


