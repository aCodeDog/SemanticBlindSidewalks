# SemanticBlindSidewalks

envs:PaddlePaddle 2.4,Paddleseg,python 3.10.you can use test.ipynb to test this model.

## dataset
Dataset for two types of blindsidewalks detection, Because the data is too large to put in Github, please click the link to get [datasets](https://drive.google.com/file/d/14zy1uvRh8fiuFsWJrqBHrkOpFr9RUx9H/view?usp=share_link) and [pre-trained](https://drive.google.com/file/d/1SV09PFaX66nkxqTcUQptpphAhobZkVKy/view?usp=share_link)

Classes ["blind sidewalks","others"] 

The dataset contains annotations(mask),raw images,and visiualization.


## robots
 Unitree GO1 

## deploying device 

Jetson Orin Nx 16GB(INT8)

## inference_model

running on the PC(host). 

## output_quant_infer

running on the deploying device (INT8）. 
