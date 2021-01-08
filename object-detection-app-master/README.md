# Install

- Install python3
- Install PIP (https://pypi.org/project/pip/)
- install library opencv, pillow (OPENCV https://opencv.org/releases/) (Pillow https://pypi.org/project/Pillow/)

> pip install opencv-contrib-python

> pip install pillow

download [YOLOv3 weights](https://pjreddie.com/media/files/yolov3.weights), [Read More YOLOv3](https://pjreddie.com/darknet/yolo/)
atau dapat juga download melalui drive verikut
https://drive.google.com/drive/folders/1B1uII12fWj-OdEI6MPbUn04QbBQu7R2A?usp=sharing

put yolov3.weights to folder yolov3/yolov3.weights

# Run
> python3 TA2020.py

or

> python TA2020.py

or 

> ./run.sh

# Note 
Why i Choose YOLO as pre-trained model for this project ?, because that's the most accurate pre-trained model than other pre-trained. even though my laptop need 2 second to detect object on image, but maybe other machine could run this faster than that (based claim from developer YOLO that this framework could run 1000% faster on GPU)
