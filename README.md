# Football Analysis Project

## Introduction
The goal of this project was to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available.
We trained and fine-tuned the model to improve its performance for football-specific scenarios.
Additionally, we assigned players to teams based on the colors of their t-shirts using KMeans for pixel segmentation and clustering.
Using this information, we measured each team's ball acquisition percentage throughout the match.
We also applied optical flow to estimate camera movement between frames, allowing us to accurately track player motion.
Furthermore, we implemented perspective transformation to represent the scene's depth and perspective, enabling us to measure player movement in meters rather than pixels.
Finally, we calculated each player's speed and the total distance covered during the game.
This project covered various advanced computer vision concepts and addressed real-world problems, making it a valuable experience for both beginners and experienced machine learning engineers.

![screenshot](https://github.com/user-attachments/assets/8dcc695d-6007-43c5-9d3d-1eb45863732d)

## Modules Used

The following modules are used in this project:

- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
[Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view)

## Sample video
[Sample input video]([https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view))

## Tools and Libraries Used

- YOLOv8
- Ultralytics
- OpenCV
- NumPy
- Scikit-learn
- PyTorch


