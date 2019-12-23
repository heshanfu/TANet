# TANet

Code will be released! (Before the conference of AAAI-2020)

# Introduce
In  this  paper,  we  focus  on  exploring  the  robustness  of  the3D object detection in point clouds, which has been rarelydiscussed  in  existing  approaches.  We  observe  two  crucialphenomena:  1)  the  detection  accuracy  of  the  hard  objects,e.g., Pedestrians, is unsatisfactory, 2) when adding additionalnoise  points,  the  performance  of  existing  approaches  de-creases rapidly. To alleviate these problems, a novel TANet isintroduced in this paper, which mainly contains a Triple At-tention (TA) module, and a Coarse-to-Fine Regression (CFR)module.  By  considering  the  channel-wise,  point-wise  andvoxel-wise attention jointly, the TA module enhances the cru-cial  information  of  the  target  while  suppresses  the  unsta-ble cloud points. Besides, the novel stacked TA further ex-ploits the multi-level feature attention. In addition, the CFRmodule boosts the accuracy of localization without excessivecomputation cost. Experimental results on the validation setof KITTI dataset demonstrate that, in the challenging noisycases, i.e., adding additional random noisy points around eachobject, the presented approach goes far beyond state-of-the-art approaches. Furthermore, for the 3D object detection taskof the KITTI benchmark, our approach ranks the first place onPedestrian class, by using the point clouds as the only input.The running speed is around 29 frames per second.

The network architecture of TANet: 
![image](imgs/TANet.png)

The detail architecture of Triple attention: 
![image](imgs/TA_Module.png)

The detail architecture of Coarse-To-Fine Regression: 
![image](imgs/Coarse-To-Fine.png)


For more information please consult the [Paper](https://arxiv.org/pdf/1912.05163.pdf)
