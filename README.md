# Driver Drowsiness Detection System

## Overview
Ever been on a long drive and felt your eyelids getting heavy? The Driver Drowsiness Detection System is here to help. This real-time application keeps an eye on your alertness level, analyzing facial expressions and detecting signs of drowsiness. If it spots trouble, it plays a sound alert to help you stay awake and safe. Plus, it comes with face recognition-based login for added security.

## Features
- Real-time monitoring: Tracks your face and eyes to detect drowsiness
- Sound alerts: Plays an alarm when drowsiness is detected
- Secure login: Uses face recognition and password hashing for authentication
- Session history: Records drowsiness incidents with timestamps
- Data storage: Saves session details in an SQLite database
- Easy-to-use interface: Built with Streamlit for a smooth experience

## Technologies Used
- Python
- Streamlit (for UI)
- OpenCV (cv2) (for computer vision)
- dlib (for facial landmark detection)
- NumPy and Pandas (for data processing)
- Pygame (for sound alerts)
- SQLite (for data storage)
- hashlib (for password security)
- imutils (for image processing)
- face_recognition (for login authentication)

## Getting Started
### Installation
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/driver-drowsiness-detection.git
   cd driver-drowsiness-detection
   ```
### Running the App
1. Start the application:
   ```bash
   streamlit run app.py
   ```
2. Log in or register to get started.
3. Allow camera access and start monitoring.
4. If drowsiness is detected, a loud alarm will play.
   
## How It Works
- The system captures frames from the webcam and detects facial landmarks.
- It analyzes the eye aspect ratio (EAR) to determine if the eyes are closing frequently.
- If the EAR drops below a threshold for a set duration, an alert is triggered.
- User data and session history are securely stored in an SQLite database.

## What’s Next?
Future improvements we are considering:
- Car integration: Sync with vehicle systems for automatic braking
- Mobile support: Bring the detection system to smartphones
- Cloud storage: Save session history online for better tracking
- AI predictions: Improve drowsiness detection using deep learning

## Contributors
- Your Name (your.email@example.com)
- Other Contributors

## Acknowledgments
A big shout-out to the open-source community for making computer vision and AI accessible to everyone.

