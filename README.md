# DataEnhancementLearn

[AugMix_DeepMind]:https://arxiv.org/abs/1912.02781v1

## :new_moon: Objective
&ensp;&ensp;&ensp;&ensp;Most of the _`Deep Learning`_ tasks are limited by their training datasets. Focusing on a specific objective, relative data could be rare or deficient. A manually labeled dataset could be a solution, but still facing quantity and quality problems. It is a worth considering question that, what can we do to improve the model performance via limited data. </br>&ensp;&ensp;&ensp;&ensp;It is important for models see various datas to achieve a robust outcome. They should see through phenomena and grasp the important pattern or factors. This is similar to the Ockham's Razor. In order to do so, <b>_`Data Enhancement`_</b> is expected. 

- <b>_Data Enhancement_</b>
    - <b>_Supervised Methods_</b>
        - _Geometric Transformation_
        - _Color Noice Transformation_
        - _Gray Scale Transformation_
    - <b>_Un-supervised Methods_</b>
        - _GAN Network Generation_
        - _Unsupervised Strages_

## :waxing_crescent_moon: Geometric Transformation
- Flip
- Rotation/Reflection
- Crop
- Zoom
## :first_quarter_moon: Color Transformation
- Noise
    - Gauss Noise
    - CoarseDropout
    - SimplexNoiseAlpha 
    - FrequencyNoiseAlpha 
- Pixel Transform
    - Gauss Noise
    - Salt-and-Pepper Noise
    - Histogram Equalization
    - Modify Hue, Saturation, Lightness
    - Random Mask
    - Color Jittering

## :waxing_gibbous_moon: Gray Scale Transformation

## :full_moon: GAN Network Generation

## :waning_gibbous_moon: Unsupervised Strages
- AutoAugment
- Population Based Augmentation (PBA)

## :last_quarter_moon: Data Enhancement in Computer Vision
- Random erasing
    - Image-aware Random Erasing (IRE)
    - Object-aware Random Erasing (ORE)
    - IRE + ORE
- Cutout
- Mixup
- CoutMix
## :waning_crescent_moon: Data Enhancement in Natural Language Processing


# Reference
[1] [https://zhuanlan.zhihu.com/p/101432423](https://zhuanlan.zhihu.com/p/101432423)</br>
[2] [https://www.zhihu.com/question/319291048](https://www.zhihu.com/question/319291048)</br>
[3] [https://blog.csdn.net/lxh248866/article/details/119989249](https://blog.csdn.net/lxh248866/article/details/119989249)</br>
[4] [https://blog.csdn.net/qq_27590277/article/details/126314073?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-4-126314073-blog-119989249.pc_relevant_3mothn_strategy_recovery&spm=1001.2101.3001.4242.3&utm_relevant_index=6](https://blog.csdn.net/qq_27590277/article/details/126314073?utm_medium=distribute.pc_relevant.none-task-blog-2\~default\~baidujs_baidulandingword\~default-4-126314073-blog-119989249.pc_relevant_3mothn_strategy_recovery&spm=1001.2101.3001.4242.3&utm_relevant_index=6)</br>