# RSTAR: <u>R</u>otational <u>ST</u>reak <u>A</u>rtifact <u>R</u>eduction in 4D CBCT using Separable and Circular Convolutions

Author: Ziheng Deng, Jun Zhao, School of BME, Shanghai Jiao Tong University

This repository is the official implementation of RSTAR. Two main contributions of the paper are:

* We proposed the idea of rotational streak artifacts (RSA) in 4D CBCT image.
* We proposed the RSTAR-Net to effectively reduce the RSA in the spatiotemporal domain.



## What is rotational streak artifacts (RSA)?

1. According to the respiratory signal, the projection data from a full-circular scan are sorted into 10 respiratory phases.

   <div align=center><img width="360" src="gif/fig1.jpg"></div>

2. Within each phase, there are limited projection angles for CT reconstruction -> sparse-view reconstruction -> streak artifacts.

   <div align=center><img width="360" src="gif/fig2.jpg"></div>

3. The distribution of streak artifacts is closely related to the projection sampling pattern.

   <div align=center><img width="360" src="gif/fig3.jpg"></div>

4. The respiratory motion is quasi-periodic and sequential -> rotational projection sampling map.

3+4 -> RSA

<div align=center>

|          Projection Sampling Map          |             Dynamic CBCT image (with RSA)              |
| :---------------------------------------: | :----------------------------------------------------: |
| <img width="180" src="gif/4dbinmap2.gif"> | <img width="180" src="gif/rotatingstreakartifact.gif"> |

</div>

## Demo

Here are some results of our RSTAR-Net tested on __*real clinical CBCT scans*__. 

<div align=center>

| Case  |             Averaged Image             |              Uncorrected Image               |              Corrected Image               |
| :---: | :------------------------------------: | :------------------------------------------: | :----------------------------------------: |
| Case1 | <img width="180" src="gif/prior.png">  | <img width="180" src="gif/uncorrected.gif">  | <img width="180" src="gif/corrected.gif">  |
| Case2 | <img width="180" src="gif/prior2.png"> | <img width="180" src="gif/uncorrected2.gif"> | <img width="180" src="gif/corrected2.gif"> |

</div>

## RSTAR-Net

Code will be available if the paper is accepted.

<div align=center><img width="360" src="gif/fig5new.jpg"></div>

<div align=center><img width="360" src="gif/fig7.jpg"></div>



