# -Object-Detection-Classifier-YOLO-V3
Build an Object Detection Classifier with TensorFlow that will be able to run detections on both images and video in real-time

### Downloading official pretrained weights
For Windows:
You can download the yolov3 weights by clicking [here](https://pjreddie.com/media/files/yolov3.weights) and adding them to the weights folder.

## Running the model
You can run the model using `detect.py` script. The script works on images, video or your webcam. Don't forget to set the IoU (Intersection over Union) and confidence thresholds.

### Usage
```
python detect.py <images/video/webcam> <iou threshold> <confidence threshold> <filenames>
```
### Images example
Let's run an example using sample images.
```
python detect.py images 0.5 0.5 data/images/dog.jpg data/images/office.jpg
```
Then you can find the detections in the `detections` folder.
