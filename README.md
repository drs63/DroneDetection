
# Drone Detection.

## YoloV3

Training YoloV3 model.


```bash
python train.py --data ./data/drone.yaml --cfg yolov3.yaml --weights '' --batch-size 128
```

Inference of YoloV3 model.
```bash
python path/to/detect.py --weights yolov3.pt --source 0              # webcam
                                                       img.jpg        # image
                                                       vid.mp4        # video
                                                       path/          # directory
                                                       path/*.jpg     # glob
                                                       'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                                                       'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```

## YoloV4

Training YoloV4 model.


```bash
python train.py --data ./data/drone.yaml --cfg yolov4.yaml --weights '' --batch-size 128
```

Inference of YoloV4 model.
```bash
python path/to/detect.py --weights yolov4.pt --source 0              # webcam
                                                       img.jpg        # image
                                                       vid.mp4        # video
                                                       path/          # directory
                                                       path/*.jpg     # glob
                                                       'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                                                       'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```

## YoloV5

Training YoloV5 model.


```bash
python train.py --data ./data/drone.yaml --cfg yolov5.yaml --weights '' --batch-size 128
```

Inference of YoloV3 model.
```bash
python path/to/detect.py --weights yolov5s.pt --source 0              # webcam
                                                       img.jpg        # image
                                                       vid.mp4        # video
                                                       path/          # directory
                                                       path/*.jpg     # glob
                                                       'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                                                       'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```

