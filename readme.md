# YoloV8 Hairroot Detector

## Overview

This project leverages a custom-trained YoloV8 model for high-precision hair root detection in images. It's crafted to aid in the analysis and tracking of hair follicle roots, offering accurate data for research or medical analysis purposes.

## Features

- **Custom YoloV8 Model**: Specifically trained on a dedicated dataset to ensure high accuracy in detecting hair roots.
- **Flask Web Application**: Provides a user-friendly interface for uploading images and viewing the results of hair root detection.
- **Interactive Results**: Detection results are displayed directly on the webpage, enabling immediate and detailed analysis.

## Installation

Follow these steps to set up the YoloV8 Hairroot Detector:

1. **Clone the Repository**

```bash
git clone <https://github.com/pj-13-shukla/YoloV8_Hairroot_Detector.git>

2. **Install Dependencies**
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt

3. **Run the Flask App**
```bash
python app.py

4. **Usage**
To use the application, follow these steps:
   1)'Access the Web Interface': Navigate to localhost:5000 or the port specified after running the Flask app.
   
   2)'Upload an Image': Use the web interface to upload an image for analysis.

   3)'View Results': The detected hair roots will be overlaid on the uploaded image, available for immediate viewing.

5. **Files**
   1)'best.pt': This is the trained model file, the core of our detection capabilities.
   
   2)'app.py': The main Flask application script that runs the web server.

   3)'index.html': The front-end HTML file for the web application, providing the user interface.

   4)'requirements.txt': A list of Python libraries required to run this project.


