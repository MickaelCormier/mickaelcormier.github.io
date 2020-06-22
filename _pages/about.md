---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
toc: true
---

My name is Mickael Cormier and I’m a research assistant at the [Karlsruhe Institute of Technology](http://www.kit.edu/english/index.php), working in close cooperation with the [Fraunhofer Institute for Optronics, System Technologies and Image Exploitation IOSB](https://www.iosb.fraunhofer.de/servlet/is/12481/) in Karlsruhe (Germany), which is one of the largest research institutes in the field of image acquisition, processing and analysis in Europe.
{: .text-justify}

The focus of my work is centered around the two topics: 
* Machine Learning / Deep Learning
* Computer Vision 

---

Open Positions for Students 
======
I'm always looking for students supporting me with my research. Some currently available topics are listed below. Topics for thesis or "Hiwi" positions are not limited to those below, so don't hesitate to ask me for other related positions.<br>

→ [Internship Web Frontend / Fullstack Development for a Deep Learning Annotations Tool (German)](https://mickaelcormier.github.io/files/opening/20200412_praxis_frontend_cormier.pdf) (Praxissemester)<br>
→ [Image and Video Annotation (German)](https://mickaelcormier.github.io/files/opening/20200622_hiwi_annotation_cormier.pdf) (Hiwi)<br>
→ [Crowd Pose Estimation and Activity Recognition](https://mickaelcormier.github.io/files/opening/20200622_hiwi_crowd-hpe_cormier.pdf) (Hiwi)<br>
→ [Embedded Deployment of Deep-Learning models on Jetson Plattforms(German)](https://mickaelcormier.github.io/files/opening/20200622_hiwi_jetson_cormier.pdf) (Hiwi)<br>
→ [3D Human Pose Estimation (German)](https://mickaelcormier.github.io/files/opening/20200409_ba_3d-hpe_cormier.pdf) (BA)<br>
→ [Group-Level Emotion Recognition (German)](https://mickaelcormier.github.io/files/opening/20200412_ma_ger_cormier.pdf) (MA)<br>
→ [3D Crowd Pose Estimation from Monocular Videos (German)](https://mickaelcormier.github.io/files/opening/20200622_ma_crowd-3d-hpe_cormier.pdf) (MA)<br>
→ [Robust Real-World Crowd Pose Estimation (German)](https://mickaelcormier.github.io/files/opening/20200622_ma_crowd-hpe_cormier.pdf) (MA)<br>
→ [Robust Real-World Crowd Pose Tracking (German)](https://mickaelcormier.github.io/files/opening/20200622_ma_crowd-hpe-tracking_cormier) (MA)<br>


---

Research Topics
======
Based on these general interests, I’m working in four main fields: [Video Activity Recognition](#var), [3D Human Pose Estimation](#3dhpe), [Continual Learning](#cl) and [Face Expression Recognition](#er). I try to develop and apply deep learning methods in order to tackle those tasks. You can find more information about the fields below. 
{: .text-justify}

**Ad**: You are a student in Computer Science, Mathematics, Physics or other related fields looking for a research topic for your thesis? You are motivated to work on challenging and interesting tasks? Feel free to contact me.
{: .notice--success}

<a name="var"></a>Video Activity Recognition
------

Action recognition in surveillance video footage is an important research topic in the computer vision community, due to the importance of its applications. Surveillance cameras are increasingly used; however, the monitoring capacity of law enforcement agencies can’t keep up with the huge amount of data being produced. Therefore, automatic or computer assisted surveillance plays a key role for security in public areas such as market places, shops, airports, etc. However, the task of tracking, understanding and reacting to what is happening in long video sequence is really challenging.

In my work, I focus on two main aspects: <br />
→ generation of qualitative annotations for training deep neural networks, using techniques such as Video Description and Captioning, Video Summarization and Generative Adversarial Networks (GAN). <br />
→ investigation of Deep Multitask Architectures for Action Recognition in Surveillance Videos using 3D Convolutions, Long Short-Term Memories (LSTM), multiple Frame-Rate Analysis and Graph Neural Networks (GNN).

<a name="3dhpe"></a> 3D Human Pose Estimation
------
Video-based Action Recognition in surveillance videos remains a challenging task, even with large annotated datasets. In order to comprehend a given situation, a human operator will usually focus on specific details such as body part motions. A group of given key points will move specifically together resulting in unique actions. In order to integrate such temporal context and common-sense knowledge into automatic systems, models need to be able to estimate and detect the 2D position of body parts. Moreover, estimating 3D key points over time provides useful information such as the velocity, acceleration ratio and motion direction for a given time period. Here, I focus on two main aspects: <br />
→ estimation and detection of the 3D position of body parts in near-real-time.  <br />
→ use of 3D human body poses for video action recognition.
{: .text-justify}


<a name="cl"></a> Continual Learning
------
Even the best system for action recognition in surveillance video footage is expected to eventually deliver false alarm or to fail to detect a dangerous situation. To improve such a system’s accuracy over time, it is important to collect and integrate user feedback without disturbing the main use of the system. Not only for system failures but also for successes.
Therefore, policies need to be defined to automatically retrain and / or fine tune the existing model with newly collected data. To this end, objective criteria need to be defined to constantly evaluate the system’s performance and its robustness to diverse bias factors, which could appear over time with the addition of new data.
{: .text-justify}

<a name="er"></a> Emotion Recognition
------

While faces and body expressions alone are insufficient to perform a reverse inference of single image to emotion, we undoubtedly use these visual cues daily to navigate our social world.
To what extent (and how) can we design models to accurately interpret an emotion or intention from face expression recognition? And to what degree are these visual cues influenced by body pose and context? Which context, personal and cultural believes must be accounted for to avoid unethical bias?

{: .text-justify}

