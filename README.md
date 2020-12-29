# PP_YOLO_train

实现功能
-------

* 实现Pytorch版PP_YOLO的目标检测
* 进行网络结构的搭建
* 对自己数据集锚框的聚类
* 对网络模型的训练和预训练

测试运行的环境
------------

* Windows10
* Python3.7
* Pytorch1.3
* CUDA10.0

training:
---------

1.用labelimg标注自己的数据集为VOC格式

2.用kmeans_for_anchors.py进行聚类获取数据的锚框

3.在使用voc2yolo3.py将数据集分为训练集和测试集

4.用voc_annotation.py得到数据的位置和信息

5.接下来就可以用trains.py进行训练了，不过要将代码中的路径改为自己的路径，并且将我的绝对路径改为你自己的绝对路径，把上面得到的锚框和得到的标签信息加入进去，就可以进行训练了

test:
-----


链接：https://pan.baidu.com/s/1Hm0awb9exJVbM39dQj7MxQ 

提取码：yolo 
