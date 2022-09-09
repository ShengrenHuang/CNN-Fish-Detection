# Faster-RCNN-Fish-Detection

在本練習中，參考[1] 我們目標利用CNN 與 pytorch 相關的 package Detecto 來實作一個fish detection 演算法，

我們首先利用 LabelImg 擷取dataset 中的目標物件的位置，如此不用將整張圖片送入CNN做運算(節省計算時間)，接著以 Python package Detecto，中pre-trained Faster R-CNN 架構 利用 Transfer Learning 套用在我的魚的dataset上。

![image](https://user-images.githubusercontent.com/108604868/188943075-989626b2-7245-42bf-a124-f07f117b1557.png)







# References  
[1] [Simplest custom object detection with Python | Deep Learning | Pytorch | Detecto | ResNet](https://www.youtube.com/watch?v=6FUcLHv6wpE&ab_channel=ArjunKashyap)  
[2] Rich feature hierarchies for accurate object detection and semantic segmentation  
[3] Fast R-CNN    
[4] Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks        
[5] [A Large Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset). 
