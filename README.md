<H1 align="center">
People Detection and Tracking in Video using YOLOv8 and DeepSORT with Left to Right Counting"  </H1>


## Steps to run Code
- Create a new conda environment with Python 3.8 and activate this environment
```
conda create -n yolov8 python=3.8
conda activate yolov8
```
- Clone the repository
```
git clone https://github.com/oguzcanbekar/YOLOv8-DeepSORT-Object-Tracking.git
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Object-Tracking
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```

- For yolov8 object detection + Tracking + Vehicle Counting

```
python predict.py model=yolov8l.pt source="PETS09-S2L2-raw.mp4" show=True
```

### RESULTS

- The result video is saved to /runs/detect/train/




