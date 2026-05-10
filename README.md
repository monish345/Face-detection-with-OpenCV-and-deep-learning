# OpenCV Deep Learning Face Detection

A deep learning-based face detection project built using OpenCV's DNN module and Python. This project detects faces in both images and videos using a pre-trained Caffe deep learning model.

---

## Features

- Face detection in images
- Face detection in videos
- Deep learning-based detection using OpenCV DNN
- Confidence score display
- Bounding box visualization
- Output image and video saving
- Google Colab compatible

---

## Technologies Used

- Python
- OpenCV
- Deep Learning
- NumPy
- Google Colab

---

## Deep Learning Model Used

This project uses OpenCV’s pre-trained SSD face detector based on the ResNet-10 architecture.

Model files used:

- `deploy.prototxt`
- `res10_300x300_ssd_iter_140000.caffemodel`

---

## Project Structure

```text
OpenCV-DeepLearning-FaceDetection/
│
├── face_detection.ipynb
├── deploy.prototxt
├── res10_300x300_ssd_iter_140000.caffemodel
├── sample_images/
├── sample_videos/
├── outputs/
└── README.md
```

---

## How It Works

The system follows this pipeline:

```text
Input Image/Video
        ↓
Blob Creation
        ↓
Deep Learning Face Detector
        ↓
Face Detection
        ↓
Bounding Box Drawing
        ↓
Output Generation
```

---

## Installation

Install required libraries:

```bash
pip install opencv-python numpy
```

---

## Running the Project

### For Image Detection

1. Upload an image
2. Run the notebook cells
3. Faces will be detected and displayed

### For Video Detection

1. Upload a video file
2. Run the video processing cells
3. Processed output video will be generated and downloaded

---

## Confidence Threshold

The project uses a confidence threshold of:

```python
0.5
```

Detections below this threshold are ignored.

---

## Sample Output

### Image Detection

- Detects multiple faces
- Displays confidence percentages
- Draws bounding boxes around detected faces

### Video Detection

- Processes frame-by-frame
- Detects faces in real-time
- Saves processed output video

---

## Learning Outcomes

This project helped improve understanding of:

- Computer Vision
- OpenCV DNN module
- Deep Learning inference
- Blob preprocessing
- Image processing
- Video frame processing
- Face detection pipelines

---

## Future Improvements

- Real-time webcam face detection
- Face recognition
- Emotion detection
- Mask detection
- Attendance system
- Flask web application
- React frontend dashboard

---

## Author

Monish T

---

## References

- OpenCV Documentation
- PyImageSearch Face Detection Tutorial
- OpenCV DNN Face Detector Model
