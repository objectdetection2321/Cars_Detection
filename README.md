Car Detection with YOLO v4
Overview
This project uses the pre-trained YOLO v4 model available on Roboflow to develop an object detection model that can accurately detect and recognize cars in images. The model is trained on a dataset of images of cars while hiding their license plates and potentially blurring any identifying information of individuals. The trained model can be used to assist in traffic analysis and surveillance in urban and suburban areas.

Dataset
The dataset for this project is collected from various public sources and augmented using tools such as Roboflow. It consists of images of cars in various environments and lighting conditions, with their license plates hidden or blurred. The dataset is divided into training, validation, and test sets.

Dependencies
Python 3.7
TensorFlow 2.4
OpenCV 4.5.1
NumPy 1.19.5
