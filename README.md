# TACO-Trash-Detection-YOLOv5

![result demo](https://github.com/e96031413/TACO-Trash-Detection-YOLOv5/blob/main/test.jpg)


AI Module Course Term Project, detect trash with YOLOv5 on TACO dataset

please put taco.yaml inside yolov5/data/

Training set, val set, test set split is 60:20:20

training batch size is 16

## Training result
```
YOLOv5s, pre-trained weight: yolov5s.pt, 300 epochs, batch size = 64, img size = 640
Class   Images  Targets    P    R    mAP@.5  mAP@.5:.95: 100%|██████████| 10/10 [00:10<00:00,  1.06s/it]
 all     297       576   0.11  0.17  0.124    0.0959
```
