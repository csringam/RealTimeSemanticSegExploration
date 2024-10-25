# RealTimeSemanticSegExploration
## Motivation
Semantic segmentation on CCT images​ achieves adequate accuracy using DeepLab V3+​  
Looking for faster algorithm​  
Newer models have higher performance and accuracy​  

## Comparisons on Older Networks
### DeepLabV3+​
mIOU on Cityscapes: 87.8​  
Speed in PyTorch on RTX 3090: 131.58 FPS​  
Reference Paper: https://arxiv.org/pdf/1802.02611.pdf ​ 
### U-Net​
mIOU on Cityscapes: 65.9​  
Speed in PyTorch on NVidia Tesla K40C: 5.31 FPS​  
Reference Paper: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9847974&tag=1 ​ 

## New Models
What is the fastest available network?​  
Does this network sacrifice accuracy to achieve speed?​  
Is the network easily imported into MATLAB?​  
Are there any specific preprocessing that may hinder users?​​  

![rtssComp](https://github.com/user-attachments/assets/b18d9769-4a75-4f61-b8e5-dc82d898e94e)  

### Networks:  
![bisenet](https://github.com/user-attachments/assets/34ece045-42d2-479f-9e3a-c31e5907dee0)  
Reference Paper: https://arxiv.org/pdf/2004.02147.pdf  
![pidnet](https://github.com/user-attachments/assets/b7a1a5ac-421c-4e22-ae3c-fb7506331220)  
Reference Paper: https://arxiv.org/pdf/2206.02066v3.pdf  
![ddrnet](https://github.com/user-attachments/assets/29ff712b-3f90-4365-ae39-f6205cf1f85e)  
Reference Paper: https://arxiv.org/pdf/2101.06085v2.pdf ​ 
![icnet](https://github.com/user-attachments/assets/3bdced15-baa1-4fdd-8d41-d75cf003181f)  
Reference Paper: https://komodo.mathworks.com/main/gecko/attachments/g2351027/1704+Zhao+ICNet.08545.pdf  
