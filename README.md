# road-works
Road works detection using yolov5 model
There is no open source dataset on road works traffic sign board and hence I created my own dataset from collecting images of around 1000 from online sources and the internet.
Annotations to the images are done in yolo format using labelImg and divided the dataset into a train set of 930 and validation set of 102 images with its labels.

For training, I trained the model on yolov5 model for 50 epochs as the data is limited to 1k only and got precision and recall of approximately 0.9
