---
layout: default
---

<img class="profile-picture" src="img/icon_bright.jpg" width="200px" />

Hello World! <br>

<p align="justify" style="margin:0 30px 0 0;">
  I am a Software Engineer at HSBC Technology India. I did my undergraduate in Computer Engineering from Nirma University, Ahmedabad, India. I have been working in the field of Artificial Intelligence and Machine Learning, having experience in projects involving Computer Vision, Medical Imaging, Satellite Imagery, Signal Processing, Nuclear Physics, and Parallel Computing.
</p>

*I am very passionate about Body Building and Fitness.*

## Research Interest
Applications of Deep Learning and Computer Vision in the domain of Medical Imaging, Nuclear Physics, and Autonomous Driving.

## News
- Oct 2020: Our paper, *"Dilated Volumetric Network: An Enhanced Fully Convolutional Network for Volumetric Prostate Segmentation from Magnetic Resonance Imaging"* was accepted in *Pattern Recognition and Image Analysis* journal.
- Sep 2020: Bagged the *HTI Hero Award* for our exceptional work at HSBC during COVID-19 pandemic.
- Aug 2020: Got certified as AWS Machine Learning specialist, Developer, and Solutions Architect.
- Apr 2020: Gave a talk on *Super-resolution using Deep Learning* at Nirma University, Ahmedabad.
- Oct 2020: Graduated from Nirma University with a bachelor's degree in Computer Engineering.
- Sep 2019: Received the *Most Innovative Idea* award for our work on authenticating users from electrocardiogram signals and deep learning methods.

<details><summary>Read more</summary>
<p>
  
- Jul 2019: Joined *HSBC Software Development India* as a Software Engineer.
- Apr 2019: Conducted *NVIDIA DLI Workshop* on topics of Computer Vision, DL for multiple data types, and CUDA programming at Mahindra École Centrale, Hyderabad.
- Mar 2019: Presented our poster, *"Volumetric Prostate Segmentation from MRI using FCNN"* at *NVIDIA GPU Technology Conference (GTC)*, San Jose.

</p>
</details>

## Publications

#### Journal
- [Dilated Volumetric Network: An Enhanced Fully Convolutional Network for Volumetric Prostate Segmentation from Magnetic Resonance Imaging.](https://just-amans-stuff.s3.ap-south-1.amazonaws.com/agarwalDilated21.pdf) <br>
**Aman Agarwal**, Aditya Mishra, Priyanka Sharma, Madhushree Basavarajaiah, and Sudeep Tanwar. <br>
*Accepted in Pattern Recognition and Image Analysis, Springer, 2021.* 
- [Using LSTM for the Prediction of Disruption in ADITYA Tokamak.](https://arxiv.org/abs/2007.06230) <br>
**Aman Agarwal**, Aditya Mishra, Priyanka Sharma, Swati Jain, Sutapa Ranjan, and Ranjana Manchanda. <br>
*Submitted to Physics of Plasmas, AIP, 2020.*

#### Conference
- [Behavioral Cloning in Autonomous Vehicle Using Deep Learning.](https://amanagarwal.io/files/autoCar.pdf) <br>
**Aman Agarwal**, Aditya Mishra, and Priyanka Sharma. <br>
*Accepted in Computing Conference, London, 2021.* 

#### Poster
- [P9190: Volumetric Prostate Segmentation from MRI using FCNN.](http://dx.doi.org/10.13140/RG.2.2.12635.18721) <br>
**Aman Agarwal**, Aditya Mishra, and Priyanka Sharma. <br>
*Presented at NVIDIA GPU Technology Conference (GTC), San Jose, 2019.*

## Projects

### Using ECG for Biometric Authentication [[code](https://github.com/amanbasu/ECG-Authentication)] [[blog](https://medium.com/intel-software-innovators/ecg-to-identify-individuals-from-data-to-deployment-74cce404f9f0)]
- ECG signals from smartwatch are passed to an algorithm hosted on web.
- The algorithm converts the ECG signals to frequency spectrogram and verifies the user by a siamese network.
- ECG is unique for an individual and is promising for this task. 
[Reference](https://ieeexplore.ieee.org/document/7353191)

<!-- img src="https://media.giphy.com/media/duGB9Or2KTW4aB4KhY/giphy.gif" width="40%"/><br/-->
<!-- *Source: Security Heartbeat GIF By Sandia National Labs* -->

### 3D Prostate Segmentation of MR Images using FCNN [[code](https://github.com/amanbasu/3d-prostate-segmentation)] [[pdf](https://just-amans-stuff.s3.ap-south-1.amazonaws.com/agarwalDilated21.pdf)]
- Our enhanced V-Net model outperformed the results of the baseline V-Net in PROMISE12 challenge.
- The model was enhanced by tweaking its architecture, adding dilation and deep supervision. We improved the accuracy by 6% points.

<div style="align: center;">
  <img align="center" src="img/gif_res.gif" alt="prostate segmentation animation" width="80%" style="margin: 0 40px;"/>
</div>

<!-- img align="center" src="img/gif_res.gif" alt="prostate segmentation animation" width="80%" style="margin: 0 50px;"/><br-->

### Predicting the dynamics of Tokamak discharge [[arXiv](https://arxiv.org/abs/2007.06230)] <br> (Department of Atomic Energy, India)
- The aim of the project was to anticipate the phenomenon of Disruption during Plasma confinement inside ADITYA Tokamak.
- We were able to anticipate the disruption of plasma 12ms prior to the actual disruption (4ms earlier than the state-of-the-art models).
- Input features included the readings of various diagnostics like plasma current, mirnov oscillations, loop voltage, bolo meter readings, and many other.

<div style="align: center;">
  <img align="center" src="img/plasma_demo.gif" alt="plasma disruption animation" width="70%" style="margin: 0 60px;"/>
</div>

<!-- img align="center" src="img/plasma_demo.gif" alt="plasma disruption animation" width="70%" style="margin: 0 80px;"/><br-->
Our model predicting the disruption in tokamak plasma in real time.

### AmSat: A holistic system to classify temporal satellite imagery [[poster](https://github.com/amanbasu/amanbasu/blob/master/satellite_image_classification.pdf)]
- An algorithm to detect the construction activity from temporal satellite images.
- Temporal images were taken from Planet satellite and a labeled dataset for classification was prepared.
- A customized I3D Inception network (3DCNN) was trained on just 24 samples, giving accuracy of 85% on a test set of 21 samples.

### Speech Emotion Recognition [[code](https://github.com/amanbasu/speech-emotion-recognition)]
- Prediction of human emotions from raw audio using IEMOCAP database.
- Bidirectional LSTM was used along with local attention mechanism to focus on the part of speech which influence the emotion more.
- The architecture was trained on NVIDIA K80 system and gave results comparable to the state-of-the-art models.

### Autonomous Car [[code](https://github.com/amanbasu/Autonomous-Car-Prototype)] [[paper](https://amanagarwal.io/files/autoCar.pdf)]
- A self-driving RC car that can maneuver itself on an indoor, hand-made track.
- Convolutional Neural Network was used to classify the direction of car from dashcam images.
- The model was deployed on Raspberry Pi for real-time predictions.

<div style="align: center;">
  <img align="center" src="img/auto_car.gif" alt="autonomous vehicle animation" width="50%" style="margin: 0 100px;"/>
</div>

### Analysis of crop health
- Detection of crop species and diseases using image data.
- Predicting the severity of disease using the image along with other parameters like soil, weather, region etc.
- Trained the network using a modified loss function, taking two classes into account, specie and disease.

<!--
## Other Projects
<!--
#### Breaking Bill [[code](https://github.com/amanbasu/Breaking-Bill)]
- Android application to add expenses to a list along with the members who share it.
- Users can generate bills and split monthly expenses among members according to their contributions.
<!--
#### File Sender Application [[code](https://github.com/amanbasu/Wifi-P2p)]
- An android application to send files from one android device to another.
- The application used wifi direct and socket programming.
- It was capable to sharing any type of file format like image, audio, video, text, pdf, doc, xls etc.
<!--
#### Hospital Management System [[code](https://github.com/amanbasu/hospital-management-system)]
- A software developed on JavaFx to store hospital details like patient information, staff information, department details etc. in SQL database. 
-->

<!--
## Blog Posts
- [Ship Detection in Satellite Images from Scratch](https://medium.com/intel-software-innovators/ship-detection-in-satellite-images-from-scratch-849ccfcc3072): detecting ships in satellite images using Yolo-v3 network.
- [ECG to Identify Individuals](https://medium.com/intel-software-innovators/ecg-to-identify-individuals-from-data-to-deployment-74cce404f9f0): using ECG signals to authenticate an individual by a siamese network.
- [To be a Solutions Architect](https://medium.com/@amanag.11/to-be-a-solutions-architect-3990135ac2fe): a guide to the AWS Certified Solutions Architect Associate exam.

<!--
## Certifications and Courses
- [AWS Certified Solutions Architect - Associate](https://www.youracclaim.com/badges/ba0dc25c-3b38-4b27-878a-639eb0d888bc/public_url)
- [PCAP Certified Associate in Python Programming](https://www.youracclaim.com/badges/32c3c723-97d9-444f-bea6-5e766e5394d6/public_url)
- Deep Learning Specialization (5 courses), Prof. Andrew Ng.
- Machine Learning by Stanford University, Prof. Andrew Ng.
- Introduction to Big Data by University of California San Diego.
- Fundamentals of Accelerated Computing with CUDA, by Nvidia.
- Computer Vision Specialization by University of Buffalo.

<!--
## Achievements
- Poster presentation at **Nvidia GTC** (2019) [[poster](img/Deep%20Learning%20Research_20_P9190_Aman_Agarwal_1920x1607.png)]
- **Most Innovative Idea** award at HSBC global graduates hackathon (2019) [[blog](https://medium.com/intel-software-innovators/ecg-to-identify-individuals-from-data-to-deployment-74cce404f9f0)]

<!--
## Hobbies & Interests
- Body Building and Cooking.
- Health & Nutrition.
- Human Anatomy.
- Cricket, badminton. -->

<p align="center">  
  <a href="https://twitter.com/TheAbecedarian_">
    <img src="https://img.icons8.com/android/96/000000/twitter.png" width="40px">
  </a>
  <a href="https://www.linkedin.com/in/aman-agarwal-743548137/">
    <img src="https://img.icons8.com/android/96/000000/linkedin.png" width="40px">
  </a>
  <a href="https://github.com/amanbasu">
    <img src="https://img.icons8.com/material-sharp/96/000000/github.png" width="45px">
  </a>
</p>

<br>
<br>
