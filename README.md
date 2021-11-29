# YOLO_Series
YOLOv3, YOLOv4, YOLOv5, YOLOX的PyTorch实现。（持续更新中......）

# 使用方法(Installation)
首先你需要确保安装PyTorch 1.10.0及以上版本，torchvision 0.11.1及以上版本；
然后运行pip install requirements.txt安装依赖项。如果有必要的话，
修改experiments文件夹下的配置文件，最后运行项目根目录下的train_xxx.py文件就可以开始训练了，
测试单张图片的结果可以运行test_xxx.py，跑一段视频可以运行video_xxx.py。

# 运行结果(Results)
1. YoloV3 on VOC<br>
![测试图片1.jpg](https://github.com/calmisential/YOLO_Series/blob/main/assets/yolov3_voc_sample1.jpg?raw=True)
![测试图片2.jpg](https://github.com/calmisential/YOLO_Series/blob/main/assets/yolov3_voc_sample2.jpg?raw=true)
![测试图片3.jpg](https://github.com/calmisential/YOLO_Series/blob/main/assets/yolov3_voc_sample3.jpg?raw=true)
![测试图片4.jpg](https://github.com/calmisential/YOLO_Series/blob/main/assets/yolov3_voc_sample4.jpg?raw=true)
# TODO list
1. 训练和测试代码
- [x] Yolo_v3
- [x] Yolo_v4
- [ ] Yolo_v5
- [ ] Yolo_x
- [ ] CenterNet
2. 发布在COCO数据集上训练好的模型
- [ ] Yolo_v3
- [ ] Yolo_v4
- [ ] Yolo_v5
- [ ] Yolo_x
- [ ] CenterNet

# References
- https://github.com/hunglc007/tensorflow-yolov4-tflite
- https://github.com/amdegroot/ssd.pytorch code for processing COCO dataset
- https://github.com/ultralytics/yolov5
- https://github.com/calmisential/YOLOv4_PyTorch
- https://github.com/calmisential/CenterNet_TensorFlow2
