# YOLO-Object-Dectection
Object detection using YOLO Algorithm

## STEPS TO RUN:
1. Make sure all the needed softwares - Python 3, openCV , numpy etc are installed.
2. Clone the repository.<br>
    Folder content : <br>
    a. yolo-coco -- Yolo COCO pretrained model <br>
    b. yolo.py -- For detection in images <br>
    c. yolo_video.py -- For detection in videos <br>
    d. yolo_live.py -- For live detection using webcam <br>
3. Download pretrained YOLO model trained with COCO dataset from <a href="https://drive.google.com/drive/folders/1cqKb1leT_eUwYnMeGIR_ixlmEAyHG67p?usp=sharing">here</a>.

## Commands to be used to run the code(assuming default values for a few other arguments)
### For detection in image:<br>
```python yolo.py -i imageName.jpeg -y yolo-coco```
### For detection in video:<br>
```python yolo_video.py -i videoName.mp4 -y yolo-coco``` 
### For live detection:<br>
```python yolo_video.py -y yolo-coco``` 



## Explanation of the arguments:
#### Required arguments
<b>-i</b><br>  Denotes the source image/video path<br>
<b>-y</b><br>  To provide the path to Yolo COCO model

#### Optional arguments
<b>-c</b>
<br>Minimum value to discard weak detection
<br>Default value : 0.5
<br>
<b>-t</b>
<br>Threshold value for non max suppression 
<br>Default value : 0.3


