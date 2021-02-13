# Vehicle-Tracker-and-Counter

Tried to detect the number of car in a video.

1.Object detection without yolo use background substraction to detect blob from image and count a blob as an object if it crossed a certain line in the frame. If the object doesn't cross the line then it won't be counted.
![the-output-video](https://github.com/DimaMirana/Vehicle-Tracker-and-Counter/blob/main/withoutYOLO.gif)

2.To run the count-with-yolo.ipnyb file , need to download the yolov3.weights from yolo website. put that yolov3.weights file in 
yolo folder and then run the file. The object detection and tracking centeroid algorithhm is based on pyImageSearch website. I am using tutorial from https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/ to develop the implementation here.
![the-output-video](https://github.com/DimaMirana/Vehicle-Tracker-and-Counter/blob/main/withYOLO.gif)
