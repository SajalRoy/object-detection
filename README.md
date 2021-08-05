Object Detection using PyTorch

Detect COCO objects in images and realtime videos


Install all the library:
 pip install -r requirements.txt


Usage for image:
python3 detect_image.py --model frcnn-resnet --image images/example_01.jpg --labels coco_classes.pickle

Usage for real-time video:
python3 detect_realtime.py --model frcnn-resnet --labels coco_classes.pickle

