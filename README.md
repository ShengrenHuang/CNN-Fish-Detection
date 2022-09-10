# Faster-RCNN-Fish-Detection

In this practice, we develop a fish detection algorithm via Detecto (python package based on PyTorch) by referring to [1]. In the field of object detection using a convolutional neural network (CNN), the R-CNN [2] is one of the most popular network architectures. Then, the scholars proposed  Fast R-CNN [3] and Faster R-CNN [4] chronologically. In this practice, we employ Faster R-CNN as the primary network architecture for fish object detection.  
We first utilize LabelImg to mark the area of interest in the fish images. Thus, we don't need to send the whole picture into the network (save the run time). With the help of Detecto, we adopt the pre-trained Faster R-CNN for transfer learning with the fish dataset [5]. The inference result shows that the prediction is correct.

![image](https://user-images.githubusercontent.com/108604868/188943075-989626b2-7245-42bf-a124-f07f117b1557.png)







# References  
[1] [Simplest custom object detection with Python | Deep Learning | Pytorch | Detecto | ResNet](https://www.youtube.com/watch?v=6FUcLHv6wpE&ab_channel=ArjunKashyap)  
[2] Ross Girshick, Jeff Donahue, Trevor Darrell, and Jitendra Malik, Rich feature hierarchies for accurate object detection and semantic segmentation, 2014.  
[3] Ross Girshick, Fast R-CNN, 2015.     
[4] Shaoqing Ren, Kaiming He, Ross Girshick, and Jian Sun, Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks, 2015.         
[5] [A Large Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset). 
