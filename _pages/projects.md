---
title: "Projects"
excerpt: "Projects"
author_profile: true
permalink: /projects/
redirect_from:
  - /tags/
---

{% include base_path %}

Intrusion Detection in Low-Light scenarios
------
- A video surveillance based solution for low light scenarios. 
- The motivation behind this solution was to enhance the security of the borders using AI given the rise in terrorism.

<p align="center">
<img src = "/images/final_output.gif" width="93%">
</p>

- Low-light images were processed using stacking and averaging techniques. 
- Detection of intruders and their firearms were done using *YOLOv4* based model.
- *HRNet* was utilized for intruder pose estimation
- *Viola-Jones* algorithm was used for intruder face recognition.

The implementation can be found [here](https://github.com/AmanGoyal99/Low-light-intrusion-detection).

Vehicle Parking Occupancy Detection
------
- A parking occupancy status detection solution which utilizes classical computer vision concepts such as _Canny Edge Detection_ and deep learning based object detection model _YoloV3_', 

<p align="center">
<img src="/images/parking-occupancy-detection_resized.jpg" width="93%">
</p>

The following procedure was followed to derive the solution:

- Suitable images were found using Open IP CCTV camera websites. 
- Parking zones were detected using _Canny Edge Detection_ and _Hough Line Transform_.
- Detection of vehicles took place using _YoloV3_ model.
- Vehicles were represented as point objects on the 2D map using _homography estimation_.
- Finally the status of the parking zone was detected using _Point Polygon Test_.

The detailed procedure can be found in this [blog](https://nayan.co/blog/AI/Vehicle-Parking-Occupancy-Detection/).

Deep Learning based COVID-19 classifier
------

- COVID-19 is one of the most destructive pandemic humankind has ever faced. 
- It has not only shaken the economy across the world but also made it an extremely difficult task for effective medical help to reach across remote regions. 
- An extremely accurate and lightweight AI model could be a solution for this as it could aid the doctors and medical team especially in remote areas to detect COVID-19.

Hence keeping this in mind, this project aims to create a deep learning based COVID-19 CT-Scan images classifier.

<p align="center">
<img src="/images/covid-19-classifier.png" width="93%" height = "63%">
</p>

- In the project, experiments have been done both with as well as without transfer learning.
- With just 50 training images, _MobileNet_ based model was able to provide an accuracy of 99%.

The implementation can be found [here](https://github.com/AmanGoyal99/COVID-19-Classifier).

Image Denoising with Autoencoders
------
This project aims to perform denoising of images from [Olivetti Faces Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html) by using _Convolutional Autoencoders_.

<p align="center">
<img src="/images/Autoencoders.png" width="93%">
</p>

- The images were provided random noise using basic python code.
- The best results were obtained when the architecture was trained using 1000 epochs.
- The above image is an example of evaluation done on testing set.

The implementation can be found [here](https://github.com/AmanGoyal99/Denoising-Images-with-Autoencoders).

QuickDraw - Image Recognition
------
This project was inspired by Google's [QuickDraw](https://quickdraw.withgoogle.com/) and aims to recognize images across 15 categories

<p align="center">
<img src="/images/quickdraw_resized.jpeg" width="93%">
</p>

- It is a _CNN_ based image classifier which classifies images across 15 categories.

The implementation can be found [here](https://github.com/AmanGoyal99/QuickDraw).


