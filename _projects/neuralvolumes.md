---
title: "Neural Volumes"
excerpt: "Neural Volumes is a method for representing dynamic objects, supervised directly from 2D images from a multi-view capture stage."
collection: projects
orderdate: 2019-07-01 00:00:00
header: 
  image: neuralvolumes2.jpg
  teaser: neuralvolumes3.jpg
gallery:
  - url: steve.gif
    image_path: steve.gif
    alt: "neural volume example 1"
    title: "Virtual Human"
  - url: dryicerender2.gif
    image_path: dryicerender2.gif
    alt: "neural volume example 2"
    title: "Sublimating Dry Ice"
---

We present a learning-based approach to representing dynamic objects, supervised directly from 2D images in a multi-view capture setting. The method consists of an encoder-decoder network that transforms input images into a 3D volume representation, and a differentiable ray-marching operation that enables end-to-end training. The method learns a dynamic warp field that greatly improves the apparent resolution and reduces grid-like artifacts and jagged motion.

[Read the paper](https://research.fb.com/publications/neural-volumes-learning-dynamic-renderable-volumes-from-images/)  
[Download the code & data](https://github.com/facebookresearch/neuralvolumes)  

### Differentiable Ray Marching

The decoder generates a volume that contains RGB and opacity values. To render this volume to an image, we use a differentiable ray marching algorithm. The idea is that we integrate the RGB and opacity values through the volume along the ray defined by each pixel.

{% include figure image_path="/images/raymarching.gif" caption="Visualization of differentiable ray marching. A line integral is computed through the volume along the ray defined by each pixel. This allows the system to be trained end-to-end." %}

### Example Results

{% include gallery caption="Example reconstructions" %}

### Bibtex
<pre>
@article{Lombardi:2019,
 author = {Lombardi, Stephen and Simon, Tomas and Saragih, Jason and Schwartz, Gabriel and Lehrmann, Andreas and Sheikh, Yaser},
 title = {Neural Volumes: Learning Dynamic Renderable Volumes from Images},
 journal = {ACM Trans. Graph.},
 issue_date = {July 2019},
 volume = {38},
 number = {4},
 month = jul,
 year = {2019},
 pages = {65:1--65:14},
 articleno = {65},
 numpages = {14},
 publisher = {ACM},
 address = {New York, NY, USA},
} 
</pre>
