# 우회전 차량을 위한 보조 신호 시스템

YOLOv7
- [YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors](https://arxiv.org/abs/2207.02696)
- Github, https://github.com/WongKinYiu/yolov7

SORT
- [Simple Online and Realtime Tracking](https://arxiv.org/abs/1602.00763)
- Github, https://github.com/abewley/sort
- Additional Reference github, https://github.com/haroonshakeel/yolov7-object-tracking

ZoeDepth
- [ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth](https://arxiv.org/abs/2302.12288)
- Github, https://github.com/isl-org/ZoeDepth

BSUV-Net
- [BSUV-Net: A Fully-Convolutional Neural Network for Background Subtraction of Unseen Videos](https://arxiv.org/abs/1907.11371)
- Github, https://github.com/ozantezcan/BSUV-Net-inference

## Usage

Colab - Colab_inference.ipynb **Only for Video Inference**

Desktop - Desktop_inference.ipynb

## Desktop Preparation

Installation the requirements.txt
- `pip install -r requirmenets.txt`
- if needed, set the path by `cd /path/`

BSUV-Net
- Download the trained models and the hrnet_v2 model files from the github.
- Place the trained models in `trained_models` folder and the hrner_v2 model files in `utils/segmentation/hrnet_v2` folder.
