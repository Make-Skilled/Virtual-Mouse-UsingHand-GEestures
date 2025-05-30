# Virtual Mouse Using Hand Gestures

A computer vision-based application that allows users to control their mouse cursor using hand gestures captured through a webcam. This project provides a hands-free way to interact with your computer, making it accessible and convenient for various use cases.

## Features

- Real-time hand gesture recognition
- Mouse cursor control using hand movements
- Click actions (left click, right click) through specific hand gestures
- Smooth cursor movement with gesture tracking
- Works with standard webcams

## Requirements

- Python 3.7 or higher
- OpenCV
- MediaPipe
- NumPy
- PyAutoGUI

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Virtual-Mouse-UsingHand-GEestures.git
cd Virtual-Mouse-UsingHand-GEestures
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the main application:
```bash
python main.py
```

2. Position yourself in front of your webcam
3. Use the following gestures to control the mouse:
   - Move your hand to control cursor movement
   - Pinch your index finger and thumb for left click
   - Pinch your middle finger and thumb for right click

## How It Works

The application uses computer vision techniques to:
1. Detect and track hand landmarks using MediaPipe
2. Calculate hand position and gesture states
3. Map hand movements to mouse cursor movements
4. Interpret specific gestures as mouse clicks

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- MediaPipe for hand tracking capabilities
- OpenCV for computer vision processing
- PyAutoGUI for system-level mouse control