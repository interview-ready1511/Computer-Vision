# Computer Vision 
Reference: https://www.ibm.com/think/topics/computer-vision#691946467

## Q1. What is Computer Vision ?
Ans. Computer vision is a subfield of artificial intelligence (AI) that equips machines with the ability to process, analyze and interpret visual inputs such as images and videos. It uses machine learning to help computers and other systems derive meaningful information from visual data.
Computer vision can be pictured as the interaction between three broad processes, each working together and informing one another: recognition, reconstruction and reorganization.

## Q2. What are the common workflows of a Computer Vision task ?
Ans. There are multiple types of models and approaches for computer vision tasks, but the following hypothetical example illustrates a common workflow:

1.Data gathering
2.Preprocessing
3.Model selection
4.Model training

## Q3. Describe various tasks of COmputer Vision ?
Ans. Computer vision algorithms can be trained on a wide range of tasks, some of which include:

Image recognition
Image classification
Object detection
Image segmentation
Object tracking
Scene understanding
Facial recognition
Pose estimation
Optical character recognition
Image generation
Visual inspection

## Q4. What is Image Recognition?
Ans. Image recognition is the broadest form of computer vision. It encompasses the identification of people, places, objects and other entities in digital images and serves as the foundation for tasks like image classification, object detection and image segmentation.

## Q5. What is Image classification ?
Ans. Image classification is a core computer vision task that categorizes images into predefined groups or classes. It predicts the most fitting label for an image or objects within an image. The previously illustrated scenario of pneumonia diagnosis using chest X-rays is an example of image classification.

## Q6. What is  Object detection ?
Ans. Object detection aims to pinpoint where objects are in digital images. It melds two learning techniques: object localization and image classification.

Object localization identifies the location of specific objects in an image by drawing bounding boxes around them. Then, image classification distinguishes the category to which objects belong. In footage of road traffic, for example, computer vision apps can use object detection to not only classify vehicles but also locate them on the road.

## Q7. Explain the common CNN architecture for Object Detection ?
Ans. Common CNN architectures for object detection include R-CNN (region-based convolutional neural network) and YOLO (you only look once). R-CNN implements two-stage detection by first determining regions bearing objects then running those regions through separate networks for classification and more exact localization. Meanwhile, YOLO conducts single-stage detection by blending localization and classification in a single network pass, making it swift enough for real-time object detection.

## Q8. What is Image segmentation ?
Ans. Image segmentation is a more precise, pixel-level version of object detection. It partitions a digital image into discrete groups of pixels known as image segments, then labels pixels according to their class or instance.

While object detection can classify multiple elements within an image and approximate each element’s width and height, image segmentation discerns exact boundaries or shapes. This makes image segmentation valuable for delineating closely bunched objects with overlapping bounding boxes.

## Q9. Explain the Image Segmentation ?
Ans. Image segmentation can be further subdivided into three task types:

Semantic segmentation is the simplest type, assigning a semantic class—the specific category to which a given pixel might belong—to each pixel.
Instance segmentation predicts the exact pixel-wise boundaries of each individual object instance in an image.
Panoptic segmentation combines semantic and instance segmentation by determining the semantic classification of all pixels and differentiating each object instance in an image.

## Q10. 
