# Keras-YoloV3-Video-and-Image-Object-detection-and-tracking
YoloV3 pretrained Video and Image Object detection in Keras

Observation: Yolov3 is faster(more FPS) then FasterRCNN/ResNet50 combo., however,

FasterRCNN detected more objects than YoloV3 on the same image and same confidence threshold levels.

On the enclosed image FasterRCNN detected 94 objects at 25% confidence, where as YoloV3 detected

69 objects at 20% confidence.

Both have some false/incorrect detection/labeling problem



![Intersection-Counts_det](https://user-images.githubusercontent.com/88380811/138731822-db1cfa26-cfba-46a0-8b87-c71df0f4f78d.PNG)
