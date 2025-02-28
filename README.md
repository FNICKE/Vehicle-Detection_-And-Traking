# 🚗 Vehicle Detection and Tracking

## 📌 Overview
This project is designed to detect and track vehicles in video footage using **Computer Vision** and **Machine Learning** techniques. It leverages **TensorFlow Object Detection** and **Kalman Filters** for accurate tracking.

## 🚀 Features
- 🔍 **Vehicle Detection**: Identifies vehicles in video streams.
- 📌 **Object Tracking**: Uses Kalman Filters for tracking movement.
- 🎥 **Multiple Camera Support**: Works with single or multiple video sources.
- ⚡ **Real-time Processing**: Processes video frames efficiently.
- 📈 **Warning System**: Alerts when vehicles enter restricted areas.

## 🛠️ Tech Stack
| Language/Framework | Usage |
|-------------------|-------------------------------|
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | Core programming language |
| ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white) | Computer vision processing |
| ![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white) | Numerical computations |
| ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white) | Object detection model |
| ![MoviePy](https://img.shields.io/badge/-MoviePy-FF0000?logo=video&logoColor=white) | Video processing |

## 📂 Project Structure
```
📁 VehicleDetectionAndTracking
│-- 🚀 VehicleDetectionAndTracking.py
│-- 📹 OneCameraFront.py
│-- 📹 OneCameraRear.py
│-- 📹 TwoCamerasFront.py
│-- 📹 TwoVideoTrackingTest.py
│-- 📂 utilities
│   │-- 🚗 VehicleDetector.py
│   │-- 🚘 VehicleTracker.py
│-- 📄 LICENSE
│-- 📄 README.md
│-- 📄 .gitignore
```

## ▶️ How to Run
### 🔧 Prerequisites
Ensure you have Python installed. Install dependencies:
```bash
pip install numpy opencv-python moviepy tensorflow tqdm
```

### 🏁 Running the Project
#### 1️⃣ Run Detection & Tracking on a Single Front Camera
```bash
python OneCameraFront.py
```
#### 2️⃣ Run Detection & Tracking on a Single Rear Camera
```bash
python OneCameraRear.py
```
#### 3️⃣ Run Detection on Two Front Cameras
```bash
python TwoCamerasFront.py
```
#### 4️⃣ Test Vehicle Tracking with Synthetic Data
```bash
python TwoVideoTrackingTest.py
```

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 🤝 Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

## 📧 Contact
For any inquiries, reach out via email or open an issue in the repository.

---
🚀 Happy Coding! 🎯

