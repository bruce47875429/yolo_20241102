# YOLOv7 License Plate Experiments

YOLOv7 training and inference notebooks, a Taiwan license plate dataset,
sample images, and saved experiment results.

## Sources

- YOLOv7: https://github.com/WongKinYiu/yolov7 (see yolov7/LICENSE.md).
- Dataset: https://universe.roboflow.com/project-a2ia8/taiwan-license-plate-recognition (CC BY 4.0).
- The notebooks adapt existing examples; the upstream model is not original work.

## Files

- `Step2_demo_yolo_v7(1).ipynb`: Colab training and detection workflow.
- `3_yolo_inference.ipynb`: image inference.
- `yolov7/`: upstream code and experiment results.
- `Taiwan_License_Plate_Recognition.v1i.yolov7pytorch/`: dataset and attribution.

Large model weights are stored using Git LFS. After cloning, run `git lfs pull`.
The notebooks use `/content/drive/MyDrive/yolo_20241102` as their Colab workspace.
