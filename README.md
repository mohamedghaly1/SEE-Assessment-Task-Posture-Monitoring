# SEE-Assessment-Task-Posture-Monitoring

## Part 1: Technical Development Task — Load Distribution Analysis in Exercise Postures
This project analyzes images of a fitness coach performing different exercises (standing, squatting empty-handed, and squatting while holding weights) to estimate load distribution across key body parts: arms, legs, hips, and chest.

Key Steps:
Data Collection & Preprocessing: Images were collected from YouTube videos and resized to a standard 512x512 resolution for consistency.

Pose Estimation: Utilized the YOLOv8 pose model (from Ultralytics) to detect key body joint points from images.

Biomechanical Analysis: Calculated joint angles and estimated the load on arms, knees, ankles, hips, and chest using simplified biomechanical assumptions based on posture and weights held.

Visualization: Generated annotated images displaying load values on the body parts.

Reporting: Produced a summary comparing load distributions between different exercise postures and highlighted key observations on load changes due to posture and weights.

## Part 2: Presentation Overview
The presentation discusses the following aspects of the project:

Model Selection: Criteria for choosing 2D vs. 3D pose estimation models based on accuracy, computation, and real-time performance.

Data Collection & Annotation: How data was gathered and keypoints annotated to train and fine-tune the model.

Training Process: Use of pre-trained models (YOLOv8) and techniques to ensure model generalization across users and environments.

Model Usage: Deployment strategies for real-time and post-processing analysis with considerations for latency, accuracy, and user-friendly feedback for home and gym scenarios.

Challenges & Limitations: Discussion on factors such as occlusions, camera angles, and biomechanical simplifications impacting accuracy and robustness.
