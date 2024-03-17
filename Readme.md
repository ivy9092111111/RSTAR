# RSTAR: <u>R</u>otational <u>ST</u>reak <u>A</u>rtifact <u>R</u>eduction in 4D CBCT using Separable and Circular Convolutions

Author: Ziheng Deng, Jun Zhao, School of BME, Shanghai Jiao Tong University

This repository is the official implementation of RSTAR. Two main contributions of the paper are:

* We proposed the idea of rotational streak artifacts (RSA) in 4D CBCT image.
* We proposed the RSTAR-Net to effectively reduce the RSA in the spatiotemporal domain.



## Demo

Here are some results of our RSTAR-Net tested on __*real clinical CBCT scans*__. 

| Case  |             Averaged Image             |              Uncorrected Image               |              Corrected Image               |
| :---: | :------------------------------------: | :------------------------------------------: | :----------------------------------------: |
| Case1 |  <img width="180" src="gif/prior.pn">  | <img width="180" src="gif/uncorrected.gif">  | <img width="180" src="gif/corrected.gif">  |
| Case2 | <img width="180" src="gif/prior2.png"> | <img width="180" src="gif/uncorrected2.gif"> | <img width="180" src="gif/corrected2.gif"> |



## What is rotational streak artifacts (RSA)?

|          Projection Sampling Map          |                   Dynamic CBCT image                   |
| :---------------------------------------: | :----------------------------------------------------: |
| <img width="300" src="gif/4dbinmap2.gif"> | <img width="300" src="gif/rotatingstreakartifact.gif"> |



## RSTAR-Net

Code will be available if the paper is accepted.

<div align=center><img width="600" src="gif/fig5new.jpg"></div>

<div align=center><img width="600" src="gif/fig7.jpg"></div>



