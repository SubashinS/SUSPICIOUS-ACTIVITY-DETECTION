# Suspicious Activity Detection

## Overview

Suspicious Activity Detection is an AI-powered surveillance system designed to identify potentially dangerous, abnormal, or suspicious human activities from video streams. The system leverages computer vision, pose estimation, and machine learning techniques to analyze human body movements and classify behaviors in real time.

This project aims to enhance security monitoring in public spaces, retail stores, educational institutions, workplaces, and smart cities by providing automated detection and alert generation.

---

## Features

* Real-time suspicious activity detection
* Human pose estimation using keypoint extraction
* Behavioral pattern analysis
* Video upload and processing support
* Automated activity classification
* Alert generation for suspicious events
* Scalable architecture for surveillance systems
* Performance analytics and monitoring

---

## Problem Statement

Traditional surveillance systems require continuous human monitoring, which is time-consuming and prone to errors. Security personnel may miss critical incidents due to fatigue or information overload.

This project addresses the challenge by automatically detecting suspicious behaviors from video footage and notifying authorities when unusual activities are observed.

---

## Technologies Used

### Programming Languages

* Python

### Computer Vision & AI

* OpenCV
* MediaPipe
* NumPy
* Pandas
* Scikit-learn

### Machine Learning

* Graph Neural Networks (GNN)
* Activity Classification Models

### Visualization

* Matplotlib
* Seaborn

### Development Tools

* Jupyter Notebook
* Git
* GitHub

---

## System Architecture

1. Video Input Acquisition
2. Human Detection
3. Pose Estimation using MediaPipe
4. Keypoint Extraction
5. Graph Construction
6. Behavioral Feature Generation
7. Suspicious Activity Classification
8. Alert Generation

---

## Dataset

The model is trained using human pose keypoints extracted from surveillance videos.

### Dataset Information

* Total Records: 349,632+
* Data Format: CSV
* Features:

  * Body Keypoints
  * Joint Coordinates
  * Motion Patterns
  * Activity Labels

---

## Workflow

### Step 1: Video Processing

* Read video frames using OpenCV.
* Detect humans in each frame.

### Step 2: Pose Estimation

* Extract body landmarks using MediaPipe.
* Generate skeletal representations.

### Step 3: Feature Extraction

* Calculate spatial relationships between joints.
* Extract motion-based features.

### Step 4: Activity Classification

* Feed extracted features into the trained model.
* Predict whether activity is normal or suspicious.

### Step 5: Alert Generation

* Trigger alerts for suspicious activities.
* Store detection logs for future analysis.

---

## Suspicious Activities Detected

The system can be extended to detect:

* Fighting
* Physical Aggression
* Theft Attempts
* Unauthorized Access
* Loitering
* Vandalism
* Abnormal Crowd Behavior
* Restricted Area Entry

---

## Performance

### Pose Detection

* Human pose estimation accuracy: ~95%

### Real-Time Processing

* Average processing speed suitable for live surveillance systems

### Scalability

* Supports multiple surveillance video sources
* Designed for future cloud deployment

---

## Installation

### Clone Repository

```bash
git clone https://github.com/SubashinS/SUSPICIOUS-ACTIVITY-DETECTION.git
```

### Navigate to Project

```bash
cd SUSPICIOUS-ACTIVITY-DETECTION
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

```bash
python main.py
```


---

## Future Enhancements

* Edge AI deployment
* YOLO-based human detection
* Real-time CCTV integration
* Multi-camera monitoring
* Mobile notifications
* Cloud dashboard
* Federated learning support
* Advanced Graph Neural Networks
* Heatmap generation for security analysis

---

## Applications

* Smart Surveillance Systems
* Retail Security
* Educational Institutions
* Public Transportation
* Airports and Railway Stations
* Industrial Safety Monitoring
* Smart Cities
* Government Security Infrastructure

---

## Author

**Subashin S**

B.Tech Artificial Intelligence & Data Science
Francis Xavier Engineering College, Tamil Nadu

GitHub: https://github.com/SubashinS

---

## License

This project is licensed under the MIT License.

Feel free to use, modify, and contribute to improve the project.
