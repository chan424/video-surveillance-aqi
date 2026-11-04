# Video Surveillance AQI Integration

Computer vision system that detects pollution sources from video feeds and integrates the insights with Air Quality Index (AQI) monitoring.

## Overview
Uses CCTV or camera streams to identify industrial smoke, heavy traffic, construction dust, or other visible pollution contributors. Correlates visual detections with nearby AQI sensor data for smarter environmental monitoring.

## Features
- Object detection for vehicles, smoke plumes, and dust events
- Real-time or batch video analysis
- Overlay of detection results on AQI maps
- Alert generation for anomalous pollution events
- Support for edge deployment (e.g., on cameras or local servers)

## Tech Stack
- **CV Framework**: OpenCV, YOLO (v5/v8), or Detectron2
- **Language**: Python
- **Deep Learning**: PyTorch or TensorFlow
- **Integration**: REST APIs to AQI data sources

## Pipeline
1. Video ingest (file, RTSP stream, or webcam)
2. Frame sampling and preprocessing
3. Detection and classification of pollution-related objects/events
4. Aggregation and correlation with AQI readings
5. Visualization and reporting

## Getting Started
```bash
git clone https://github.com/chan424/video-surveillance-aqi.git
cd video-surveillance-aqi
pip install -r requirements.txt
python detect.py --source video.mp4
```

## Datasets
Custom or public datasets of urban pollution scenes recommended for training.

## Applications
- Smart city pollution tracking
- Industrial compliance monitoring
- Traffic-related AQI correlation studies

## License
MIT
