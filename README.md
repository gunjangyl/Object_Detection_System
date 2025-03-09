# Object_Detection_System

## 🚀 Project Overview
This project implements an **Object Detection System** using deep learning models such as **YOLOv8, Faster R-CNN, SSD**, and others. The system is capable of detecting multiple objects in images and videos in real time, providing accurate bounding boxes around detected objects.

## 🔥 Features
- ✅ **Real-time object detection** from images, videos, and webcam streams
- ✅ **Supports multiple models** (YOLOv8, Faster R-CNN, SSD)
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

Dataset is structured in **COCO**.

---

## 📊 Results & Performance
- Model: **YOLOv8n**
- Dataset: **COCO 2017**
- mAP@50: **78.6%**


### 📸 Sample Detections
<br><br>
**Image 1:**  
![Image](https://github.com/user-attachments/assets/c094f968-df5b-497a-9174-0f6bbd06a977)
<br>
**Image 2:**  
![Image](https://github.com/user-attachments/assets/00e5a44a-3886-4052-a3dc-b4f687f209c7)
<br>
**Image 3:**  
![Image](https://github.com/user-attachments/assets/10446431-acd6-450d-a3a5-3d980619c5ba)
<br>
**Image 4:**  
![Image](https://github.com/user-attachments/assets/ac73a6c9-9fe1-4046-b3c7-1e38b1697102)




---







