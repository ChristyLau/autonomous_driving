# test detect and train
先搭建好运行环境，python>=3.7, pytorch>=1.8，以及其他运行需要的包，具体见requirement.txt文件

## detect
1. 在新环境下直接运行detect.py
2. 在runs/detect下查看检测结果

## train
1. 下载coco128数据集（https://github.com/ultralytics/yolov5/releases/download/v1.0/coco128.zip） ，并解压
2. 修改data/coco128.yaml文件的第11行，改成数据集刚刚下载解压后的路径
3. 运行train.py
4. 在runs/train下查看训练结果
