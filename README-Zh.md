# FaceRecognition
一个基于MTCNN和Tensorflow的简单人脸识别程序  
[README-En.md](/README.md)

## 用法:
1. 建立开发环境
2. 在此处下载预训练模型：链接：https：//pan.baidu.com/s/1skGsxbf密码：6666  
   然后将这些文件放到models文件夹中
3. 
```Bash
python main.py
```

## Demos:
![Demo1](https://github.com/lmgy/FaceRecognition/blob/master/demos/pic1.jpg)
![Demo2](https://github.com/lmgy/FaceRecognition/blob/master/demos/pic2.jpg)

## 开发环境:
1. Windows 10 64bit
2. Python (3.5.4) 64bit
3. numpy (1.13.3)
4. opencv-python (3.3.1)
5. six (1.11.0)
6. tensorflow-gpu (1.1.0rc0)
7. CUDA (8.0) 64bit
8. cuDNN (5.1) 64bit
    
## 关于我使用的模型的信息：
更多关于models: https://arxiv.org/abs/1602.07261  
更多关于MTCNN: https://kpzhang93.github.io/MTCNN_face_detection_alignment/  