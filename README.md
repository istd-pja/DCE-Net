#  DCE-Net: A Differential Contrast-Enhanced Network for Infrared Small Target Detection

This is the code for "DCE-Net: A Differential Contrast-Enhanced Network for Infrared Small Target Detection"


# 1. Data preparation

This experiment includes multiple public datasets, which are introduced below one by one. When trainning, you may consider extending the testing interval or reducing the number of test images to avoid affecting the progress, .

## 1.1 "NUDT"

* dataset: https://github.com/YeRen123455/Infrared-Small-Target-Detection

* paper doi: 10.1109/TIP.2022.3199107

* description: NUDT-SIRST dataset is a synthesized dataset, which contains 1327 images with resolution of 256x256.

* path format
  
  images: "your root path/train_imgs/xxx.png", "your root path/test_imgs/xxx.png", where "xxx" will be automatically retrieved in the code.

  labels: "your root path/train_labels/xxx.png", "your root path/test_labels/xxx.png", where "xxx" will be automatically retrieved in the code.

## 1.2 "IRSTD-1K"

* dataset: https://github.com/RuiZhang97/ISNet

* paper doi: 10.1109/CVPR52688.2022.00095

* description: IRSTD-1k dataset is the realistic infrared small target detection dataset, which consists of 1,001 manually labeled realistic images with various target shapes, different target sizes, and rich clutter back-grounds from diverse scenes.

* path format
  
  images: "your root path/train_imgs/xxx.png", "your root path/test_imgs/xxx.png", where "xxx" will be automatically retrieved in the code.

  labels: "your root path/train_labels/xxx.png", "your root path/test_labels/xxx.png", where "xxx" will be automatically retrieved in the code.
  
 
