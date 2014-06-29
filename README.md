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


**Results** [More] (https://github.com/redclock/my-papers/tree/master/MIPT)

![Gallery](https://github.com/redclock/my-papers/raw/master/MIPT/sc1.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/MIPT/sc3.jpg)


Real-Time Rendering of Translucent Objects with Variable Sizes
---------
A technique to make real-time translucent rendering scalable with different size.

**Abstract**

> We present a novel technique for real-timely rendering
> translucent objects. Our technique is mainly based on
> translucent shadow maps with a new adaptive sampling
> strategy. In this sampling strategy, the hierarchy levels and
> positions for sampling are selected according to the size of
> target object. By our optimization, less storage in the texture
> is required than that in previous methods. Compared with
> previous methods, our technique provide a way to choose
> the proper sampling pattern and is applicable for a wider
> range of object sizes. With the implementation on GPU, the
> presented technique is able to render translucent objects in
> animated scenes where lights and material parameters vary
> real-timely without any lengthy preprocessing.

**Results**

![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_color1.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_color2.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_color3.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_color4.jpg)

![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_size1.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_size2.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_size3.jpg)
![Gallery](https://github.com/redclock/my-papers/raw/master/RTVS/trans_size4.jpg)
