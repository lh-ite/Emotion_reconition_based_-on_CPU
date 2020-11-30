INSTALL
程序名称：Emotion_Recognition
Anaconda3
需要安装的包
Python 3.6.8
tensorflow-cpu    2.3.1
Keras                              2.4.3   
numpy                              1.18.5
scikit-learn                       0.23.1
matplotlib                         3.2.2
pandas                             1.0.5
opencv-python                      4.4.0.44
Pillow                             7.2.0

实现步骤：
1. 将FER2013数据集（fer2013.csv）下载到Emotion_Recognition\fer2013文件夹中。该文件夹中的fer2013_clean2.csv为我在fer2013数据集的基础上处理的数据集，可直接用来训练，具体处理方式见论文。FER2013数据集可在参考程序链接中找到。
2. load_and_process.py中可设置要训练的数据集。
3. 运行train_emotion_classifier.py进行模型训练，并生成混淆矩阵。训练完的模型储存在models文件夹下。

