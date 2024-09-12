# ObjectDetection-YOLOv3
YOLOv3 (You Only Look Once, version 3) is a real-time deep learning model for object detection. It divides an image into a grid, predicting bounding boxes and class labels for objects within each cell. Using Non-Maximum Suppression (NMS), it removes duplicate detections to output labelled boxes with confidence scores.
* Input Image: The model takes an input image and divides it into a grid of cells.
* Grid Cell Predictions: Each grid cell predicts bounding boxes (with height, width, and center coordinates) and class probabilities for potential objects within that cell.
* Bounding Boxes: Predicted bounding boxes are refined to accurately fit around detected objects using anchor boxes.
* Non-Maximum Suppression (NMS): To avoid multiple detections of the same object, YOLOv3 applies NMS, selecting the best bounding box with the highest confidence score.
* Output: The model outputs the final bounding boxes with class labels and confidence scores for each detected object.

# Procedure

1. Install the libraries
2. Run `python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt`
3. Labelled output will be rendered
4. Image will be saved as `object-detection.jpg`

# Screenshot
<p align = 'Center'>
<img src= 'https://github.com/user-attachments/assets/5275566b-bdaa-41f5-a447-9d0b64cf7c5b'>
</p>
