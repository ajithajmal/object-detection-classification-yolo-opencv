# object-detection-classification-yolo-opencv


#download yolo
wget https://pjreddie.com/media/files/yolov3.weights
wget https://pjreddie.com/media/files/yolov3-tiny.weights


 # Run the  Commands
If you want to perform object detection in a static image file,
```
python3 yolo.py --image=True --image_path='images/bicycle.jpg'
```

If you want to perform object detection in a video,
```
python3 yolo.py --play_video=True --video_path='videos/car_on_road.mp4'
```

If you want to start the webcam and perform real-time object detection,
```
python3 yolo.py --webcam=True

