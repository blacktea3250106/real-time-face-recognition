# Real-Time Face Recognition using FaceNet and OpenCV

<img src="screenshots/face_recognition.gif" width="640" height="360">

## Overview

This Python script enables real-time face recognition using the FaceNet model and OpenCV. It allows you to detect and recognize faces in a live video stream from a webcam. The script utilizes a pre-trained FaceNet model for facial feature extraction and a face detection model from OpenCV's deep neural networks (DNN) for face localization.

## Key Features

- Real-time face detection using the Single Shot MultiBox Detector (SSD) model.
- Face recognition using the FaceNet model.
- Live video processing from your webcam.
- Displaying the recognized person's name and confidence score.
- Frames per second (FPS) calculation for video processing speed.

## Prerequisites

Before running the script, make sure you have the following prerequisites installed:

- Python 3.x
- OpenCV (cv2)
- TensorFlow/Keras
- NumPy
- Caffe (required for the face detection model)

You can easily install these dependencies using `pip`. For example:

```bash
pip install opencv-python tensorflow numpy
```
### Getting Started
1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/real-time-face-recognition.git
```

2. Navigate to the project directory:

```bash
cd real-time-face-recognition
```

3. Download the required model files:
- FaceNet model: You can obtain the FaceNet model and weights from various online sources. Ensure that you place the model file in the project directory and update the script to load it.
- Face detection model: The script uses a pre-trained Caffe model for face detection, which can be downloaded from the official Caffe model zoo.

4. Run the script:
```bash
python face_recognition.py
```

5. The script will open your webcam feed and initiate real-time face recognition. Recognized faces will be labeled with their names and confidence scores.

6. To exit the program, press the 'q' key.

## Customization

You can customize the script to meet your specific requirements by adjusting the following parameters:

- Face detection confidence threshold: Modify the confidence threshold to control the sensitivity of face detection. You can adjust this in the script where the threshold is defined.

- Face recognition threshold: Adjust the threshold for face recognition to control the confidence level for recognizing faces. You can modify this in the script where the threshold is defined.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The FaceNet model was developed by researchers at Google. For more information about FaceNet, refer to their research paper.

- The face detection model used in this script is based on the Single Shot MultiBox Detector (SSD) architecture, provided as part of the OpenCV library.

## Authors

- [blacktea3250106](https://github.com/blacktea3250106)

Feel free to enhance this README with additional information or acknowledgments as needed.


