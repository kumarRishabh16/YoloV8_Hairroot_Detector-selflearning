**YoloV8_Hairroot_Detector**

**Overview**
This project utilizes a custom-trained YoloV8 model to detect hair roots in images accurately. It's designed to assist in the analysis and tracking of hair follicle roots, providing precise data for research or medical purposes.

**Features**
Custom YoloV8 Model: Trained on a specialized dataset for high accuracy in hair root detection.
Flask Web Application: An easy-to-use interface for uploading images and viewing detection results.
Interactive Results: Results are displayed directly on the web page, allowing for immediate analysis.

**Installation**
Clone the repository.
Install dependencies: pip install -r requirements.txt.
Run the Flask app: python app.py.

**Usage**
Access the web interface via localhost:5000 or the specified port.
Upload an image through the web interface.
View detected hair roots overlaid on the uploaded image.

**Files**
best.pt: The trained model file.
app.py: The Flask application.
index.html: The front-end HTML file.
requirements.txt: Required Python libraries.
