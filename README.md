# Deep Convolutional Style Transfer Network
A tensorflow implementation for style transfer.

    In an attempt to learn Tensorflow I've implemented an image transformation network as described in 
    A neural algorithm of artistic style by Gatys et al.

This code is based on [OlavHN/fast-neural-style](https://github.com/OlavHN/fast-neural-style).

*****


>   In an attempt to learn Tensorflow I've implemented an deep convolutional image transformation network as described in  by Gatys et al.

Style image: starry  
---
<div  align="center"> 
<img src="examples/2-style2.jpg" width = "450" height = "300" alt="starry" align=center />
</div>

Content imgae: Tongji University
---
<div  align="center"> 
<img src="examples/012-content.jpg" width = "450" height = "300" alt="Chairman Mao" align=center />
</div>

---
Result 1: iteration = 500
---
<div  align="center"> 
<img src="examples/tongji20_iter_500.jpg" width = "450" height = "300"  align=center />
</div>

Result 2: iteration 1000
---
<div  align="center"> 
<img src="examples/tongji20.jpg" width = "450" height = "300"  align=center />
</div>

###
 Style: East of China
 ---
 <div  align="center"> 
<img src="examples/444.png" width = "450" height = "300"  align=center />
</div>

###
Style: Scream
---
<div  align="center"> 
<img src="examples/333.png" width = "450" height = "300"  align=center />
</div>

###
Style: Colorful
---
<div  align="center"> 
<img src="examples/222.png" width = "450" height = "300"  align=center />
</div>

###
Style: Lover
---
<div  align="center"> 
<img src="examples/111.png" width = "450" height = "300"  align=center />
</div>

###
Running
    python eval.py --model_file <your path to wave.ckpt-done> --image_file img/test.jpg

Use --iterations to change the number of iterations (default 1000).

###
Requirements and Prerequisites:

* Python 2.7.x
* Tensorflow >= 1.0
