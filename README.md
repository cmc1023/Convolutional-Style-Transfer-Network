# Deep Convolutional Style Transfer Network
A tensorflow implementation for style transfer.

    In an attempt to learn Tensorflow I've implemented an Image Transformation Network as described in 
    Perceptual Losses for Real-Time Style Transfer and Super-Resolution by Johnson et al.

This code is based on [OlavHN/fast-neural-style](https://github.com/OlavHN/fast-neural-style).

*****


>   In an attempt to learn Tensorflow I've implemented an Image Transformation Network as described in Perceptual Losses for Real-Time Style Transfer and Super-Resolution by Johnson et al.

![](examples/2-style2.jpg) 

![](examples/012-content.jpg)

---
iteration = 500
---
![](examples/tongji20_iter_500.jpg)

iteration = 1000
---
![](examples/tongji20.jpg)

    python eval.py --model_file <your path to wave.ckpt-done> --image_file img/test.jpg


style image: Lotus

<img src="examples/5-style.jpg" width = "533" height = "398" alt="5-style" align=left />

<br /><br />

content imgae: Tongji University

<img src="examples/6-content.jpg" width = "530" height = "398" alt="6-content" align=left />

<br /><br />

iteration = 500
---
![](examples/tongji07_iter_500.jpg)

iteration = 1000
---
![](examples/tongji07.jpg)
