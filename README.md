# Real-Time-Face-Detection
This project demonstrates a real-time face detection application using the YOLOv8 model, Streamlit for UI, and OpenCV for webcam access. The application detects faces from the webcam feed and displays them in a user-friendly interface.

## Features
* Real-time face detection using a YOLOv8 model.
* Streamlit interface with Start and Stop buttons for controlling the webcam feed.
* Displays bounding boxes and confidence scores for detected faces.

## Requirements
Make sure to have the following installed: </br>
* Python 3.8 or higher
* Libraries: streamlit, opencv-python, Pillow, numpy, ultralytics, supervision, huggingface_hub

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Shah114/Realtime-Face-Detection.git
   cd realtime-face-detection
   ```

2. Install the required dependencies:
   ```python
   pip install -r requirements.txt
   ```

3. Download the YOLOv8 face detection model:
The model will be downloaded automatically from Hugging Face during runtime. Ensure you have an active internet connection.

## Running the Application
1. Launch the Streamlit app:
   ```python
   streamlit run app.py
   ```

2. Use the interface to start and stop the webcam feed.

3. Press the "Start" button to begin detection. Press "Stop" to end the detection.

## File Structure
* app.py: Main Python file for the Streamlit application.
* requirements.txt: List of Python dependencies.

## Screenshots
