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

├── app.py # Flask application 
├── detector.py # YOLOv8 detection and tracking module
├── yolov8n.pt # YOLOv8 pretrained weights
├── requirements.txt # Python dependencies
├── Dockerfile # Docker configuration
├── static/sample_videos/ # Example videos for testing
├── templates/index.html # Web UI template (if used) ```



