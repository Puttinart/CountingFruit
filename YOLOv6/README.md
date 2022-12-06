# YOLOv6
## Inference image
    !python tools/infer.py --weights runs/train/exp13/weights/best_ckpt.pt --source CountingFruit --yaml data/dataset.yaml
    
## Train model
    !python tools/train.py --batch 4 --conf configs/yolov6l_finetune.py --data data/dataset.yaml --device 0 --eval-interval 2
