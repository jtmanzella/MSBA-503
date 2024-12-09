# MSBA-503
Project Overview
This project focuses on comparing object detection models and analyzing their performance across a series of test images. The models implemented include:

YOLO (You Only Look Once) Model: Designed for real-time object detection with a focus on speed and simplicity.
RCNN (Region-Based Convolutional Neural Network) Model: A more complex model providing higher accuracy and object detection count.
Dominant Color Detection Model: A supplementary model used to identify the most prominent colors in images.

Dataset and Columns
Dataset
The dataset includes the following images:

Pigs.jpg
Race_Horse.jpeg
Randy_Moss.jpeg
Team_USA.jpeg
Bayern.jpeg
Byron_Buxton.jpeg
Columns and Description
For both YOLO and RCNN models, the following columns are used to structure the data:

Image: The name of the image file being analyzed.
Total Objects Detected: The count of objects identified by the model in the image.
Detection Time (s): The time (in seconds) taken by the model to analyze the image and detect objects.
Average Confidence (%): The average confidence score of the model's predictions for all detected objects in the image.
Detected Objects: A list of objects identified in the image, along with their confidence scores.
For the Dominant Color Detection Model:

Top Colors: The most prominent colors detected in the image.
Models Overview
YOLO Model
Purpose: Real-time object detection.
Strengths: High speed, capable of detecting multiple objects in a single pass.
Outputs: Total objects detected, detection time, average confidence, and a list of detected objects with confidence scores.
RCNN Model
Purpose: Detailed object detection with enhanced accuracy.
Strengths: Higher confidence and detection count compared to YOLO.
Outputs: Same as YOLO with more precise object identification.
Dominant Color Detection Model
Purpose: Identification of dominant colors in images.
Outputs: List of dominant colors for each image.

## Additional Resources
- [Image Analytics Table Document](https://github.com/jtmanzella/MSBA-503/blob/main/Image%20Analytics%20Table%20Document.docx)
