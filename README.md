# Face Detection in Images and Videos Using OpenCV
This project demonstrates face detection in both images and videos using the Haar Cascade classifier available in OpenCV. The implementation is capable of detecting and marking human faces in various frames, providing a foundation for more advanced computer vision applications.

# Overview
  ~ Objective: To accurately detect human faces in images and videos using computer vision techniques and highlight them with bounding boxes.
  ~ Tools Used: OpenCV for image processing and face detection, Google Colab for running the code, and IPython display functions for video playback.

# Features
  ~ Face Detection in Images:
Users can upload images, and the system will detect faces using the Haar Cascade classifier. Detected faces are marked with bounding boxes.

  ~ Face Detection in Videos:
The project supports video face detection by processing each frame individually. A unique pastel color (pastel purple) is used for bounding boxes to enhance visibility.

  ~ Non-Maximum Suppression:
Implemented to reduce overlapping rectangles around detected faces, ensuring clarity and precision in detection.

  ~ Output and Display:
The processed video with detected faces is saved and can be displayed directly within the Jupyter Notebook environment using HTML video tags.
