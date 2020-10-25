# ObjectTracking-DeepSORT-YOLOv3-TF2
This repository implements YOLOv3 and Deep SORT in order to perfrom real-time object tracking. 

## Installation

First, clone or download this GitHub repository. Install requirements and download pretrained weights:

```
https://github.com/anushkadhiman/ObjectTracking-DeepSORT-YOLOv3-TF2.git
cd ObjectTracking-DeepSORT-YOLOv3-TF2
````

```
pip install -r ./requirements.txt
`````

```
# yolov3
wget -P model_data https://pjreddie.com/media/files/yolov3.weights

# yolov3-tiny
wget -P model_data https://pjreddie.com/media/files/yolov3-tiny.weights
``````


## Tracking

```
python object_tracker.py
````

## Result

### Tracking Person by Pre-trained model
![Alt text](tracking.gif?raw=true "video")

## References
Deep SORT Repository - https://github.com/nwojke/deep_sort






