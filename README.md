# Deep Convolutional Style Transfer Network
A tensorflow implementation for style transfer.

    In an attempt to learn Tensorflow I've implemented an Image Transformation Network as described in 
    Perceptual Losses for Real-Time Style Transfer and Super-Resolution by Johnson et al.

This code is based on [OlavHN/fast-neural-style](https://github.com/OlavHN/fast-neural-style).

*****


>   In an attempt to learn Tensorflow I've implemented an Image Transformation Network as described in Perceptual Losses for Real-Time Style Transfer and Super-Resolution by Johnson et al.

Style image: starry  
---
<div  align="center"> 
<img src="examples/2-style2.jpg" width = "450" height = "300" alt="starry" align=center />
</div>
![](examples/2-style2.jpg) 

Content imgae: Tongji University
---
![](examples/012-content.jpg)

---
iteration = 500
---
![](examples/tongji20_iter_500.jpg)

iteration = 1000
---
![](examples/tongji20.jpg)

    python eval.py --model_file <your path to wave.ckpt-done> --image_file img/test.jpg

###
 Style: East of China
 ---
![](examples/444.png)  

###
Style: Scream
---
![](examples/333.png)

###
Style: Colorful
---
![](examples/222.png)

###
Style: Lover
---
![](examples/111.png)
