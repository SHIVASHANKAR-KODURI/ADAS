# ADAS - Advanced Driver Assistance System 🚗

Welcome to the **ADAS (Advanced Driver Assistance System)** project!  
This project is developed by **SHIVA SHANKAR KODURI** as part of an academic and practical implementation to enhance road safety and driving support using computer vision techniques.

---

## 📌 Project Overview

This project demonstrates key modules of an ADAS system using Python and OpenCV. It includes the following core functionalities:

- **Lane Detection**: Identifies lane lines on the road and provides visual lane boundaries.
- **Object Detection**: Detects and classifies objects (e.g., cars, pedestrians, traffic signs) in real-time.
- **Driver Assistance**: Core logic to combine lane detection and object detection for ADAS-level insights.

---

## 📁 Project Structure

```bash
ADAS/
│
├── lane_detection/
│   ├── lane_detection.py
│   └── test_videos/
│       └── sample_lane_video.mp4
│
├── object_detection/
│   ├── object_detection.py
│   ├── yolov5s.pt              # Pre-trained YOLOv5 model
│   └── test_images/
│       └── sample_object.jpg
│
├── utils/
│   ├── draw_utils.py
│   └── config.py
│
├── README.md
└── requirements.txt
````

---

## 🧠 Technologies Used

* **Python**
* **OpenCV**
* **YOLOv5** (You Only Look Once - Object Detection)
* **NumPy**
* **Matplotlib** (optional for plotting)
* **Google Colab** for training and testing

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/SHIVASHANKAR-KODURI/ADAS.git
cd ADAS
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run Lane Detection

```bash
cd lane_detection
python lane_detection.py
```

### 4. Run Object Detection

```bash
cd object_detection
python object_detection.py
```

---

## 📊 Features

* ✅ Real-time lane tracking
* ✅ Object detection using YOLOv5
* ✅ Overlay of lanes and bounding boxes
* ✅ Extensible for alerting and automation modules

---

## 📽️ Sample Output
**Lane Detection**

<img width="515" height="296" alt="image" src="https://github.com/user-attachments/assets/7ba68f13-9b6b-4de6-b138-112e417346d8" />

**Object Detection**
<img width="800" height="534" alt="image" src="https://github.com/user-attachments/assets/bdee1916-aa4a-4a03-aee5-b680a20edcd6" />


---

## 🛠️ To-Do / Future Enhancements

* [ ] Traffic sign recognition
* [ ] Collision warning system
* [ ] Driver drowsiness detection
* [ ] Integration with Raspberry Pi or Jetson Nano

---

## 👨‍💻 Author

**SHIVA SHANKAR KODURI**

* AIML Student | SR University
* Vice Chair, Digital Design and Branding Club
* 📧 [shivashankarkoduri@gmail.com](mailto:shivashankarkoduri@gmail.com)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

