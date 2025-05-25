# Survivor Detection Drone

Object detection system using TensorFlow to identify human survivors in disaster zones from drone footage.

## 🛰️ Use Case
Deployed on UAVs for post-earthquake search and rescue missions. Detects humans using aerial imagery and draws bounding boxes.

## 🧠 Model
- Base: TensorFlow Object Detection API (SSD / YOLO)
- Input: Real-time or image/video feed
- Output: Bounding boxes and confidence scores for detected humans

## 📁 Structure
- `notebooks/`: Training and fine-tuning notebook
- `scripts/`: Detection script (real-time or single image)
- `models/`: Exported trained model
- `assets/`: Sample input/output images
- `data/`: Training dataset (images and annotations)

## 🛠️ How to Use
1. Place dataset in `data/`
2. Train model via `detection_notebook.ipynb`
3. Run detection with `scripts/detect.py`

## 🔮 Future Work
- Integrate with drone’s camera feed
- Trigger GPS tagging and alert systems
