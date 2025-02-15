# Object_Detection_System

## 🚀 Project Overview
This project implements an **Object Detection System** using deep learning models such as **YOLOv8, Faster R-CNN, SSD**, and others. The system is capable of detecting multiple objects in images and videos in real time, providing accurate bounding boxes around detected objects.

## 🔥 Features
- ✅ **Real-time object detection** from images, videos, and webcam streams
- ✅ **Supports multiple models** (YOLOv8, Faster R-CNN, SSD, etc.)
- ✅ **Custom dataset support** for training new models
- ✅ **Performance evaluation** with mAP, precision, recall
- ✅ **Easy-to-use API** for inference & training

---

## 📂 Project Structure
```
📂 object-detection-system  
│── 📂 datasets/          # Dataset files (linked or stored)  
│── 📂 models/            # Pre-trained or trained models  
│── 📂 src/               # Source code for training & inference  
│── 📂 configs/           # Configuration files  
│── 📂 notebooks/         # Jupyter Notebooks for visualization & experimentation  
│── 📂 results/           # Output images & performance metrics  
│── requirements.txt      # Dependencies  
│── README.md            # Project description & setup instructions  
│── setup.py             # If packaging as a Python module  
│── LICENSE              # License information  
│── .gitignore           # Ignore unnecessary files  
```

---

## 🛠 Installation
1️⃣ Clone the repository:
```bash
git clone https://github.com/ygunjangyl/Object_Detection_System.git  
cd Object_Detection_System  
```

2️⃣ Install dependencies:
```bash
pip install -r requirements.txt  
```

3️⃣ Download pre-trained models (if needed):
```bash
mkdir models && cd models
# Example for YOLOv8
wget https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt
```

---

## 🎯 Usage
### **Run Object Detection on an Image**
```bash
python detect.py --image test.jpg --model yolov8.pt
```

### **Run Object Detection on a Video**
```bash
python detect.py --video input.mp4 --model yolov8.pt
```

### **Real-Time Detection Using Webcam**
```bash
python detect.py --video 0 --model yolov8.pt
```

---

## 🏋️ Training a Custom Model

Dataset should be structured in **COCO or Pascal VOC format**.

---

## 📊 Results & Performance
- Model: **YOLOv8n**
- Dataset: **COCO 2017**
- mAP@50: **78.6%**


### 📸 Sample Detections
**Image 1:**  
![Detection 1](results/Screenshot (19).png)  

**Image 2:**  
![Detection 2](results/Screenshot (36).png)  

**Image 3:**  
![Detection 3](results/Screenshot (74).png)  

**Image 4:**  
![Detection 2](results/Screenshot (84).png)  

**Image 5:**  
![Detection 3](results/Screenshot (103).png)  



---







