

This project aims to develop an AI-powered system for detecting and tracking players, referees, and footballs in match footage using YOLO, a state-of-the-art deep learning-based object detection model. To enhance detection accuracy, I fine-tuned the model on a custom dataset tailored to football analytics.

In addition to object detection, I implemented K-means clustering for pixel segmentation, enabling automated team classification based on jersey colors. This will facilitate the computation of team-specific ball possession metrics by analyzing object interactions over time.

To track player movement, I incorporated optical flow, allowing for frame-to-frame motion estimation while compensating for camera movement. Additionally, perspective transformation will be applied to correct for depth distortion, converting pixel-based measurements into real-world metrics such as distance covered in meters.

Building on these components, we will compute advanced performance analytics, including player speed, total distance covered, and ball acquisition percentages, providing actionable insights for match analysis.

This project integrates key concepts from computer vision, deep learning, and sports analytics.


<img width="1260" alt="Screenshot 2025-02-06 at 1 29 53 PM" src="https://github.com/user-attachments/assets/bc418d49-94cc-412b-8f59-b61399bf4a02" />



4# Models Used:

The following modules are used in this project:

YOLO: AI object detection model
Kmeans: Pixel segmentation and clustering to detect t-shirt color
Optical Flow: Measure camera movement
Perspective Transformation: Represent scene depth and perspective
Speed and distance calculation per player

TO access to entire code of the project kindly access the below google drive link. In case the google drive link expires do contact me on my personal email address for access: m.rafay.ch@gmail.com

Code Link: https://drive.google.com/drive/folders/1gOQMH1D1eHIo98Lkhg6rovicfrzEZPJG?usp=share_link





