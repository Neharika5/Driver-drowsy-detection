
Overview: This Python-based driver alert system utilizes facial landmark detection to track eye blinks and triggers an alert in cases of detected drowsiness.

Features: It employs dlib for face detection, facial landmark identification, OpenCV (cv2) for image and video processing, imutils for frame resizing, scipy for distance calculations, and pygame.mixer for audio alerts.

Requirements: To run the script, ensure Python 3.x and the required Python packages (dlib, OpenCV (cv2), imutils, scipy, pygame) are installed.

Usage: Clone the repository, install dependencies using pip install -r requirements.txt, and execute the script with python driver_alert_system.py. Properly position and ensure the functionality of the webcam for facial monitoring.

Instructions: Fine-tune sensitivity via the thresh and frame_check variables, adjust lighting for accurate facial landmark detection, and customize alert sounds by replacing music.wav.

Contributions: Contributions are welcome! Fork the repository, make improvements, or suggest additional features through pull requests.
