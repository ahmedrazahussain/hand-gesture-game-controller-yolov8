# Hand-Gesture-Game-Controller-YOLOv8
This project turns your webcam into a gesture-based game controller using a custom-trained YOLOv8 model. The model recognizes 5 specific hand gestures and maps them to common game controls:
- 'Up'
- 'Down'
- 'Right'
- 'Left'
- 'Space'
## Features
- Real-time hand gesture detection using YOLOv8
- Control games or apps with gestures (Keyboard simulation)
- Trained on a custom dataset using Roboflow
- Easily extendable to more controls or gestures
## How It Works
1. **Data Collection**: Hand gestures representing 5 game commands are captured and annotated using Roboflow.
2. **Model Training**: Yolov8 model is trained on the dataset to detect 'up', 'down', 'right', 'left', and 'space'.
3. **Gesture Detection**: Webcam input is processed in real-time to detect gestures.
4. **Keyboard Mapping**: Detected gestures are mapped to actual key presses using 'pyautogui'.
## Applications
- Play games without a physical controller
- Hands-free interface for accessibility
- Fun computer vision demo project
