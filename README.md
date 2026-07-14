# LiDAR Interpolation Tracking using Basic AI

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![LiDAR](https://img.shields.io/badge/LiDAR-Point%20Cloud-green)
![Computer Vision](https://img.shields.io/badge/Annotation-Tracking-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project demonstrates **LiDAR object tracking using interpolation** on the **Basic AI Annotation Platform**. The objective is to efficiently annotate moving objects across sequential LiDAR frames by leveraging interpolation-based tracking instead of manually annotating every frame.

The repository includes documentation of the annotation workflow along with a **screen recording** showcasing successful interpolation and tracking results.

---

## 🎯 Objectives

- Reduce manual annotation effort.
- Demonstrate LiDAR object tracking workflow.
- Validate interpolation accuracy on sequential point cloud frames.
- Showcase annotation capabilities of the Basic AI platform.

---

## 🛠 Platform Used

- **Basic AI Annotation Platform**
- LiDAR Point Cloud Annotation
- Interpolation-Based Tracking

---

## 📂 Repository Structure

```
LiDAR-Interpolation-Tracking/
│
├── README.md
├── videos/
   └── tracking_demo.mp4

```

---

## 🚀 Workflow

### 1. Load Dataset
Import the LiDAR sequence into the Basic AI platform.

### 2. Initial Annotation
Create bounding boxes for the target object in the initial frame.

### 3. Apply Interpolation
Use the interpolation tool to automatically propagate annotations across consecutive frames.

### 4. Review Tracking
Inspect generated annotations and correct any inaccuracies when necessary.

### 5. Validate Results
Verify object continuity, bounding box alignment, and tracking consistency.

### 6. Export
Save the completed annotations after validation.

---

## 📹 Demonstration

The repository contains a screen recording demonstrating:

- Dataset loading
- Initial object annotation
- Interpolation process
- Automatic tracking
- Final verified tracking result

Video Location:

```
videos/tracking_demo.mp4
```

---

## ✨ Features

- LiDAR point cloud tracking
- Interpolation-assisted annotation
- Reduced manual labeling effort
- Continuous object tracking
- Annotation validation workflow
- Demonstration video included

---

## 📊 Use Cases

- Autonomous Driving
- ADAS Dataset Preparation
- Robotics
- Smart Mobility
- AI Training Dataset Generation
- LiDAR Annotation Training

---

## 📸 Sample Workflow

```
Frame 1
      │
      ▼
Manual Annotation
      │
      ▼
Interpolation
      │
      ▼
Automatic Tracking
      │
      ▼
Quality Check
      │
      ▼
Final Annotation
```

---

## 📖 Learning Outcomes

Through this project:

- Learned LiDAR point cloud annotation workflow.
- Performed interpolation-based object tracking.
- Understood annotation quality validation.
- Gained practical experience with the Basic AI platform.
- Improved annotation efficiency using interpolation techniques.

---

## 🎥 Output

✔ Successfully tracked objects across sequential LiDAR frames using interpolation.

✔ Screen recording demonstrating the complete tracking workflow has been included.

---

## 📌 Future Improvements

- Multi-object tracking
- Occlusion handling
- Automatic error detection
- Integration with AI-assisted pre-labeling
- Performance benchmarking across different datasets

---

## 👨‍💻 Author

**Soham Banerjee**

- AI & Machine Learning
- LiDAR Annotation
- Computer Vision
- Data Analytics

---

## 📜 License

This project is intended for educational and demonstration purposes.

```
© 2026 Soham Banerjee
```
