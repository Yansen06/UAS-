# Install

- Install python3
- Install PIP (https://pypi.org/project/pip/)
- install library opencv, pillow (OPENCV https://opencv.org/releases/) (Pillow https://pypi.org/project/Pillow/)

> pip install opencv-contrib-python

> pip install pillow

download [YOLOv3 weights](https://pjreddie.com/media/files/yolov3.weights), [Read More YOLOv3](https://pjreddie.com/darknet/yolo/)
or you can download from google Drive
https://drive.google.com/drive/folders/1B1uII12fWj-OdEI6MPbUn04QbBQu7R2A?usp=sharing

put yolov3.weights to folder yolov3/yolov3.weights

# Run
> python3 TA2020.py

or

> python TA2020.py

or 

> ./run.sh

# Note 
Mengapa saya Memilih YOLO sebagai pre-trained untuk proyek ini?, Karena itulah pre-trained yang paling akurat daripada model terlatih lainnya. Meskipun laptop saya membutuhkan 2 detik untuk mendeteksi objek pada gambar, tetapi mungkin mesin lain dapat menjalankan ini lebih cepat dari itu (berdasarkan klaim dari pengembang YOLO bahwa kerangka kerja ini dapat berjalan 1000% lebih cepat pada GPU)
