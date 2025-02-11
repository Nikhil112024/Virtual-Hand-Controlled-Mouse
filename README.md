# Hand-Controlled Mouse

## Overview
This project enables users to control their mouse pointer using hand gestures. It utilizes **OpenCV**, **PyAutoGUI**, and **MediaPipe** to track hand movements and translate them into cursor movements and click actions.

## Features
- **Move Cursor:** Control mouse pointer using hand movement.
- **Click Actions:** Perform left and right clicks with gestures.
- **Scroll Functionality:** Scroll up and down using hand gestures.
- **Real-Time Processing:** Uses **MediaPipe Hand Tracking** for fast and efficient tracking.

## Requirements
Make sure you have **Python 3.10** installed. Then, install the required libraries:

```bash
pip install opencv-python pyautogui mediapipe
```

## Libraries Used
- **OpenCV** - For capturing and processing video input.
- **PyAutoGUI** - For simulating mouse actions.
- **MediaPipe** - For real-time hand tracking.

## Usage
Run the script to start the hand-controlled mouse system:

```bash
python hand_mouse_control.py
```

## How It Works
1. **Hand Detection**: Uses **MediaPipe** to detect hands and track landmarks.
2. **Gesture Recognition**: Identifies specific finger positions to determine actions (move, click, scroll).
3. **Mouse Control**: Uses **PyAutoGUI** to move the cursor and perform clicks based on gestures.

## Example Gestures
| Gesture | Action |
|---------|--------|
| Index finger up | Move cursor |
| Index + Middle finger up | Perform a click |
| Thumb + Pinky up | Scroll up/down |

## Contributing
Feel free to fork this repository and contribute improvements. Pull requests are welcome!

## License
This project is licensed under the MIT License.

---

### Author
[Nikhil Kumar](https://github.com/Nikhil112024)

