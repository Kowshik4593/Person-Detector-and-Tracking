# Therapist and Child Detection and Tracking

## Project Description

This project implements a person detection and tracking system, specifically designed to identify children with Autism Spectrum Disorder (ASD) and therapists in a video. The system assigns unique IDs to each detected person and tracks them throughout the video. It also handles cases where a person leaves and re-enters the frame, ensuring consistent ID assignment.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- SciPy
- YOLOv4 pre-trained model files (`yolov4.cfg`, `yolov4.weights`)
- COCO class labels file (`coco.names`)

## Installation

Before running the code, install the required dependencies using the following command:

```bash
pip install -r requirements.txt
