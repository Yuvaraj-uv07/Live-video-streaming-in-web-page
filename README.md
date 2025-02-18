# Flask Live Video Streaming

## Overview
This project enables live video streaming on a web page using Flask and OpenCV. It captures real-time video from a webcam and streams it over a web interface.

## Features
- Real-time video streaming using Flask
- Captures video from a webcam
- Streams video in MJPEG format
- Uses Flask-Ngrok for easy public access

## Technologies Used
- **Backend:** Flask, OpenCV, Flask-Ngrok
- **Frontend:** HTML (served via Flask Response)

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flask-live-streaming.git
   ```
2. Navigate to the project directory:
   ```bash
   cd flask-live-streaming
   ```
3. Install dependencies:
   ```bash
   pip install flask opencv-python flask-ngrok
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and visit:
   ```
   http://localhost:5000
   ```

## Future Improvements
- Implement user authentication for secured streaming
- Support multiple camera sources
- Add recording and playback functionality


Feel free to contribute by reporting issues or suggesting features!

