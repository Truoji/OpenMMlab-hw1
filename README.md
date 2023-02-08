# OpenMMlab-hw1
openmmlab AI训练营作业


OpenMMlabCamp：

homework2:

1. 将数据集整理为COCO格式

2. 选`mask_rcnn_r50_fpn_2x_coco_bbox_mAP-0.392__segm_mAP-0.354_20200505_003907-3e542a40.py`构建训练集，改变类别数量和名称，降低学习率
3. 训练默认24轮，得到模型文件

```json
2023-02-08 18:40:34,411 - mmdet - INFO - Evaluating segm...
2023-02-08 18:40:34,434 - mmdet - INFO - 
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.793
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=1000 ] = 0.895
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=1000 ] = 0.882
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = 0.404
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.678
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.856
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.838
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=300 ] = 0.838
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=1000 ] = 0.838
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=1000 ] = 0.400
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=1000 ] = 0.758
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=1000 ] = 0.889

2023-02-08 18:40:34,435 - mmdet - INFO - Exp name: mask_rcnn_r50_fpn_2x_ballon.py
2023-02-08 18:40:34,435 - mmdet - INFO - Epoch(val) [24][13]	bbox_mAP: 0.7717, bbox_mAP_50: 0.8955, bbox_mAP_75: 0.8955, bbox_mAP_s: 0.4545, bbox_mAP_m: 0.6993, bbox_mAP_l: 0.8255, bbox_mAP_copypaste: 0.7717 0.8955 0.8955 0.4545 0.6993 0.8255, segm_mAP: 0.7928, segm_mAP_50: 0.8955, segm_mAP_75: 0.8824, segm_mAP_s: 0.4040, segm_mAP_m: 0.6783, segm_mAP_l: 0.8557, segm_mAP_copypaste: 0.7928 0.8955 0.8824 0.4040 0.6783 0.8557

```

4. Color splash特效制作

<video src="homewok2_basic\hw2.mp4"></video>

## 模型文件

链接：https://pan.baidu.com/s/1fxb6oQP9EnsatqLl5uJo2A?pwd=cqsm 
提取码：cqsm
