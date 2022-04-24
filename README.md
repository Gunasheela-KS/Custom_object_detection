# Custom_object_detection

The code in this repository implements custom object detection on image/videos using yolo v5.

Experiment:
250 epochs completed in 1.019 hours.
Optimizer stripped from runs/train/exp2/weights/last.pt, 14.4MB
Optimizer stripped from runs/train/exp2/weights/best.pt, 14.4MB

Validating runs/train/exp2/weights/best.pt...
Fusing layers... 
Model summary: 213 layers, 7018216 parameters, 0 gradients, 15.8 GFLOPs
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:00<00:00, 10.58it/s]
                 all          5          5      0.987      0.846      0.995      0.857
                elon          5          2          1      0.539      0.995      0.752
              barack          5          1      0.967          1      0.995      0.995
                mark          5          2      0.993          1      0.995      0.824
