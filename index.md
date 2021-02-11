---
layout: default
---

<img class="profile-picture" src="img/icon_bright.jpg" width="200px" />

hello world! <br>

<p align="justify" style="margin:0 30px 0 0;">
  i am a software engineer at hsbc technology india. i did my undergraduate degree in computer engineering from nirma university, ahmedabad, india. i have four years of experience in the field of artificial intelligence and machine learning. my projects includes computer vision, medical imaging, remote sensing, signal processing, nuclear physics, and parallel computing.
</p>

*i am very passionate about body building and fitness.*

## research interest
applications of deep learning and computer vision in the domain of medical imaging, nuclear physics, and autonomous driving.

## publications

#### journal
- [dilated volumetric network: an enhanced fully convolutional network for volumetric prostate segmentation from magnetic resonance imaging.](https://amanagarwal.io/3d-prostate-segmentation/) <br>
**aman agarwal**, aditya mishra, madhushree basavarajaiah, priyanka sharma, and sudeep tanwar. <br>
*accepted in pattern recognition and image analysis, springer, 2021.* 
- [using lstm for the prediction of disruption in aditya tokamak.](https://arxiv.org/abs/2007.06230) <br>
**aman agarwal**, aditya mishra, priyanka sharma, swati jain, sutapa ranjan, and ranjana manchanda. <br>
*submitted to physics of plasmas, aip, 2020.*

#### conference
- [behavioral cloning in autonomous vehicle using deep learning.](https://amanagarwal.io/files/autocar.pdf) <br>
**aman agarwal**, aditya mishra, and priyanka sharma. <br>
*accepted in computing conference, london, 2021.* 

#### poster
- [volumetric prostate segmentation from mri using fcnn.](http://dx.doi.org/10.13140/rg.2.2.12635.18721) <br>
**aman agarwal**, aditya mishra, and priyanka sharma. <br>
*presented at nvidia gpu technology conference (gtc), san jose, 2019.*

## open-source projects

### using ecg for biometric authentication [[code](https://github.com/amanbasu/ecg-authentication)] [[blog](https://medium.com/intel-software-innovators/ecg-to-identify-individuals-from-data-to-deployment-74cce404f9f0)]
- ecg signals from smartwatch are passed to a *siamese network* hosted on aws.
- the network converts the ecg signals to frequency spectrogram and verifies the user.
- ecg is unique for an individual and is very promising for this task. 
[reference](https://ieeexplore.ieee.org/document/7353191)

### object detection in satellite images [[code](https://github.com/amanbasu/ship-detection)]
- a deep network to detect ships in oceans from real-time satellite images using *yolov3*.
- trained a customized model on *darknet* and hosted it on aws to download the latest satellite images from *planet labs*, make predictions, & send the detected object coordinates to the user.

### 3d prostate segmentation of mr images using fcnn [[project page](https://amanagarwal.io/3d-prostate-segmentation/)]
- our enhanced v-net model outperformed the results of the baseline in the *promise12* challenge.
- the model was enhanced by tweaking its architecture, adding dilation, and deep supervision. we improved the accuracy by 6%.

<p align="center">  
  <img align="center" src="img/gif_res.gif" alt="prostate segmentation animation" width="80%"/>
</p>

### predicting the dynamics of tokamak discharge [[paper](https://arxiv.org/abs/2007.06230)] <br> (department of atomic energy, india)
- the aim of the project was to anticipate the phenomenon of major disruption in plasma confinement for *aditya tokamak*.
- we were able to anticipate the disruption of plasma 12 ms prior to the actual disruption (4 ms earlier than the state-of-the-art models).
- input features included the readings of various diagnostics like plasma current, mirnov oscillations, loop voltage, bolo meter readings, and many other.

<p align="center">  
  <img align="center" src="img/plasma_demo.gif" alt="plasma disruption animation" width="70%"/>
  <p align="center">our model predicting the disruption in tokamak plasma in real time.</p>
</p>

### speech emotion recognition [[code](https://github.com/amanbasu/speech-emotion-recognition)]
- prediction of human emotions from raw audio using *iemocap* database.
- bidirectional lstm was used along with local attention mechanism to focus on the part of speech which influence the emotion more.
- the architecture was trained on nvidia k80 system and gave results comparable to the state-of-the-art models.

### autonomous car [[code](https://github.com/amanbasu/autonomous-car-prototype)] [[paper](https://amanagarwal.io/files/autocar.pdf)]
- a self-driving rc car that can maneuver itself on an indoor, hand-made track.
- convolutional neural network was used to classify the direction of car from dashcam images.
- the model was deployed on raspberry pi for real-time predictions.

<p align="center">  
  <img align="center" src="img/auto_car.gif" alt="autonomous vehicle animation" width="50%"/>
</p>

<p align="center">  
  <a href="https://twitter.com/theabecedarian_">
    <img src="img/twitter.png" width="40px">
  </a>
  <a href="https://www.linkedin.com/in/aman-agarwal-743548137/">
    <img src="img/linkedin.png" width="40px">
  </a>
  <a href="https://github.com/amanbasu">
    <img src="img/github.png" width="45px">
  </a>
</p>

<br>
<br>
