<h1 align="center">Bayesian Image Super-Resolution</h1>

<p align="middle">
  <img src="presentation/img/readme_img_1.jpg" width="100%"></img>
</p>

A Bayesian framework for Multi-Frame Image Super-Resolution, based on ["Bayesian Image Super-Resolution" (ME Tipping and CM Bishop, NeurIPS 2003)](https://papers.nips.cc/paper/2315-bayesian-image-super-resolution.pdf). 
  
It's a two-stage method wherein the image registration parameters are estimated in the first stage, followed by estimating the HR image in the second stage. The registration parameters are estimated using the marginal likelihood, computed using using a Gaussian process prior over the HR image. In the second stage, any relevant prior (eg. MRF, TV) can be used for estimating the HR image.
  
For more details, check out:
- [Report](report/report.pdf)
- [Presentation](presentation/main.pdf)

## Results Overview

<p align="middle">
  <img src="presentation/img/readme_img_2.jpg" width="100%"></img>
</p>

## Visualization of the HR Image Estimation

<p align="middle">
  <img src="presentation/img/mfsr_tv.gif" width="40%"></img>
</p>

## Authors
- [Harshit Varma](https://github.com/hrshtv)
- [Gaurav P](https://github.com/gaurav638012)

---
*(This was done as a course project for CS736: Medical Image Computing, Spring 2021, IIT Bombay)*
