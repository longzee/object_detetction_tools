
## darknet2caffe
Steps:

First,you should install this repo https://github.com/marvis/pytorch-caffe-darknet-convert;

Note:this repo need install pytorch and caffe.

Second,you should install upsample_layer into caffe, please check this [link](https://github.com/BVLC/caffe/pull/6384/commits/4d2400e7ae692b25f034f02ff8e8cd3621725f5c).

Finally,download yolov3.weights and run yolov3_darknet2caffe.py this file.

1) download yolov3.weights 

    `$ wget https://pjreddie.com/media/files/yolov3.weights`

2) run yolov3_darknet2caffe.py this file in this folder (/home/xx/pytorch-caffe-darknet-convert/).

    `$ python yolov3_darknet2caffe.py yolov3.cfg yolov3.weights yolov3.prototxt yolov3.caffemodel`
