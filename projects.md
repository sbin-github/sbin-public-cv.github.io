<head>
<style>
mark { 
  background-color: white;
  color: rgb(51, 87, 128);
}
</style>
</head>


<h2> Human-Computer Interaction </h2>
**\*This project is being funded by NRF (생체신호센서융합기술개발사업)**

---
### <mark>Improvement of gesture recognition</mark>
<img src="images/gesture_static/GesturesAccuracy.png?raw=true"/>
_(Paper in preparation)_
<br>
Our study focused on obtaining high resolution features from the passive elastic elements in the human body. We achieved 97.5% accuracy in the classification of 28 gestures. The baseline SOTA method with 8-channel sEMG (Delsys, USA) achieved 94% accuracy. The experiment involved 10 subjects.
<br>
Details will be released later.

---
### <mark>Real-world application of gesture recognition</mark>
{% include youtubePlayer.html id="spRBrlzH1nE" %}
_(Paper in preparation)_
<br>
Studies on gesture recognition are often not focused on real-world applications. We studied the critical factors in gesture recognition in the presence of dynamic arm movements. Based on the analysis, we suggested sensor placement, training method, and classification algorithm for real-world applications. Especially, we proposed a reliable out-of-distribution data elimination method for the robust application.
<br>
Details will be released later.

---
### <mark>Real-time gait analysis for soft wearable robots</mark>
{% include youtubePlayer.html id="vO7Zg8ciqf0" %}
_(Under progress)_
<br>
Most gait analysis methods employ IMUs or encoders. However, those sensor system requires solid brackets, and misalignment problems are often caused. We developed a soft sensor system with an ergonomic design and optimized our algorithm for the robust real-time gait phase & mode analysis.
<br>
- A very early step of this study was announced in [IEEE ICCAS 2021](https://ieeexplore.ieee.org/document/9649762)
- Another early step is accepted by IFAC MECHATRONICS 2022

---

<br>
## Learning-based Control
---

### <mark>Transfer of human gait style to robots with limited DOFs</mark>
{% include youtubePlayer.html id="wcGt7EAkdVg" %}
_(Under progress)_
<br>
Natural-looking joint trajectory generation is essential for wearable robots. At the same time, the system must consider the wearer's safety and reasonable energy consumption. This study aims to transfer the walking style of the human being to a robot with limited DOFs based on the Adversarial Motion Priors [(X. B. Peng et al.)](https://arxiv.org/abs/2104.02180), while strictly maintaining the safety factors and observing energy efficiency.

---

<br>
## Courseworks
---

### <mark>Momentum Frame: Physics Learned from Momentum Frame</mark>
{% include youtubePlayer.html id="tmLDXB6z8Mc" %}
<br>
CS570 - Artificial Intelligence and Machine Learning

Traditional physics simulations such as MPM requires huge resource for its computation as it treats information from each point individually. We suggested a compressed and fast physics simulation based on deep learning with N2N learning and MSE + GAN loss. The model can generate whole sequence from a single frame input and more than 50 times faster than the baseline MPM method.

The network is leveraged to reconstruct physics from MSE loss, and GAN structure prevent collapse from repeated generation by preventing transition of the input distribution. Also, [CoordConv layer](https://arxiv.org/abs/1807.03247) was introduced to teach potentioal energy and could highly improve the result quality.
<br>
<!-- <p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p> -->
<!-- Remove above link if you don't want to attibute -->
