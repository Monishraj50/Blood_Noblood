# Blood_Noblood Detection
Detecting the faces with Blood and faces without Blood.
## Dataset
Download the dataset from the below link

>[Download dataset](https://drive.google.com/file/d/1tcdLZymFiw36lzu95zgCAQzudi0Wxma5/view?usp=sharing)

The folders are as follows: <br/>
1. Blood : Faces contaning blood <br/>
2. NoBlood : Faces not containing blood <br/>
3. Faces: Contains cropped images of faces <br/>
## Working with Dataset

 | -train <br/>
 > |--train_blood <br/>
 > |--train_noblood <br/>
 
 | -val <br/>
 > |--val_blood <br/>
 > |--val_noblood <br/>
 
## Detecting the Corrupted Images
Image files can get corrupted when downloaded or imported from cameras and mobile devices. When an image is corrupted, we will not able to open that image.Recontruction
If one of your image files is damaged, you can no longer open it. With a little luck, however, the JPG can be repaired.

## Preview of Dataset
## Faces with Blood
|<img src=https://github.com/Monishraj50/Blood_Noblood/blob/master/img/blood_1.jpg width='250' height='250' /> |
<img src=https://github.com/Monishraj50/Blood_Noblood/blob/master/img/blood_100.jpg width='250' height='250' />|
## Faces without blood
|<img src=https://github.com/Monishraj50/Blood_Noblood/blob/master/img/noblood_10.jpg width='250' height='250' />|
<img src=https://github.com/Monishraj50/Blood_Noblood/blob/master/img/noblood_102.jpg width='250' height='250' />|

## Training
Here we are using a  pre-trained model or desired portion of the model can be integrated directly into a new neural network model. In this usage, the weights of the pre-trained can be frozen so that they are not updated as the new model is trained. Alternately, the weights may be updated during the training of the new model, perhaps with a lower learning rate, allowing the pre-trained model to act like a weight initialization scheme when training the new model.

We are using a The InceptionV3 is the third iteration of the inception architecture, first developed for the GoogLeNet model.
This model was developed by researchers at Google and described in the 2015 paper titled [Rethinking the Inception Architecture for Computer Vision.](https://arxiv.org/abs/1512.00567)

Training Accuracy and Validation Accuracy Curve 
<img src=https://github.com/Monishraj50/Blood_Noblood/blob/master/img/acc.png width='350' height='350' />




