# Human Detection Web Application

## Overview

This is a real-time Human Detection web application built with Python and Flask. It uses computer vision to detect humans and upper bodies in images, videos, and webcam feeds. The system estimates distances and provides real-time audio guidance to assist safe navigation.

---

## Features

- Human and upper-body detection  
- Distance estimation to detected entities  
- Real-time webcam support  
- Audio feedback for safe navigation  
- Supports image and video file inputs  
- Responsive dark-themed UI with Bootstrap

---

## Tech Stack

- **Python 3** – Backend logic  
- **Flask** – Web framework  
- **OpenCV** – Human/object detection  
- **imutils** – Image processing  
- **gTTS** – Text-to-speech feedback  
- **pygame** – Audio playback  
- **Bootstrap 5** – UI design  
- **JavaScript** – UI interactions  

---

## Folder Structure

/ (root)
│
├── main.py # Core logic and Flask server
├── requirements.txt # Python dependencies
├── image.JPG # Sample image for testing
├── video.mp4 # Sample video for testing
├── bootstrap.min.css # Dark-themed Bootstrap CSS
├── bootstrap.min.js # Bootstrap JavaScript bundle
├── bold-and-dark.js # Custom JS for UI polish
│
├── templates/ # HTML templates
│ ├── home.html
│ ├── image.html
│ ├── video.html
│ └── webcam.html
│
└── static/
└── assets/
├── bootstrap/
│ ├── css/bootstrap.min.css
│ └── js/bootstrap.min.js
└── js/
└── bold-and-dark.js

---

### Install dependencies

```bash
pip install -r requirements.txt
```
### Run the Application

Start the Flask application using:

```bash
python main.py
```

Once the app is running, the server will be available at: `http://127.0.0.1:5000`

## Usage

### Open in Browser

Go to:  
[http://127.0.0.1:5000/home](http://127.0.0.1:5000/home)

---

### Choose a Detection Mode

- **IMAGE**: Upload or use sample images  
- **VIDEO**: Upload video files for analysis  
- **WEB CAM**: Enable real-time detection via webcam  

---

### The System Will:

- Detect humans and upper bodies  
- Estimate distance to detected entities  
- Provide real-time audio feedback with movement guidance  
  _Example: "Person ahead, move left"_

---

## Cleanup

Stop the server anytime with:

```bash
Ctrl + C
```

---

### **Author**  
**Izaan Ibrahim Sayed**  
Email: izaanahmad37@gmail.com  
GitHub: [github.com/izaanahmad37](https://github.com/izaanibrahim37) 
