# SportSight
SportSight is a deep learning + IoT-based system for **real-time tracking of sports equipment availability** for students, removing the need for manual checking.

## Features

- Object detection for sports equipment
- Camera sensor integration for real-time updates
- Flask-based simple user interface
- Live equipment availability tracking

## Installation

Clone the repository:
```
https://github.com/ManojnaMBhat/SportSight.git
cd SportSight
```
## YOLO Weights Download
```
Download the `yolov3.weights` file (approx 248MB) from the official YOLO website:

[Download yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)

Place the downloaded `yolov3.weights` file in the project folder before running:
```
## Install dependencies:
```
pip install -r requirements.txt
```

## Usage
1️⃣ Install the "IP Webcam" app on your Android phone from the Play Store.  
2️⃣ Open the app, start the server, and note the **IP webcam URL** shown (e.g., `http://192.168.0.105:8080/video`).  
3️⃣ Copy this URL and paste it inside the Python file(yolo_opencv.py) where the webcam URL is required. 

4️⃣ Run the project:

```
python yolo_opencv.py
```
Open in your browser:
```
http://localhost:5000
