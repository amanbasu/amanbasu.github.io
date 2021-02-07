---
layout: default
---

<img class="profile-picture" src="img/icon_bright.jpg" width="200px" />

hello world! <br>

<p align="justify" style="margin:0 30px 0 0;">
  i am a software engineer at <span style="color: #ef241c">hsbc technology</span> india. i did my undergraduate degree in computer engineering from <span style="color: #0a377a">nirma university</span>, ahmedabad, india. i have four years of experience in the field of artificial intelligence and machine learning. my projects includes computer vision, medical imaging, remote sensing, signal processing, nuclear physics, and parallel computing.
</p>

*i am very passionate about body building and fitness.*

## research interest
applications of deep learning and computer vision in the domain of medical imaging, nuclear physics, and autonomous driving.

## news
- jan 2021: passed the <span style="color: #ffa800">tensorflow developer certification</span> exam.
- oct 2020: our paper on prostate segmentation accepted in *pattern recognition & image inalysis*.
- sep 2020: bagged the <span style="color: #ef241c">hsbc hero award</span> for our exceptional work at hsbc during covid-19 pandemic.
- aug 2020: got certified as <span style="color: #ff9900">aws</span> machine learning specialist, developer, and solutions architect.
- apr 2020: gave a talk on *super-resolution using deep learning* at <span style="color: #0a377a">nirma university</span>, ahmedabad.
- oct 2019: graduated from <span style="color: #0a377a">nirma university</span> with a bachelor's degree in computer engineering.

<details><summary>read more</summary>
<p>
  <ul>
    <li>sep 2019: received the <i>most innovative idea</i> award for our work on authenticating users from electrocardiogram signals and deep learning methods.</li>
    <li>jul 2019: joined <span style="color: #ef241c">hsbc software development</span>, india as a software engineer.</li>
    <li>apr 2019: conducted <span style="color: #76b900">nvidia dli workshop</span> on topics of computer vision, dl for multiple data types, and cuda programming at mahindra école centrale, hyderabad.</li>
    <li>apr 2019: presented our poster, on prostate segmentation at <span style="color: #76b900">nvidia gpu technology conference (gtc)</span>, san jose.</li>
  </ul>
</p>
</details>

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
<img src="https://img.shields.io/github/stars/amanbasu/ecg-authentication?color=0088ff"/> <img src="https://img.shields.io/github/forks/amanbasu/ecg-authentication?color=ff8800"/> <img src="https://img.shields.io/badge/python-3.6+-ee0044?logo=python"/>
- ecg signals from smartwatch are passed to a *siamese network* hosted on <span style="color: #ff9900">aws</span>.
- the network converts the ecg signals to frequency spectrogram and verifies the user.
- ecg is unique for an individual and is very promising for this task. 
[reference](https://ieeexplore.ieee.org/document/7353191)

<!-- img src="https://media.giphy.com/media/dugb9or2ktw4ab4khy/giphy.gif" width="40%"/><br/-->
<!-- *source: security heartbeat gif by sandia national labs* -->

### object detection in satellite images [[code](https://github.com/amanbasu/ship-detection)]
<img src="https://img.shields.io/github/stars/amanbasu/ship-detection?color=0088ff"/> <img src="https://img.shields.io/github/forks/amanbasu/ship-detection?color=ff8800"/> <img src="https://img.shields.io/github/issues-closed/amanbasu/ship-detection?color=00ff00"/>
- a deep network to detect ships in oceans from real-time satellite images using *yolov3*.
- trained a customized model on *darknet* and hosted it on <span style="color: #ff9900">aws</span> to download the latest satellite images from *planet labs*, make predictions, & send the detected object coordinates to the user.

### 3d prostate segmentation of mr images using fcnn [[project page](https://amanagarwal.io/3d-prostate-segmentation/)]
<img src="https://img.shields.io/github/stars/amanbasu/3d-prostate-segmentation?color=0088ff"/> <img src="https://img.shields.io/github/forks/amanbasu/3d-prostate-segmentation?color=ff8800"/> <img src="https://img.shields.io/github/issues-closed/amanbasu/3d-prostate-segmentation?color=00ff00"/> <img src="https://img.shields.io/badge/tensorflow-1.10.0-green?logo=tensorflow"/> <img src="https://img.shields.io/badge/python-3.6+-ee0044?logo=python"/>
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
<img src="https://img.shields.io/github/stars/amanbasu/speech-emotion-recognition?color=0088ff"/> <img src="https://img.shields.io/github/forks/amanbasu/speech-emotion-recognition?color=ff8800"/> <img src="https://img.shields.io/github/issues-closed/amanbasu/speech-emotion-recognition?color=00ff00"/> <img src="https://img.shields.io/badge/tensorflow-1.10.0-green?logo=tensorflow"/> <img src="https://img.shields.io/badge/python-3.6+-ee0044?logo=python"/>
- prediction of human emotions from raw audio using *iemocap* database.
- bidirectional lstm was used along with local attention mechanism to focus on the part of speech which influence the emotion more.
- the architecture was trained on <span style="color: #76b900">nvidia</span> k80 system and gave results comparable to the state-of-the-art models.

### autonomous car [[code](https://github.com/amanbasu/autonomous-car-prototype)] [[paper](https://amanagarwal.io/files/autocar.pdf)]
<img src="https://img.shields.io/github/stars/amanbasu/autonomous-car-prototype?color=0088ff"/> <img src="https://img.shields.io/github/forks/amanbasu/autonomous-car-prototype?color=ff8800"/> <img src="https://img.shields.io/badge/python-3.6+-ee0044?logo=python"/>
- a self-driving rc car that can maneuver itself on an indoor, hand-made track.
- convolutional neural network was used to classify the direction of car from dashcam images.
- the model was deployed on raspberry pi for real-time predictions.

<p align="center">  
  <img align="center" src="img/auto_car.gif" alt="autonomous vehicle animation" width="50%"/>
</p>

<!--
## other projects
### analysis of crop health
- detection of crop species and diseases using image data.
- predicting the severity of disease using the image along with other parameters like soil, weather, region etc.
- trained the network using a modified loss function, taking two classes into account, specie and disease.

<!--
#### breaking bill [[code](https://github.com/amanbasu/breaking-bill)]
- android application to add expenses to a list along with the members who share it.
- users can generate bills and split monthly expenses among members according to their contributions.
<!--
#### file sender application [[code](https://github.com/amanbasu/wifi-p2p)]
- an android application to send files from one android device to another.
- the application used wifi direct and socket programming.
- it was capable to sharing any type of file format like image, audio, video, text, pdf, doc, xls etc.
<!--
#### hospital management system [[code](https://github.com/amanbasu/hospital-management-system)]
- a software developed on javafx to store hospital details like patient information, staff information, department details etc. in sql database. 
-->

<!--
## blog posts
- [ship detection in satellite images from scratch](https://medium.com/intel-software-innovators/ship-detection-in-satellite-images-from-scratch-849ccfcc3072): detecting ships in satellite images using yolo-v3 network.
- [ecg to identify individuals](https://medium.com/intel-software-innovators/ecg-to-identify-individuals-from-data-to-deployment-74cce404f9f0): using ecg signals to authenticate an individual by a siamese network.
- [to be a solutions architect](https://medium.com/@amanag.11/to-be-a-solutions-architect-3990135ac2fe): a guide to the aws certified solutions architect associate exam.

<!--
## certifications and courses
- [aws certified solutions architect - associate](https://www.youracclaim.com/badges/ba0dc25c-3b38-4b27-878a-639eb0d888bc/public_url)
- [pcap certified associate in python programming](https://www.youracclaim.com/badges/32c3c723-97d9-444f-bea6-5e766e5394d6/public_url)
- deep learning specialization (5 courses), prof. andrew ng.
- machine learning by stanford university, prof. andrew ng.
- introduction to big data by university of california san diego.
- fundamentals of accelerated computing with cuda, by nvidia.
- computer vision specialization by university of buffalo.

<!--
## achievements
- poster presentation at **nvidia gtc** (2019) [[poster](img/deep%20learning%20research_20_p9190_aman_agarwal_1920x1607.png)]
- **most innovative idea** award at hsbc global graduates hackathon (2019) [[blog](https://medium.com/intel-software-innovators/ecg-to-identify-individuals-from-data-to-deployment-74cce404f9f0)]

<!--
## hobbies & interests
- body building and cooking.
- health & nutrition.
- human anatomy.
- cricket, badminton. -->

## certifications

<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="2e50b4df-73d4-4a13-b7fa-f0d5338a4207" data-share-badge-host="https://www.youracclaim.com"></div><script type="text/javascript" async src="//cdn.youracclaim.com/assets/utilities/embed.js"></script>

<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="734d7780-ed11-4f97-96bd-4d50da410aa8" data-share-badge-host="https://www.youracclaim.com"></div><script type="text/javascript" async src="//cdn.youracclaim.com/assets/utilities/embed.js"></script>

<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="ba0dc25c-3b38-4b27-878a-639eb0d888bc" data-share-badge-host="https://www.youracclaim.com"></div>

<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="32c3c723-97d9-444f-bea6-5e766e5394d6" data-share-badge-host="https://www.youracclaim.com"></div><div style="display:inline-block;float:left;"><a href="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/28247976"><img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/28247976" width="150"></a></div>


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
