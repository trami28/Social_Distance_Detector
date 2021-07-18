# **Social Distance Detector**
*This project has been done for the GRIP(Gradual Rotational Internship Program) conducted by the Spasrk Foundation under the task Computer Vision and IOT (for #July2021 Batch)*

The objective of the project is to detect whether social distancing protocol is properly followed in public places. It can then be implemented to monitor social distancing protocol in real time via CCTV surveillance.

The project can be divided into three sub systems
1. Object dectection 
2. Object Tracking
3. Distance measurement between detected objects

### YOLO object detection (You Only Look Once) 
It uses Convolutional Neural Networks for Object Detection. YOLO can detect multiple objects on a single image. It means that apart from predicting classes of the objects, YOLO also detects locations of these objects on the image. YOLO applies a single Neural Network to the whole image. This Neural Network divides image into regions and produces probabilities for every region. After that YOLO predicts number of Bounding  Boxes that cover some regions on the image and chooses the best ones according to the probabilities.
*The detailed tutorial can be found here*
https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/
