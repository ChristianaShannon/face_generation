# face_generation

#### 项目来源： UDAcity 深度学习 P5 项目 ####

- 项目介绍：
  1. 使用tensorflow，构建一个生成式对抗网络（Generative Adversarial Nets）来生成新的人脸图像
  2. 利用项目提供的 CelebA数据集，完成人脸图像的生成
- 项目环境：
  - conda 3 --Jupyter Notebook
  - Python3.6.2
  - Tensorflow 1.4
  
### 1. 文件组成 ###

    dlnd_face_generation.ipynb 为代码实施，依赖于Tensorflow
	
  	problem_unittests.py 和helper.py 为辅助assert代码


### 2. 环境要求 ###
   本项目依赖于以下python数据库：

    
    * tensorflow 1.4 深度学习框架
       
   
	ipynb文件运行环境：

    * Anaconda3 Python3.6
    
       
### 项目运行 ###
    
    GPU K80运行， CelebA数据集一个epoch 约需要15min，minst小于2min
    
### 项目优化 ###
  
  模型参数可进一步优化，使得人脸生成图像更清晰.
