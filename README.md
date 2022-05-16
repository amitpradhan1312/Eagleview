# Eagleview
In this project we will train the YOLOv4 network on 2 classes 'Car' , 'Person' with the given image dataset
YOLO can view an image and draw bounding over what it perceives as identified classes. We apply a single neural network to the full image. This network divedes the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities. For more information about this algorithm, please, click here.
YOLO belongs to the family of One-Stage Detectors. In a sliding window + classification approach, you look at the image and classify it for every window.Compared to YOLOv3, YOLOv4 has improved again in terms of accuracy (average precision) and speed (FPS), the two metrics we generally use to qualify an object detection algorithm as shown in the below graph: image And the best part of the YOLOv4 model is that model training can be done on a single GPU. Given below is the architecture of the model:
Tweaking images size can also attain good accuracy
Training it for more than 1000 epochs might also help in achieving good model
