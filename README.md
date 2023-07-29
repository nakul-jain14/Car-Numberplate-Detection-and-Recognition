# Car-Numberplate-Detection-and-Recognition

![Project Image](path/to/project-image.png)


## Introduction
The Car Number Plate Detection and Recognition project aims to automatically detect and recognize car number plates in images using OpenCV and TesseractOCR. The system is specifically designed for Russian car plate numbers and utilizes a Haar Cascade XML file for plate detection and pytesseract library for character recognition.

## Features
- Automatic car number plate detection and recognition.
- Haar Cascade XML-based plate detection, specialized for Russian car plates.
- Efficient image processing techniques to improve character recognition accuracy.

## Installation
1. Clone the repository to your local machine.
2. Install the required dependencies using pip:
3. 
pip install pytesseract
pip install opencv-python

##Set the Tesseract OCR path to where the executable file is located in your system. Modify the following line in the code accordingly:

pytesseract.pytesseract.tesseract_cmd = r"C:\Users\NAKUL\OneDrive\Desktop\projects\number plate detection\tesseract-ocr-w64-setup-5.3.1.20230401.exe"

##Usage
-Place the car image you want to process in the repository directory or provide the appropriate file path when reading the image in the code.
-Run the Python script that contains the car number plate detection and recognition functions.
-The script will display the input car image along with the detected car number plate enclosed within a red rectangle.
-It will also print the text extracted from the car plate using TesseractOCR after applying image processing for improved accuracy.

##Technologies Used
OpenCV: A powerful computer vision library used for image processing and object detection.
pytesseract: A Python wrapper for TesseractOCR, enabling text extraction from images.

