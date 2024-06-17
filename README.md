# Head-Tracking-Application-with-Unity
## Overview

The Head Tracking Application is a project that allows real-time tracking of a user's head movements using a webcam and Unity. The application captures facial movements using Python and OpenCV, sends the data over UDP to Unity, and adjusts the camera position and rotation accordingly. This can be used for interactive experiences, virtual reality simulations, and more.

[![Head Tracking Demo](https://img.youtube.com/vi/AWgUh-0wNjE /0.jpg)](https://www.youtube.com/watch?v=AWgUh-0wNjE )

## Installation Instructions

### Python

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/blackprince2002/Head-Tracking-Application-with-Unity.git
   cd Head-Tracking-Application-with-Unity

2. **Install Dependencies:**
   ```bash
   pip install -r python/requirements.txt

### Unity

1. **Open Unity:**
   - Open Unity Hub.
   - Click on "Add" and select the unity directory of this repository.

1. **Attach Scripts:**
   - Attach UDPReceive.cs to a GameObject in your Unity scene.
   - Attach HeadTracking.cs to the main camera GameObject.

### Usage Instructions

1. **Run the Python Script:**
   - Navigate to the python directory.
   - Run face_tracking.py to start capturing and sending head tracking data.

1. **Run the Unity Project:**
   - Open the Unity project located in the unity directory.
   - Play the scene (MainScene.unity) to visualize the head tracking in action.
  
### Project Structure

   - python/: Contains Python scripts for capturing webcam data (face_tracking.py) and dependencies (requirements.txt).
   - unity/: Unity project directory with assets (Assets/), including scripts (Scripts/) and scenes (Scenes/).
   - LICENSE: MIT License for this project.

### Project Structure

   - OpenCV: Used for face detection and image processing in Python.
   - Unity: Used for real-time 3D rendering and game development.
   - Haarcascades: Pre-trained classifiers for face and feature detection in OpenCV.



     
