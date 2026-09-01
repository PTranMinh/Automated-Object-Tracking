# [ AUTOMATED OBJECT TRACKING SYSTEM ]
### Dynamic Vehicle Tracking with YOLOv8 & DeepSORT

![Project Banner](banner.png)  <!-- ĐẶT ẢNH banner.png VÀO ĐÂY -->

<!-- Badges section -->
[![YOLOv8](https://img.shields.io/badge/Model-YOLOv8-blue.svg?style=flat-square&logo=opencv)](https://github.com/ultralytics/ultralytics)
[![DeepSORT](https://img.shields.io/badge/Tracker-DeepSORT-green.svg?style=flat-square)](https://github.com/nwojke/deep_sort)
[![Python](https://img.shields.io/badge/Made%20with-Python-gold.svg?style=flat-square&logo=python)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Deployed-success.svg?style=flat-square)](#)

---

## 🚀 PROJECT OVERVIEW

Welcome to the **Automated Object Tracking System** repository by PTranMinh. This project implements a cutting-edge pipeline combining the object detection precision of **YOLOv8** with the robust object association of **DeepSORT** (Deep Simple Online and Realtime Tracking).

Designed primarily for vehicle tracking in diverse environments, this system can simultaneously track multiple cars, trucks, and other vehicles across video frames, providing stable unique IDs and trajectory prediction.

### 🌟 Key Features

*   **Real-time Multi-Object Tracking:** Stable tracking of numerous dynamic objects.
*   **High-Accuracy Detection:** Powered by the state-of-the-art YOLOv8 model.
*   **Robust Data Association:** DeepSORT handles occlusions and maintains ID consistency.
*   **Advanced Visualization:** Clear bounding boxes with class labels, IDs, confidence, and path trajectories.
*   **System Telemetry:** Integrated display of active tracks, FPS, and detection summaries.

---

## 🛠️ SYSTEM ARCHITECTURE & PIPELINE

This high-performance tracking system follows a seamless data flow as visualized in our banner image:

`[ Video/Camera Feed ]` $\rightarrow$ `[ YOLOv8 Detector ]` $\rightarrow$ `[ Bounding Boxes & Features ]` $\rightarrow$ `[ DeepSORT Association ]` $\rightarrow$ `[ Tracked Output with Unique IDs ]`

The banner image (see above) provides a detailed visualization of the system telemetry, object classification, and trajectory lines deployed in a complex dusk highway environment.

---

## 💻 GETTING STARTED

### Prerequisites

Ensure you have a recent version of Python (3.8+) and necessary libraries.

### Installation

1.  **Clone the cleaned repository:**
    ```bash
    git clone [https://github.com/PTranMinh/Automated-Object-Tracking.git](https://github.com/PTranMinh/Automated-Object-Tracking.git)
    cd Automated-Object-Tracking
    ```

    ```

---

## 🎥 USAGE DEMO

Run the tracking demonstration on the provided sample video:

```bash
python track_demo.py --source data/video_demo.mp4
