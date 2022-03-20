# Object Detection for Parcel Shape Estimation and Analysis
# Description
In this study, we look at the idea of assisting parcel processing by automating the 2D detection of parcels. Deep learning models such as Faster R-CNN, YOLOv5 and RetinaNet have been used to derive features of the parcel and to recognize all the occurrences of an object category. 

A Convolutional Neural Network method is applied here for the environment to assign importance to various aspects in the image after taking in an input image. To set up our programming environment to be ready to run object detection training and inference commands, Detectron 2 and YOLOv5 dependencies are installed in different Google Collaboratory files. We used R101-FPN as a baseline for Faster RNN R50-FPN for RetinaNet.

# Dataset
The Cardboard boxes dataset was extract from an online source: https://medium.com/@ringlayer/cardboard-box-detection-using-retinanet-keras-5d4f331d9d15, and https://www.kaggle.com/datasets/sakshi12345/cardboard-box-images-with-annotations-for-yolov5and is preprocess via Roboflow.


# Reference

Antonius, F., 2019. Cardboard box detection using retinanet(keras). [Online]. Available at: https://medium.com/@ringlayer/cardboard-box-detection-using-retinanet-keras-5d4f331d9d15 [Accessed 4 July 2019]

Roboflow: give your software the power to see objects in images and video. [Online]. Available at: https://roboflow.com/

Sakshi,2018. Cardboard box images with annotations for yolov5. [Online]. Available at: https://www.kaggle.com/datasets/sakshi12345/cardboard-box-images-with-annotations-for-yolov5
