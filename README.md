FitTrack-AI Privacy Preserving Multi Camera Key Point Fusion for Human Posture Analysis
A simple system which analyzes human posture using keypoints from front and side cameras while ensuring complete user privacy.

Project Description

This project takes only numerical keypoints (x, y coordinates and confidence scores) from two cameras, combines them, and gives basic posture feedback. No image or video is stored at any stage.

Repository Structure
FitTrack-AI/
├── main.py                 # Main file to run the system
├── Pose_Detection.py       # Filters keypoints
├── fusion_logic.py         # Multi-camera keypoint fusion
├── feedback_logic.py       # Posture feedback logic
├── camera_input.py         # Dummy camera input (simulation)
├── utils.py                # Helper functions
├── constants.py            # Constants used in project
├── app.py                  # Streamlit web interface for demo
└── README.md
