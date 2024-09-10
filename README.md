
# Real-Time Full-Body Landmark Detection with MediaPipe and Raspberry Pi

## Overview

This project implements a **full-body landmark detection** system using **MediaPipe**, **OpenCV**, and **Raspberry Pi**. The goal is to enable real-time tracking of 33 key body points to facilitate applications such as **fitness tracking**, **rehabilitation assistance**, and interactive **human-computer interfaces**.

## Key Features

- Real-Time Pose Estimation: Utilizes MediaPipe's advanced pose detection capabilities to accurately track and visualize body landmarks.
- Edge Computing: Runs on a Raspberry Pi for a portable and cost-effective solution, making it ideal for deployment in various environments.
- OpenCV Integration: Processes video frames from the camera to detect and draw body landmarks in real-time.
- Scalable Applications: Suitable for fitness centers, rehabilitation clinics, and home use, providing real-time feedback and analysis.

## Components

- Raspberry Pi: The core hardware device for running the AI model and processing video frames.
- Camera Module: Captures live video for pose detection.
- MediaPipe: Handles the detection and tracking of body landmarks.
- OpenCV: Processes video frames and overlays detected landmarks.

## Getting Started

### Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- MediaPipe (`mediapipe`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/adnano1/your-repository.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-repository
   ```

3. Install the required packages:
   ```bash
   pip install opencv-python mediapipe
   ```

### Usage

Run the main script to start the full-body landmark detection:
```bash
python main.py
```

### Future Work

- Develop a smart wearable device using the Raspberry Pi to provide real-time feedback for fitness and rehabilitation.
- Integrate additional sensors for a more comprehensive analysis of body movements and physical metrics.

