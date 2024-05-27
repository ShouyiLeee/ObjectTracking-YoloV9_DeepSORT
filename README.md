# Object Tracking with YOLOv9 and DeepSORT
- This project implements real-time object tracking using the YOLOv9 object detection model and the DeepSORT tracking algorithm.

## Dependencies
- Python 3.6+
- PyTorch
- OpenCV
- DeepSORT (https://github.com/nwojke/deep_sort)


## Usage
- Download a YOLOv9 model:
- You can find pre-trained YOLOv9 models online. Make sure to download a model with the appropriate class labels for your desired application.



## For detection only:

### Bash
- > python detect_dual.py --weights <path/to/yolov9.pt> 


## For detection and tracking:

### Bash
- > python track_dual.py --weights <path/to/yolov9.pt>

- Replace <path/to/yolov9.pt> with the actual path to your downloaded YOLOv9 model.

## Additional Notes:
- The track_dual.py script allows for customization of various parameters like confidence threshold, maximum distance for re-identification, and minimum IoU (Intersection over Union) for tracking. You can modify these parameters within the script.
- The class names used by the YOLOv9 model need to be defined in the script. You can find the class names corresponding to your model in the downloaded files or documentation.
- This project is for educational purposes and might require adjustments for specific applications.
## References
- YOLOv9: https://github.com/WongKinYiu/yolov9
- DeepSORT: https://github.com/nwojke/deep_sort
- Real-Time Object Tracking with YOLOv9 and DeepSORT Algorithm
