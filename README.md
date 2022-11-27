# Hysteroma Detection

Hysteroma Detection model based on PaddlePaddle.

[Paper_name](paper_links)

## Setup

```bash
git clone https://github.com/PaddlePaddle/PaddleDetection.git
cd PaddleDetection
pip install -r requirements.txt
python setup.py install
```

## Optimizing

### PP-YOLO

```bash
python tools/train.py -c configs/ppyolo/hysteroma_ppyolo.yml --eval
```

### YOLOv3

```bash
python tools/train.py -c configs/yolov3/hysteroma_yolov3.yml --eval
```

### SSD

```bash
python tools/train.py -c configs/ssd/hysteroma_ssd.yml --eval
```

### Faster RCNN

```bash
python tools/train.py -c configs/faster_rcnn/hysteroma_faster_rcnn.yml --eval
```