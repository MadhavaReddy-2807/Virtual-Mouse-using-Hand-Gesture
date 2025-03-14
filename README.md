# Virtual Mouse

## Introduction
The **Virtual Mouse** is a computer interaction system that allows users to control the cursor and perform various actions using hand gestures detected by a camera. It eliminates the need for a physical mouse, enabling touchless control using only finger movements.

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- Numpy
- PyAutoGUI

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/virtual-mouse.git
   cd virtual-mouse
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python mediapipe numpy pyautogui
   ```
3. Run the application:
   ```bash
   python virtual_mouse.py
   ```

## Usage Instructions
The Virtual Mouse recognizes the following hand gestures:

| Gesture                        | Action         |
|--------------------------------|---------------|
| Index finger open, thumb closed | Moves cursor  |
| Open thumb, open middle, close index | Left click  |
| Open thumb, close middle, open index | Right click |
| Open thumb, close middle & index | Double click   |
| All fingers closed              | ScreenShot   |
### Additional Notes
- Ensure your webcam is properly configured and positioned for accurate hand tracking.
- Adjust sensitivity settings within the script if needed.
- The program may require permission to control the mouse and take screenshots.

## Troubleshooting
- If the cursor is not moving, check if the camera is detecting the hand properly.
- If clicks are not registering, try adjusting the hand distance from the camera.
- If the program lags, lower the camera resolution or optimize the detection settings.


