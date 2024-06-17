# Head-Tracking-Application-with-Unity
## Overview

The Head Tracking Application is a project that allows real-time tracking of a user's head movements using a webcam and Unity. The application captures facial movements using Python and OpenCV, sends the data over UDP to Unity, and adjusts the camera position and rotation accordingly. This can be used for interactive experiences, virtual reality simulations, and more.

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
     
