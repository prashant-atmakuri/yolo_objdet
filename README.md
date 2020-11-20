# yolo_objdet

Object Detection Using YOLO pre-trained model
Download the files 1.yolov3.weights 2.yolov3.cfg 3. coco.names 4. Images to test
Weight file: it’s the trained model, the core of the algorythm to detect the objects.
Cfg file: it’s the configuration file, where there are all the settings of the algorythm.
Name files: contains the name of the objects that the algorythm can detect.

Blob it’s used to extract feature from the image and to resize them. YOLO accepts three sizes:

320×320 it’s small so less accuracy but better speed
609×609 it’s bigger so high accuracy and slow speed
416×416 it’s in the middle and you get a bit of both.
