# Face Detection using OpenCV

## Description

This Python script uses the OpenCV library to perform real-time face detection from a video stream captured by the default camera.

## Requirements

- Python 3.x
- OpenCV (install using `pip install opencv-python`)

## Usage

1. Clone the repository or download the script `face_detection.py`.

2. Install the required dependencies:

    ```bash
    pip install opencv-python
    ```

3. Run the script:

    ```bash
    python face_detection.py
    ```

4. Press the 'a' key to stop the video stream.

## Script Explanation

- The script loads the Haar Cascade classifier for face detection.
- It opens the default camera (webcam) using OpenCV's VideoCapture.
- The script continuously captures video frames, converts them to grayscale, and detects faces.
- Detected faces are highlighted with rectangles drawn on the frames.
- Press the 'a' key to stop the video stream.

## Customization

Feel free to customize the script based on your requirements. You can modify parameters like `scaleFactor`, `minNeighbors`, and `minSize` in the `detectMultiScale` function for different face detection results.

## License

This script is licensed under the [MIT License](LICENSE).

