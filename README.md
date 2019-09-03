# ScratchDetection

Automatic Detection of Industrial Scratches Based on Multi-Feature Fusion Network

<img src="https://github.com/love6tao/ScratchDetection/blob/master/GIF/image19.GIF" width="256"/> <img src="https://github.com/love6tao/ScratchDetection/blob/master/GIF/image20.GIF" width="256"/> 


<img src="https://github.com/love6tao/ScratchDetection/blob/master/GIF/image21.GIF" width="256"/> <img src="https://github.com/love6tao/ScratchDetection/blob/master/GIF/image22.GIF" width="256"/> 


For scratch detect, our contribution contains:

* multi-feature fusion: dual-attention mechanism and context fusion
* auxiliary loss: enrich the context information and accelerating the training
* real-world industrial datasets

## Compare Results

<img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/soureimage_1.bmp" width="256"/> <img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/%E8%B0%B7%E5%BA%95%E6%9C%80%E5%B0%8F%E5%80%BC.jpg" width="256"/> 

    Original defect                     image histogram-based thresholding[1]

<img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/%E5%8A%A8%E8%83%BD%E4%BF%9D%E6%8C%81%E6%B3%95.jpg" width="256"/> <img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/Kittler%E6%9C%80%E5%B0%8F%E9%94%99%E8%AF%AF%E5%88%86%E7%B1%BB%E6%B3%95.jpg" width="256"/> 

    Moment-preserving thresholding[2]                     Kittler[3]
    
   <img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/ISODATA(%E4%B9%9F%E5%8F%AB%E5%81%9Aintermeans%E6%B3%95%EF%BC%89.jpg" width="256"/> <img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/Yen%E6%B3%95.jpg" width="256"/> 

    ISODATA[4]                              Yen[5]
    
   <img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/Garbor%20Based.png" width="256"/> <img src="https://github.com/love6tao/ScratchDetection/blob/master/compare%20results/Our%20Method.bmp" width="256"/> 

    Garbor Based[6]                     Our Method
    
  
* histogram-based thresholding 谷底最小值[1]：C. A. Glasbey, "An analysis of histogram-based thresholding algorithms," CVGIP: Graphical Models and Image Processing, vol. 55, pp. 532-537, 1993.

* Moment-preserving thresholding动能保持法[2]：W. Tsai, “Moment-preserving thresholding: a new approach,” Comput.Vision Graphics Image Process., vol. 29, pp. 377-393, 1985.

* Kittler最小错误分类法[3]：Kittler, J & Illingworth, J  (1986), "Minimum error thresholding", Pattern Recognition 19: 41-47

* ISODATA(也叫做intermeans法）[4]：Ridler, TW & Calvard, S (1978), "Picture thresholding using an iterative selection method", IEEE Transactions on Systems, Man and Cybernetics 8: 630-632, <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4310039>

* Yen法[5]：1) Yen J.C., Chang F.J., and Chang S. (1995) "A New Criterion  for Automatic Multilevel Thresholding" IEEE Trans. on Image  Processing, 4(3): 370-378 2) Sezgin M. and Sankur B. (2004) "Survey over Image Thresholding Techniques and Quantitative Performance Evaluation" Journal of  Electronic Imaging, 13(1): 146-165

* Garbor Based[6]：Tao X, Xu D, Zhang Z T, et al. ”Weak scratch detection and defect classification methods for a large-aperture optical element”. Optics Communications, 2017, 387: 390-400.
