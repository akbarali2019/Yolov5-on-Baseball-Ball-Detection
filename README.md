# Yolov5-on-Baseball-Ball-Detection
Yolov5 on Baseball Ball Detection



training command: python train.py --img 640 --batch 16 --epochs 3 --data coco128.yaml --weights yolov5s.pt

testing command: python detect.py --weights yolov5s.pt --img 832 --source data/images --augment

resume for crash: python train.py --img 640 --batch 16 --epochs 3 --data coco128.yaml --resume ./last.pt
# https://drive.google.com/drive/folders/14D6tRe8m_L_UvE1ASaT8LXp1Z6zrM3q0?usp=sharing
