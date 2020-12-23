# Face_Rec
v0.1

基于CSDN用户“就是这个七昂”的项目稍作调整：https://blog.csdn.net/qq_42633819/article/details/81191308

由于新版本的语法问题，整个项目基于以下老版本运行：  
Tensorflow - 1.2.1  
Python - 3.5.4  
OpenCV - 3.3.1  
numpy - 1.13.1  
pillow - 4.2.1  
Keras - 2.0.8  
scikit-learn - 0.19.0

使用该项目前请先于项目根目录创建文件夹data

Python文件功能介绍：  
face_rec：调用笔记本摄像头拍摄照片作为训练集数据，拍摄张数和暂存路径在文件尾的CatchPICFromVideo函数修改。拍摄好的训练集图片建议按人名建文件夹分类，放置data目录下 
load_data：预处理data目录下的分类后的图片为正方形，并打上标记（代码78行）  
face_train：调用TF训练  
Face_recognition：调用摄像头进行人脸识别

该项目仅实现二分类
