# Yolov8-object-detection-and-tracking-region-wise
Flask web app for real-time YOLOv8 object detection, tracking, region-wise counting, and speed estimation in videos. Includes Docker deployment and sample videos.



# YOLOv8 Object Detection, Tracking, Region Counting, and Speed Estimation

This project implements a Flask web application that uses a YOLOv8 model for real-time object detection, tracking, region-wise counting, and speed estimation in videos.

---

## ✨ Features

- Object detection and tracking (YOLOv8)
- Region-based people counting (entry line)
- Speed estimation in km/h
- Flask web UI for video upload and visualization
- Dockerized for easy deployment

---
## 📁 Project Structure

project_root/
├── app.py                # Main Flask application file
├── detector.py           # YOLOv8 object detection and tracking module
├── yolov8n.pt            # Pretrained YOLOv8 model weights
├── requirements.txt      # Python dependencies list
├── Dockerfile            # Docker configuration file
├── static/               # Static files directory
│   └── sample_videos/    # Sample videos for testing
└── templates/            # HTML templates directory
    └── index.html        # Main web UI template
## Project Structure

```plaintext
project_root/
├── app.py                # Main Flask application file
├── detector.py           # YOLOv8 object detection and tracking module
├── yolov8n.pt            # Pretrained YOLOv8 model weights
├── requirements.txt      # Python dependencies list
├── Dockerfile            # Docker configuration file
├── static/               # Static files directory
│   └── sample_videos/    # Sample videos for testing
└── templates/            # HTML templates directory
    └── index.html        # Main web UI template
```


