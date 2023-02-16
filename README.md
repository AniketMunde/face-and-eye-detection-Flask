Here’s a formatted and copy-ready README file:

---

# Real-Time Face Detection Flask App

This project is a real-time face detection application built with Flask and OpenCV. The app captures video from a camera, detects faces using the Haar Cascade Classifier, and streams the video with detected faces to a web page.

## Table of Contents

- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Usage](#usage)
- [File Structure](#file-structure)
- [License](#license)

## Project Overview

The application captures live video from a camera and detects faces in each frame using OpenCV’s Haar Cascade Classifier. Detected faces are highlighted with rectangles and streamed to a web interface.

## Requirements

The following libraries are required:

- `Flask`
- `OpenCV`

Install the dependencies with:

```bash
pip install flask opencv-python
```

## Usage

To run the application:

1. Ensure your camera is connected or enabled.
2. Run the Flask app with:

    ```bash
    python main.py
    ```

3. Open a web browser and navigate to `http://127.0.0.1:5000` to view the live stream.

## File Structure

- `main.py`: The main script to start the Flask server and handle video streaming and face detection.
- `haarcascade_frontalface_default.xml`: A required XML file for the Haar Cascade Classifier.
- `templates/index.html`: HTML template to render the video feed.

## License

This project is for educational purposes and is open for personal or academic use.

---

Copy this into a README file to provide clear instructions and details for your project!