# Image Segmentation for wound Database - Implementation using Keras segmentation Library using Mobilenet, UNET

Implementation of image segmentation using Keras segmentation library

Link to Keras segmentation library = https://github.com/divamgupta/image-segmentation-keras

# Image segmentation will be done on Control dataset and Illumination variant Dataset

Wound dataset = 200
Illumination dataset = 200

The dataset were augmented using <a href="https://github.com/mdbloice/Augmentor">Augmentor library</a> and <a href="https://github.com/aleju/imgaug">Imgaug library</a>.

The input image size = 224x224

Example of the Dataset :

Input Image            |  Output Segmentation Image
:-------------------------:|:-------------------------:
![]()  |  ![](output_segmentation/prediction1.png)
![](sample_images/3_input.jpg)  |  ![](sample_images/3_output.png)
