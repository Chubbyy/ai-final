# Adverse Weather Object Detection for Autonomous Vehicles
*Tentative plan*

Autonomous vehicles rely on computer vision to identify objects such as cars, pedestrians, and
other obstacles on the road. However, adverse weather conditions such as rain, fog, and snow can
reduce visibility and make object detection less reliable.

This project aims to create a weather-aware object detection system using Convolutional Neural
Networks (CNNs). We will investigate how different weather conditions affect detection accuracy
and whether image augmentation can improve model performance.

We will use a small subset of the BDD100K autonomous driving dataset, which contains road
images captured under different weather conditions. We will focus primarily on clear and rainy
images, with simulated fog where needed.

We will use TensorFlow with a pretrained CNN-based object detection model, such as SSD
MobileNet V2. Transfer learning will allow us to adapt the model without training it from scratch.
We will measure precision, recall, and mean Average Precision (mAP), and visualize predicted
bounding boxes to compare detection performance.

We expect to develop a working CNN-based object detection prototype capable of identifying
vehicles and pedestrians in different weather conditions. The project will demonstrate the effects
of adverse weather on object detection and evaluate whether weather-based data augmentation
improves detection accuracy.