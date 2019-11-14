# unet-denoising-dirty-documents
unet 实现文本文档去噪、去水印

# requirement
torch 1.2.0<br>
torchvision 0.4.0<br>
opencv-python 4.1.0.25<br>
numpy 1.16.2<br>

# usage
## 1. 准备数据集
下载链接：[denoising-dirty-documents数据集](https://pan.baidu.com/s/17chJLi_uDJovKR2zboFcvA)<br>提取码：cf7c<br>
![dir.jpg](images/dir.jpg)
## 2. 训练
```python train.py```<br>
数据增强在 transforms.py 包括灰度化、水平垂直翻转、旋转、裁剪、直方图均衡化、均值滤波、Log灰度变换
## 3. 预测
```python predict.py```<br>
## 4. 预训练模型
下载链接：[预训练模型1.5M](https://pan.baidu.com/s/1L3v-xehLBk-G6kbb55vGnA)<br>
提取码：poyf<br>

# test_images
![test_001.jpg](images/test_001.jpg)
![test_002.jpg](images/test_002.jpg)
![test_003.jpg](images/test_003.jpg)
![test_004.jpg](images/test_004.jpg)

# reference
[眼底图像血管分割 retina-unet](https://github.com/orobix/retina-unet)