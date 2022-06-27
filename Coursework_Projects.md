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
### <mark>(CS570) Momentum Frame: Physics Learned from Momentum Frame</mark>
{% include youtubePlayer.html id="tmLDXB6z8Mc" %}
<br>
Traditional physics simulations such as MPM requires huge resource for its computation as it treats information from each point individually. We suggested a compressed and fast physics simulation based on deep learning with N2N learning and MSE + GAN loss. The network is leveraged to reconstruct physix from MSE loss, and GAN structure prevent collapse from repeated generation by preventing transition of the input distribution. Also, [CoordConv layer](https://arxiv.org/abs/1807.03247) was introduced to teach potentioal energy and could highly improve the result quality. The model generate whole sequence from a single frame input more than 50 times faster than a baseline MPM method.
<br>
Details will be released later.

---
