# Women_Saftey_Analytics
This project is a real-time women surveillance system that analyzes CCTV footage or live video feeds to ensure the safety of women. The system features several functionalities, including an alert system that notifies authorities when a woman is alone at night or surrounded by suspicious individuals. Alerts are triggered based on the woman’s facial emotions.
# Features
- YOLO for Object Detection: Detects persons and other objects in real-time footage.
- Face Cropping and Gender Classification: Crops the detected face and determines gender for further assessments using transformer pipelines.
- Alert System: Sends alerts via Telebot when a woman is alone or in a potentially unsafe situation, with future plans to notify the nearest police station or authorities.
- Distance Calculation: Measures the distance between the woman and surrounding men, triggering alerts if distress or fear is detected in the woman’s emotions.
- Pose and Emotion Detection: Utilizes MediaPipe Holistic for detecting poses and emotions, integrated with a centroid tracker for monitoring speed and movement.

# Installation
To run this project, follow these steps:
1. Clone the repository:
  git clone https://github.com/adityayogeshwar/Women-saftey-Analytics.git
# Future Enhancements
- To Develop a fully functional software application based on this project.
- Adding the functionalities like violence detection, fire detection, fall detection, and more.
- Implementing techniques like super-resolution for enhancing blurry CCTV images to minimize errors.
