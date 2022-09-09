# Faster-RCNN-Fish-Detection

在本練習中，參考[1] 我們目標利用CNN 與 pytorch 相關的 package Detecto 來實作一個fish detection 演算法，在CNN object detection 的範疇中，主要以 R-CNN 為廣為popular 的網路架構[2]，後續發展出Fast R-CNN[3]，與Faster R-CNN。在本練習中，我們主要利用Faster R-CNN來當作演算法實作上的網路架構。

我們首先利用 LabelImg 擷取dataset 中的目標物件的位置，如此不用將整張圖片送入CNN做運算(節省計算時間)，接著以 Python package Detecto，中pre-trained Faster R-CNN 架構 利用 Transfer Learning 套用在我的魚的dataset上。下圖為inference 的結果。結果正確辨識魚種。

In this practice, we develop a fish detection algorithm via Detecto (python package) by referring to [1]. In the field of object detection using a convolutional neural network (CNN), the R-CNN [2] is one of the most popular network architectures. Then, the scholars proposed  Faster R-CNN [3] and Faster R-CNN [4] chronologically. In this practice, we employ Faster R-CNN as the primary network architecture for fish object detection.  

![image](https://user-images.githubusercontent.com/108604868/188943075-989626b2-7245-42bf-a124-f07f117b1557.png)







# References  
[1] [Simplest custom object detection with Python | Deep Learning | Pytorch | Detecto | ResNet](https://www.youtube.com/watch?v=6FUcLHv6wpE&ab_channel=ArjunKashyap)  
[2] Rich feature hierarchies for accurate object detection and semantic segmentation  
[3] Fast R-CNN    
[4] Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks        
[5] [A Large Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset). 
