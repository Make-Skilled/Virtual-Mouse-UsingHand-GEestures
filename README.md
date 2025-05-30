# Virtual Mouse Using Hand Gestures

A computer vision-based application that allows users to control their mouse cursor using hand gestures captured through a webcam. This project provides a hands-free way to interact with your computer, making it accessible and convenient for various use cases.

## Table of Contents
- [Features](#features)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [Gesture Controls](#gesture-controls)
- [Troubleshooting](#troubleshooting)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- Real-time hand gesture recognition with high accuracy
- Smooth mouse cursor control using hand movements
- Multiple click actions:
  - Left click
  - Right click
  - Double click (coming soon)
- Adjustable sensitivity settings
- Works with standard webcams
- Low latency response
- Cross-platform compatibility (Windows, macOS, Linux)

## System Requirements

### Hardware Requirements
- Webcam (minimum 720p resolution recommended)
- Processor: Intel Core i3 or equivalent
- RAM: 4GB minimum
- Storage: 100MB free space

### Software Requirements
- Python 3.7 or higher
- Operating System: Windows 10/11, macOS 10.14+, or Linux
- Webcam drivers installed
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Virtual-Mouse-UsingHand-GEestures.git
cd Virtual-Mouse-UsingHand-GEestures
```

2. Create and activate a virtual environment (recommended):
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage Guide

1. Run the main application:
```bash
python main.py
```

2. Initial Setup:
   - Ensure your webcam is properly connected and accessible
   - Position yourself 2-3 feet away from the webcam
   - Ensure good lighting conditions
   - Keep your hand within the camera frame

3. Calibration:
   - The system will automatically calibrate when started
   - Keep your hand steady during the initial calibration
   - Follow the on-screen instructions if any appear

## Gesture Controls

### Basic Movements
- Move your hand horizontally to move the cursor left/right
- Move your hand vertically to move the cursor up/down
- Move your hand closer/further to adjust cursor speed

### Click Actions
- Left Click: Pinch your index finger and thumb together
- Right Click: Pinch your middle finger and thumb together
- Double Click: Coming soon

### Tips for Better Control
- Keep your hand steady for precise movements
- Maintain good lighting conditions
- Avoid rapid movements for better accuracy
- Keep your hand within the camera frame

## Troubleshooting

### Common Issues and Solutions

1. Webcam Not Detected
   - Check if your webcam is properly connected
   - Ensure no other application is using the webcam
   - Update webcam drivers

2. Poor Tracking
   - Improve lighting conditions
   - Ensure your hand is clearly visible
   - Check if you're within the recommended distance
   - Clean your webcam lens

3. High Latency
   - Close unnecessary applications
   - Check system resource usage
   - Reduce webcam resolution if needed

4. Installation Issues
   - Ensure Python 3.7+ is installed
   - Update pip: `python -m pip install --upgrade pip`
   - Try installing dependencies individually if batch install fails

## Technical Details

The application uses several key technologies:

1. Hand Tracking
   - MediaPipe for accurate hand landmark detection
   - 21-point hand landmark model
   - Real-time processing pipeline

2. Cursor Control
   - PyAutoGUI for system-level mouse control
   - Smooth movement interpolation
   - Configurable sensitivity settings

3. Computer Vision
   - OpenCV for image processing
   - Frame capture and preprocessing
   - Real-time gesture recognition

## Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

Please ensure your code follows our style guidelines and includes appropriate tests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- MediaPipe for hand tracking capabilities
- OpenCV for computer vision processing
- PyAutoGUI for system-level mouse control
- All contributors and users of this project