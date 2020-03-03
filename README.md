# Image Segmentation for wound Database - Implementation using Keras segmentation Library using Mobilenet, UNET

Implementation of image segmentation using Keras segmentation library

Link to Keras segmentation library = https://github.com/divamgupta/image-segmentation-keras

# Image segmentation will be done on Control dataset and Illumination variant Dataset

Control wound dataset = 200
Illumination wound dataset = 200

The dataset were augmented using <a href="https://github.com/mdbloice/Augmentor">Augmentor library</a> and <a href="https://github.com/aleju/imgaug">Imgaug library</a> for illumination and other augment.

The input image size were set to = 224x224

Example of the Dataset :

Controlled Image            |  Illumination Image
:-------------------------:|:-------------------------:
![](Comparison/compare2.png)  |  ![](Comparison/compare2_1.png)
![](Comparison/compare3.png)  |  ![](Comparison/compare3_1.png)
![](Comparison/compare4.png)  |  ![](Comparison/compare4_1.png)
![](Comparison/compare5.png)  |  ![](Comparison/compare5_1.png)
![](Comparison/compare6.png)  |  ![](Comparison/compare6_1.png)
![](Comparison/compare7.png)  |  ![](Comparison/compare7_1.png)
