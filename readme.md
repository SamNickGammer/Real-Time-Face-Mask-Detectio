# Real-Time Mask Detection

This project utilizes deep learning techniques to detect whether individuals in a video stream are wearing masks or not in real-time.

## Installation

To run this project, you'll need to install the required dependencies listed in the `requirements.txt` file. You can install them using pip:

```bash
pip install -r requirements.txt
```



## Usage

1. Make sure you have a webcam connected to your system.
2. Run the `mask_detection.py` script.
3. The script will start capturing frames from the webcam and display the video stream.
4. It will detect faces in the frames and classify them as wearing a mask or not.
5. The output will be displayed in the video stream with bounding boxes and labels indicating whether a mask is detected or not.
6. Press 'q' to quit the application.

## Files

- `mask_detection.py`: Python script containing the real-time mask detection logic.
- `face_detector`: Directory containing the pre-trained face detection model.
  - `deploy.prototxt`: Prototxt file defining the architecture of the face detection model.
  - `res10_300x300_ssd_iter_140000.caffemodel`: Pre-trained weights for the face detection model.
- `mask_detector.model`: Pre-trained mask detection model.
- `requirements.txt`: List of required Python packages and their versions.

## Dependencies

- TensorFlow (>=1.15.2)
- Keras (2.3.1)
- Imutils (0.5.3)
- NumPy (1.18.2)
- OpenCV-Python (4.2.0.*)
- Matplotlib (3.2.1)
- SciPy (1.4.1)


