my-papers
=========
My publications here.

Multi-Image based Photon Tracing for Interactive Global Illumination
---------
This technique is for interactive rendering of global illumination. It is compatible with diffuse inter-reflections, glossy surfaces and caustics in fully dynamic scenes. 

Result frame rates are 10~30 FPS in GTX 260.  

**Abstract**

> Image space photon mapping has the advantage of simple implementation on GPU without pre-computation of
> complex acceleration structures. However, existing approaches use only a single image for tracing caustic photons,
> so they are limited to computing only a part of the global illumination effects for very simple scenes. In this paper
> we fully extend the image space approach by using multiple environment maps for photon mapping computation to
> achieve interactive global illumination of dynamic complex scenes. The two key problems due to the introduction
> of multiple images are 1) selecting the images to ensure adequate scene coverage; and 2) reliably computing 
> ray-geometry intersections with multiple images. We present effective solutions to these problems and show that, with
> multiple environment maps, the image-space photon mapping approach can achieve interactive global illumination
> of dynamic complex scenes. The advantages of the method are demonstrated by comparison with other existing
> interactive global illumination methods.

**Gallery**
![RESULT](www.github.com/redclock/my-papers/raw/MIPT/sc1.jpg)
