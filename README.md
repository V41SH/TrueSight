# TrueSight
A YOLOv3 based object detection + voice feedback model.


## Steps to run:
1. The code was run on Windows 10 and the python version used is 3.8.5
2. Download dependencies; OpenCV, os, numpy and gtts (using pip)
3. An internet connection is required for gtts to function
4. Download the yolov3 weights from the link: https://pjreddie.com/media/files/yolov3.weights
5. yolov3 is a pre trained model, these weights are a result of training on the MS-COCO dataset: https://cocodataset.org/#download
5. Place the weights folder in the same directory as the Python file
6. Run the following command: `python trueSight_yolo.py`

- The processed image will then be displayed in its own window, it will also be saved in the directory as object-detection.jpg
- Once this window is closed, the generated mp3 file will begin playing.
- One can analyze their own images by saving it in the `images` folder and altering the file path in line 21 of the python file.