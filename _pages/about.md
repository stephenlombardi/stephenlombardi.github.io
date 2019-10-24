---
permalink: /
title: "Neural Volumes"
excerpt: "Code & data available now"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
header:
  overlay_image: dryicerender.gif
  actions:
    - label: "find out more"
      url: "/projects/neuralvolumes/"
---

{% include base_path %}

# About me

I'm a Research Scientist working at Facebook Reality Labs, Pittsburgh. I'm working on techniques to render and animate photorealistic virtual humans in real time. To do this, I'm combining ideas from computer graphics, computer vision, and machine learning. I got my Ph.D. in 2016 from Drexel University, advised by [Ko Nishino](https://vision.ist.i.kyoto-u.ac.jp/).

## Recent Projects

{% for post in site.projects limits:1 %} {% include archive-single.html type="grid" %} {% endfor %}

## Full Publication List

[**Neural Volumes: Learning Dynamic Renderable Volumes from Images**](/projects/neuralvolumes/)  
Stephen Lombardi, Tomas Simon, Jason Saragih, Gabriel Schwartz, Andreas Lehrmann, Yaser Sheikh  
ACM Transactions on Graphics (SIGGRAPH 2019) 38, 4, Article 65  
[ [arXiv](https://arxiv.org/abs/1906.07751) ] [ [supplemental video](https://research.fb.com/publications/neural-volumes-learning-dynamic-renderable-volumes-from-images/) ] [ **[code & data](https://github.com/facebookresearch/neuralvolumes)** ]  

**VR Facial Animation via Multiview Image Translation**  
Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh  
ACM Transactions on Graphics (SIGGRAPH 2019) 38, 4, Article 67  
[ [PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/) ] [ [supplemental video](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/) ]  

**Deep Appearance Models for Face Rendering**  
Stephen Lombardi, Jason Saragih, Tomas Simon, Yaser Sheikh  
ACM Transactions on Graphics (SIGGRAPH 2018) 37, 4, Article 68  
[ [arXiv](https://arxiv.org/abs/1808.00362) ] [ [supplemental video](https://research.fb.com/publications/deep-appearance-models-for-face-rendering/) ] [ [talk video](https://www.youtube.com/watch?v=3IZ2KGH1lR0) ]  

**Radiometric Scene Decomposition: Estimating Complex Reflectance and Natural Illumination from Images**  
Stephen Lombardi  
Ph.D. Thesis  

**Radiometric Scene Decomposition: Scene Reflectance, Illumination, and Geometry from RGB-D Images**  
Stephen Lombardi and Ko Nishino  
4th International Conference on 3D Vision, October 2016  
[ [arXiv](https://arxiv.org/abs/1604.01354) ]  

**Reflectance and Illumination Recovery in the Wild**  
Stephen Lombardi and Ko Nishino  
IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 38, no. 1, May 2015  

**Two-Point Gait: Decoupling Gait from Body Shape**  
Stephen Lombardi, Ko Nishino, Yasushi Makihara, Yasushi Yagi  
14th International Conference on Computer Vision, December 2013  

**Reflectance and Natural Illumination from a Single Image**  
Stephen Lombardi and Ko Nishino  
12th European Conference on Computer Vision, October 2012  
[ [talk video](http://videolectures.net/eccv2012_lombardi_image/) ]  

**Bayesian Defogging**  
Ko Nishino, Louis Kratz, and Stephen Lombardi  
International Journal of Computer Vision, vol. 98, no. 3, pg 263-278, July 2012  

**Single Image Multimaterial Estimation**  
Stephen Lombardi and Ko Nishino  
25th IEEE Conference on Computer Vision and Pattern Recognition, June 2012  

**Directional Statistics-based Reflectance Model for  
Isotropic Bidirectional Reflectance Distribution Functions**  
Ko Nishino and Stephen Lombardi  
Journal of the Optical Society of America A, vol. 28, no. 1, pg 8-18, January 2011  
