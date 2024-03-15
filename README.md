# Video Player Hand Gesture Controller

This project aims to create a video player controller using hand gestures. By leveraging computer vision techniques and hand tracking, users will be able to control the playback of videos using simple hand gestures detected by a webcam.

## Features

- Control video playback using hand gestures such as play, pause, rewind, fast forward, and volume control.
- Support for various video formats and platforms.
- Simple and intuitive user interface.
- Minimal hardware requirements - only a webcam is needed.

## Technologies Used

- **Python**: Programming language used for implementing the controller logic.
- **OpenCV**: Library used for real-time computer vision and hand tracking.
- **MediaPipe**: Framework used for hand landmark detection and tracking.
- **PyAutoGUI**: Library used for simulating keyboard and mouse inputs for controlling the video player.
- **FFmpeg**: Optional - for video processing and playback.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/video-player-gesture-controller.git
   ```
2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the video player gesture controller script:

   ```bash
   python app.py
   ```

## Usage
Ensure that your webcam is connected and properly positioned to capture your hand gestures.
Run the app.py script to start the video player controller.
Follow the on-screen instructions to perform hand gestures for controlling video playback:
Show one finger to fast forward the video.
Show two fingers to rewind the video.
Show three fingers to increase the volume.
Show four fingers to decrease the volume.
Show five fingers to pause or play the video.
Enjoy controlling your video player with hand gestures!
Contributing
Contributions are welcome! If you have any ideas, bug fixes, or enhancements, feel free to open an issue or submit a pull request.

