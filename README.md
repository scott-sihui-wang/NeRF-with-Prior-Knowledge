# NeRF with Prior Knowledge

## 1. Introduction

This project is hosted on `Colab`. Please follow the [link](https://drive.google.com/drive/folders/1oJkk1f5hWw_F-ndAl_hFj6-5HYAAj4gq?usp=sharing) to check out the full details of this project. Please also find the project report [here](CMPT985_Final_Report.pdf).

## 1.1 Motivation

While neural radiance fields (NeRF) have achieved great success in novel view synthesis with surprisingly simple network design, generalization remains a problem for image synthesizing in novel views. How to utilize encoding of extra information, i.e., _prior knowledge_, to improve the quality of synthesized images in novel views, therefore becomes the interest of my project.

## 1.2 Tasks of the Project

Recent variations of NeRF, such as `CodeNeRF`, `PixelNeRF`, and `VisionNeRF`, all use encoding of extra information to improve models' generalizability. As `VisionNeRF` uses `Vision Transformer` which enables modelling of long-range dependencies, it is believed that `VisionNeRF` might be more effective in boosting the model's generalization abilities.

In this project, my goals are:

- Test `VisionNeRF` on datasets to collect evidence if `VisionNeRF` has better generalization ability or not;
- Test and compare `CodeNeRF` and `PixelNeRF` on simple and complex datasets, and analysis their generalization abilities.

**Topics:** _Neural Radiance Fields (NeRF)_, _Rendering_

**Skills:** _Pytorch_, _Python_, _Deep Neural Networks_, _Jupyter Lab_, _Colab_

## 2. Results

Here are some results of my experiments:



## 3. Acknowledgement

We acknowledge the use of codes from [CodeNeRF](https://github.com/wbjang/code-nerf), [PixelNeRF](https://github.com/sxyu/pixel-nerf), and [VisionNeRF](https://github.com/ken2576/vision-nerf).
