<div align="center">

# Generalizable and Animatable 3D Full-Head Gaussian Avatar from a Single Image

[Shuling Zhao](https://github.com/ShaelynZ)  and  [Dan Xu](https://www.danxurgb.net/)

The Hong Kong University of Science and Technology 

<a href='https://shaelynz.github.io/fhavatar/'><img src='https://img.shields.io/badge/Project-Page-green.svg'></a> 
<a href=''><img src='https://img.shields.io/badge/Paper-arXiv-red'></a>

<b>TL;DR</b>: Given a single input image, we reconstruct animatable 3D full-head Gaussian avatars in a single forward pass, providing 360° view synthesis and supporting real-time (246 FPS) animation.

<img src="assets/result_1.gif"  width="90%"/>
<img src="assets/result_2.gif"  width="90%"/>

### Method
<img src="assets/framework.jpg"  width="100%"/>
Given an input source image, the UV space feature extraction module extracts its global and local UV feature maps for animatable 3D full-head reconstruction. The symmetric UV space feature fusion module takes advantage of the symmetry of human faces and the UV space to combine these UV feature maps. From the predicted UV Gaussian attribute maps, 3D Gaussian primitives are sampled, which can be animated with a parametric face model and rendered given a camera pose.
</div>

## Updates
- **`2026/01/19`**: We released this repo.

<!-- ## Code
Coming soon. Please stay tuned. -->

## Citation
```
@article{zhao2026generalizable,
  title={Generalizable and Animatable 3D Full-Head Gaussian Avatar from a Single Image},
  author={Zhao, Shuling and Xu, Dan},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2026}
}
```

## Contact
If you have any question or collaboration needs, please email `szhaoax@connect.ust.hk`.
