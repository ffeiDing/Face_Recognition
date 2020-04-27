# Face Recognition 

***Pytorch implementation of Softmax, Sphereface, CosFace and Arcface***

------------

- Deep Learning Platform:  PyTorch 1.4.0
- Language:  Python 3.7.3

------------

-  Database:  `WebFace`  (You should first complete the data preprocessing section by following these steps https://github.com/wy1iu/sphereface#part-1-preprocessing)

- Network: `LResnet50E-IR`

------------

### Result with batchsize of 256 with 30 epochs

Loss  |  Hyper-parameter  |  Accuracy on LFW
------------- | -------------  |  -------------
Softmax  | -  |  
Sphereface  | m=4  |  
Cosface  | s=30, m=0.4  |  99.00%
Arcface | s=30, m=0.5  |  
