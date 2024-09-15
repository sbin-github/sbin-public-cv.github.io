<head>
<style>
mark { 
  background-color: white;
  color: rgb(51, 87, 128);
}
</style>
</head>

<h1> RESEARCH </h1>

<hr style="height:3px; background-color:black; border:0;">


<h2>Optimal/Learning-based Control</h2>
**\*Funded by NRF (보행장애 완전극복 웨어러블 로봇기술을 위한 인간운동제어이론 연구)**
<br>
**\*\*Project goal: Human-integrated control for wearable robots to completely overcome gait disorders**


---

### <mark>MPC-based Stride-to-Stride Reference Trajectory Generation</mark>
{% include youtube.html id="DeFXXFtqL-Y" %}
_(Under progress)_
<br>
The research aims to one-stride reference generation for a biped robot suffering high-level disturbances, including modeling errors and external forces. A conservative one-stride reference is generated, which will be tracked by low-level control. The generated reference considers not only ZMP-based stable motion but also static transition between each gait.

---

### <mark>Transfer of style to robots with limited DOFs</mark>
{% include youtube.html id="wcGt7EAkdVg" %}
_(Under progress)_
<br>
Generating natural-looking joint trajectories is crucial for wearable robots, while also ensuring the wearer's safety and maintaining reasonable energy consumption. This study aims to transfer human walking styles to a robot with limited degrees of freedom (DOFs) using [Adversarial Motion Priors](https://arxiv.org/abs/2104.02180), all while strictly adhering to safety constraints and optimizing for energy efficiency.

---
### <mark>Robust controller for wearable robots</mark>
<!-- {% include youtube.html id="dueZzaKWLBw" %} -->
{% include youtube.html id="u0uSIhfIuNE" %}
_(Under progress)_
<br>
Controlling a wearable robot necessitates accounting for unobservable, nonlinear, and non-periodic disturbances from its user. This project aims to develop a robust controller by combining learning-based and model-based control approaches. Additionally, the human walking style is transferred to the robot’s joint trajectory, taking into consideration the safe range of motion and the specific needs of real-world patients.

---

<br>
<h2> Human-Computer Interaction </h2>
**\*Funded by NRF (생체신호센서융합기술개발사업)**
<br>
**\*\*Project goal: Human-robot high-speed synchronization**

---
### <mark>Improvement of gesture recognition</mark>
<img src="images/gesture_static/GesturesAccuracy.png?raw=true"/>
<br>
Our study focused on extracting high-resolution features from the passive elastic elements of the human body, achieving 98.0% accuracy in classifying 28 gestures. In comparison, the baseline method using an 8-channel sEMG system (Delsys, USA) reached 93.1% accuracy. The experiment involved 10 subjects and was evaluated using 5-fold cross-validation.
<br>
- Published in the *IEEE Transactions on Industrial Informatics (IF=11.648)*

---
### <mark>Robust real-world application of gesture recognition</mark>
{% include youtube.html id="spRBrlzH1nE" %}
_(Paper in preparation)_
<br>
Research on gesture recognition frequently overlooks considerations relevant to real-world applications. In this study, we investigated the key factors influencing gesture recognition in the presence of dynamic arm movements. Based on our analysis, we proposed optimized sensor placement, training methods, and classification algorithms specifically designed for practical deployment. Additionally, we introduced a reliable method for eliminating out-of-distribution data, enhancing the robustness of the system in real-world scenarios.
<br>
Details will be released later.

---
### <mark>Real-time gait analysis for soft wearable robots</mark>
{% include youtube.html id="vO7Zg8ciqf0" %}
{% include youtube.html id="fRwCSk-NRls" %}
_(Under progress)_
<br>
Most gait analysis methods rely on IMUs or encoders; however, these sensor systems necessitate rigid mounts, often resulting in misalignment issues. To overcome this challenge, we developed a soft sensor system with an ergonomic design and optimized our algorithm to enable robust, real-time analysis of gait phases and modes.
<br>
- A very early step of this study was announced in [IEEE ICCAS 2021](https://ieeexplore.ieee.org/document/9649762)
- Another early step was announced in [IFAC MECHATRONICS 2022](https://www.sciencedirect.com/science/article/pii/S240589632202612X)

---

<br>
## Courseworks
---

### <mark>Momentum Frame: Training Physics from Momentum Information</mark>
{% include youtube.html id="tmLDXB6z8Mc" %}
<br>
CS570 - Artificial Intelligence and Machine Learning

Traditional physics simulations, such as MPM, require significant computational resources because they process information from each point individually. We proposed a compressed and accelerated physics simulation based on deep learning, utilizing N2N learning and a combination of MSE and GAN loss. Our model can generate an entire sequence from a single input frame and operates more than 50 times faster than the baseline MPM method.

The network utilizes MSE loss to reconstruct the underlying physics, while the GAN structure helps prevent collapse from repeated generation by maintaining the stability of the input distribution. Additionally, the [CoordConv layer](https://arxiv.org/abs/1807.03247) was introduced to model potential energy, which significantly enhances the quality of the results.
<br>
<!-- <p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p> -->
<!-- Remove above link if you don't want to attibute -->
