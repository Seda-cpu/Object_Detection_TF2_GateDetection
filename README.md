# Object_Detection_TF2_GateDetection
İts the first task of TeknoFest 2021 autonomous underwater vehicles category which is a technology competition in Turkey. 


**Dataset**

Our vehicle can detects a custom object in underwater. I created my own dataset by taking pictures of our custom gate. I use 25 images for training and 9 images for test. I labelled the images by using LabelImg. 

LabelImg: https://github.com/tzutalin/labelImg.git

I upload my dataset to kaggle you can see here https://www.kaggle.com/sedanurkrc/underwater-gate-dataset

Here is some pictures of the dataset

![data_gate](https://user-images.githubusercontent.com/74606830/141806272-1e217f08-af50-46d0-b5f0-113c226aabf9.png)

**Training**

I use ssd_mobilenet_v2 pretrainede models weights. And in 2000 epochs it gets 0.18 loss.
![tensorboard](https://user-images.githubusercontent.com/74606830/141807141-10932f1b-80df-41c6-8c31-31efa67a636c.jpg)


**Test**

![WhatsApp Image 2021-11-15 at 18 01 56](https://user-images.githubusercontent.com/74606830/141807217-12d684ef-3294-4638-8f84-a6c6a9f06e93.jpeg)

