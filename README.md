# Object Detection and OCR with YOLO and EasyOCR

## Description
This project demonstrates the use of a custom-trained YOLO model to detect objects in an image and EasyOCR to recognize text within the detected objects. The workflow involves loading a YOLO model, detecting objects in an image, cropping the detected regions, and performing OCR to extract any text.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- Matplotlib
- Ultralytics YOLO
- EasyOCR

## Installation
To run this project, you need to install the required Python packages. You can do this using pip:

## How to Run
Load the Model: The script loads a pre-trained YOLO model from a specified path.
Detect Objects: It processes an input image (car5.png) to detect objects.
Visualize Results: The detected objects are displayed with bounding boxes.
Crop and OCR: Crops the detected regions and applies EasyOCR to recognize text within the cropped images.

## Usage Notes
Replace runs\detect\train\weights\best.pt with the path to your custom YOLO model weights.
Replace C:\Users\robel\Downloads\car5.png with the path to your input image

## Acknowledgements
This project utilizes the YOLO object detection model and EasyOCR for optical character recognition.
