# 🔥 Fire and Smoke Detection System

An **AI-powered Fire and Smoke Detection System** designed to automatically detect **fire and smoke** in images and videos using the **YOLO object detection framework**.

The system uses **Deep Learning and Computer Vision** to identify fire and smoke, localize them using bounding boxes, and display confidence scores. It can be applied across different environments, including **mining areas, industrial facilities, residential areas, forests, warehouses, and other safety-critical locations**.

---

## 📌 Project Overview

Fire and smoke can pose serious safety risks in residential, industrial, mining, forest, and other environments. Early detection can help identify potential hazards and support faster response.

This project uses **YOLO-based object detection** to automatically analyze images and video footage and identify the presence of **fire and smoke**.

The system provides:

* 🔥 Fire detection
* 💨 Smoke detection
* 📦 Bounding-box localization
* 📊 Confidence scores
* 🖼️ Image-based detection
* 🎥 Video-based detection

---

## ✨ Features

* 🔥 Detects fire
* 💨 Detects smoke
* 📦 Draws bounding boxes around detected objects
* 📊 Displays detection confidence scores
* 🖼️ Supports image analysis
* 🎥 Supports video analysis
* ⚡ Real-time object detection using YOLO
* 🚁 Can be used with UAV/aerial imagery
* 🌍 Suitable for multiple environments and applications

---

## 🏗️ System Workflow

```text
              Image / Video Input
                     │
                     ▼
             ┌─────────────────┐
             │ Input Processing│
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │   YOLO Model    │
             └────────┬────────┘
                      │
             ┌────────┴────────┐
             ▼                 ▼
          🔥 Fire           💨 Smoke
             │                 │
             └────────┬────────┘
                      ▼
             Bounding Box +
            Confidence Score
                      │
                      ▼
               Detection Result
```

---

## 🤖 Object Detection

The project uses **YOLO (You Only Look Once)** for detecting fire and smoke.

For each detected object, the system provides:

```text
Object Class
     ↓
Fire / Smoke
     ↓
Bounding Box
     ↓
Confidence Score
```

Example:

```text
Fire
Confidence: 92%
```

The bounding box identifies the region of the image or video frame where the detected fire or smoke is located.

---

## 🖼️ Image Detection

The system can analyze images and identify fire and smoke present in the scene.

```text
Input Image
    ↓
YOLO Detection
    ↓
Fire / Smoke Detection
    ↓
Bounding Box
    ↓
Confidence Score
```

This can be used for analyzing photographs, surveillance images, UAV imagery, inspection images, and other visual data.

---

## 🎥 Video Detection

The system can also process videos frame by frame.

```text
Input Video
    ↓
Video Frames
    ↓
YOLO Object Detection
    ↓
Fire / Smoke Detection
    ↓
Bounding Boxes
    ↓
Confidence Scores
```

Detected fire and smoke are displayed directly on the video frames using bounding boxes and confidence scores.

---

## 📂 Project Structure

```text
Fire-and-Smoke-Detection/
│
├── fire_smoke_model.py
├── fire_smoke_test.py
└── README.md
```

### File Description

| File                  | Description                                                     |
| --------------------- | --------------------------------------------------------------- |
| `fire_smoke_model.py` | Contains the YOLO-based fire and smoke detection implementation |
| `fire_smoke_test.py`  | Used for testing the fire and smoke detection system            |
| `README.md`           | Project documentation                                           |

---

## 🛠️ Technologies Used

* **Python**
* **YOLO**
* **Deep Learning**
* **Computer Vision**
* **Object Detection**

---

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/abdultouheed/Fire-and-Smoke-Detection-for-Mining-Safety.git
```

Navigate to the project:

```bash
cd Fire-and-Smoke-Detection-for-Mining-Safety
```

Run the model and test script according to the implementation:

```bash
python fire_smoke_model.py
```

and

```bash
python fire_smoke_test.py
```

> Make sure the required Python dependencies and YOLO model files used by the project are available in your environment.

---

## 🎯 Applications

The Fire and Smoke Detection System can be used in a variety of environments, including:

* ⛏️ **Mining safety monitoring**
* 🏭 **Industrial and factory safety**
* 🏠 **Residential fire monitoring**
* 🏢 **Building and facility surveillance**
* 🌲 **Forest and wildfire monitoring**
* 📦 **Warehouse and storage facility monitoring**
* 🚁 **UAV-based aerial inspection**
* 🚗 **Outdoor and infrastructure monitoring**
* 📹 **CCTV and surveillance systems**
* ⚠️ **General fire and hazard monitoring**

The system can be adapted to different environments by training the detection model with **relevant and diverse fire and smoke datasets**.

---

## 📊 Detection Output

The system provides visual detection results containing:

* **Class:** Fire or Smoke
* **Confidence:** Model confidence score
* **Bounding Box:** Location of the detected object
---

## 🚀 Future Improvements

The system can be further improved by:

* Adding more diverse fire and smoke training data
* Improving detection in low-light environments
* Improving detection under different weather conditions
* Supporting real-time camera feeds
* Supporting real-time UAV camera feeds
* Adding automatic alerts when fire or smoke is detected
* Integrating GPS coordinates with detected hazards
* Developing a real-time monitoring dashboard
* Recording detection events and timestamps
* Deploying the model on edge devices
* Improving detection accuracy through additional training and optimization

---

## 👨‍💻 Author

**Abdul Touheed**

Computer Science Engineer | Machine Learning Enthusiast | Python Developer
