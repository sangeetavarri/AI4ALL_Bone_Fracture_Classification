# Bone Fracture Classification
*Developed a computer vision model to identify and classify bone fracture accurately using the YOLO object detection method and advanced data preprocessing techniques. Applied skills in python, machine language and collaborative tools such as kaggle and Github, all within AI4ALL’s innovative AI4ALL Ignite accelerator program.* 

## Problem Statement <!--- do not change this line -->

Our project aimed to answer the following question:

*How can computer vision algorithms be applied to detect and categorize bone fractures from X-ray scans, and what impact could this have on improving diagnostic efficiency?*

Our team was particularly interested in exploring the use of machine vision in healthcare, with a specific focus on bone fracture detection. Fractures are common injuries that affect people of all ages, and thus, we believe that making timely and accurate detection is essential.

To expand more on that, accurate and timely fracture detection is crucial to preventing complications and ensuring appropriate treatment. By developing a model capable of quickly analyzing X-ray images, we aim to streamline the diagnostic process, minimize human error, and assist healthcare professionals in making faster, more accurate decisions. This project is highly relevant as it has the potential to improve clinical workflows, enhance patient outcomes, and reduce healthcare costs through more precise and efficient diagnostics.

## Key Results <!--- do not change this line -->
During the course of our project, we faced challenges with the Google Colab platform due to frequent usage limits, which hindered our ability to further refine the model or explore additional hyperparameters. As a result, we encountered some technical difficulties that we believe contributed to the model's low performance.

Here are the current results:
- Total Precision Score: 0.374
   - By class:
      - Elbow Positive: 0.0575
      - Fingers Positive: 0.314
      - Forearm Fracture: 0.481
      - Humerus: 0.775
      - Shoulder Fracture: 0.31
      - Wrist Positive: 0.304
- Total Recall Score: 0.264
  - By class:
     - Elbow Positive: 0.0345
     - Fingers Positive: 0.188
     - Forearm Fracture: 0.454
     - Humerus: 0.583
     - Shoulder Fracture: 0.2
     - Wrist Positive: 0.126.
   
From these results, it’s clear that the Humerus class shows the best performance in terms of both precision and recall, while the Elbow Positive class is the most misclassified. In the future, we plan to focus on improving the Elbow Positive class, either by acquiring better data or adjusting class weights to improve its performance.

Although this model is not yet suitable for real-world deployment, we believe that with improved technical resources and further training, it has significant potential for more accurate fracture detection 

## Methodologies <!--- do not change this line -->

To achieve the results in this project, we began by selecting our dataset, which was sourced from Kaggle. The first step involved data cleaning, where we identified and removed images with incorrect or missing labels. Since the dataset was already pre-split into training, testing, and validation sets, we proceeded to the model-building phase. We then developed and trained multiple iterations of the YOLO (You Only Look Once) model using the prepared dataset. This phase took longer than expected due to the high computational power required for training an image-based dataset, which we had limited access to. We also encountered a few technical challenges, which we believe contributed to the model's lower performance. Despite these challenges, once the training was completed, we evaluated the model using precision and recall metrics, and were also able to generate a confusion matrix for evaulation. 

## Data Sources <!--- do not change this line -->

Kaggle Bone Fracture Detection Dataset: https://www.kaggle.com/datasets/pkdarabi/bone-fracture-detection-computer-vision-project 


YOLO Documentation: https://docs.ultralytics.com/

## Technologies Used <!--- do not change this line -->
- Kaggle
- Google Colab
- Python
   - Primary Libraries Used:
       - cv2
       - Matplotlib
       - Yolov8 (Ultralytics)

## Authors <!--- do not change this line -->
- John Akinmolayan (Github: jakinmol8637)
- Britney Carrasco (Github: Britneycara13)
- Ramani Garia (Github: RamaniGaria)
- Sangeeta Varri (Github: sangeetavarri)
