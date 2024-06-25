# Gesture-Based Volume Control

This project leverages Python and OpenCV to provide a touch-free way to control the volume of your system through hand gestures. By using real-time hand tracking, the system can detect specific gestures to adjust the volume, offering an intuitive and interactive user experience.

## Features

- **Real-time Hand Tracking :** Uses OpenCV and Mediapipe to accurately track hand movements.
- **Gesture Recognition :** Identifies specific gestures or finger positions to control volume.
- **User-Friendly :** Provides an intuitive, touch-free interface for controlling volume.

## Installation

1. **Clone the Repository :**
   ```bash
   git clone https://github.com/Mrigyank-Roy/Volume-Control-by-Hand-Tracking-System.git

2. **Install Libraries :**
   ```bash
   pip install opencv-python numpy comtypes pycaw mediapipe

3. **Run the Application :**
   ```bash
   python GestureControl.py

## Usage

1. Ensure your webcam is connected and working.
2. Run the application using the command provided in the installation section.
3. The system will start tracking your hand. Use specific gestures (like the distance between your thumb and index finger) to adjust the volume:
   - **Increase Volume:** Gesture to increase the distance between your thumb and index finger.
   - **Decrease Volume:** Gesture to decrease the distance between your thumb and index finger.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## Contact
If you have any questions or feedback, feel free to contact me at roymrigyank2004@gmail.com

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [Mediapipe](https://mediapipe.dev/)
- [PyCaw](https://github.com/AndreMiras/pycaw)
- [Comtypes](https://pypi.org/project/comtypes/)


