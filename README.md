# Single-Image-Deraining

## Problem Statement  
![image](https://user-images.githubusercontent.com/32372013/236968134-5bd36b36-420f-45ae-8bc2-bb3935843e04.png)

## Overall Approach  

- U-Net: This is the baseline model without any modifications (see *UNet_Rain100L.ipynb*).  

- U-Net + Local Attention: This model incorporates local attention in the U-Net architecture (see *Attention_Rain100L.ipynb*).  

- U-Net + Residual Connections: This model uses residual connections within the U-Net architecture (see *Residual_Rain100.ipynb*).  

- U-Net + Local Attention + Residual Connections: This model combines both local attention and residual connections (see *Attention_Residual_Rain100L.ipynb*).  

![image](https://user-images.githubusercontent.com/32372013/236968210-352e62c1-f5d3-4ef3-976b-4288079b28fb.png)

## Results  
![image](https://user-images.githubusercontent.com/32372013/236968249-a8e19c64-2f78-4a36-8f83-a02478a09b07.png)  

- The *"Results - Derained 200 epochs"* folder contains all derained test image results produced by each model. 

## Findings/Discussion  
![image](https://user-images.githubusercontent.com/32372013/236968285-60c2fd85-257e-4d2e-9797-bfb0420302a3.png)



