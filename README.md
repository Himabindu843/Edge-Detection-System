

# Edge Detection System using Python

##  Project Description

The **Edge Detection System** is an image processing application developed using Python that detects object boundaries in images by identifying sharp changes in pixel intensity. This project implements and compares four widely used edge detection algorithms: **Sobel, Prewitt, Laplacian, and Canny**.

Edge detection is a fundamental step in computer vision and plays a crucial role in feature extraction, object detection, medical imaging, and pattern recognition.

## Objectives

* To understand the concept of edge detection in digital images
* To implement multiple edge detection algorithms
* To compare the performance of different edge detectors
* To gain hands-on experience with OpenCV and NumPy

## Technologies Used

* **Programming Language:** Python
* **Libraries:**

  * OpenCV
  * NumPy
  * Matplotlib


##  Algorithms Implemented

### Sobel Edge Detection

* Uses first-order derivatives
* Detects horizontal and vertical edges
* Produces strong and clear edges

###  Prewitt Edge Detection

* Similar to Sobel but simpler
* Less sensitive to noise
* Faster computation

### Laplacian Edge Detection

* Uses second-order derivatives
* Detects edges in all directions
* Sensitive to noise, so smoothing is required

### Canny Edge Detection

* Multi-stage algorithm
* Includes noise reduction and edge tracking
* Produces thin and accurate edges


## Project Workflow

Input Image
   ↓
Grayscale Conversion
   ↓
Gaussian Blur (Noise Reduction)
   ↓
Apply Edge Detection Algorithms
   ↓
Result Visualization & Comparison


## Project Structure

Edge-Detection-System/
│
├── edge_detection.py
├── README.md
├── requirements.txt
└── sample_images/


## How to Run the Project

### Step 1: Install Dependencies

pip install opencv-python numpy matplotlib

### Step 2: Run the Script

python edge_detection.py

##  Output

The system displays:

* Original image
* Sobel edge output
* Prewitt edge output
* Laplacian edge output
* Canny edge output


## Learning Outcomes

* Understanding of image gradients and edges
* Practical experience with OpenCV
* Knowledge of feature extraction techniques
* Ability to compare computer vision algorithms


## Future Enhancements

* Add GUI using **Tkinter or Streamlit**
* Apply edge detection on **medical images**
* Integrate with **object detection systems**
* Real-time edge detection using webcam

!https://github.com/Himabindu843/Edge-Detection-System/blob/main/edge_detection_output.jpg

