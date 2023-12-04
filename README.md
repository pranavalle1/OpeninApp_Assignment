# OpeninApp_Assignment
 AI model capable of enhancing the quality of a video by upscaling its resolution and reducing noise.
In this project, we have used a pretrained Super-Resolution Generative Adversarial Networks(SRGAN) model to perform Video enhancement using Single Image Super Resolution. The model takes a low resolution video as input and provides a high resolution video as output. The model has been validated in different genres videos at different quality levels. It is done in 6 simple steps which includes conversion of input video into low resolution frames and then converting back the processed high resolution frames into the output video.
## STEP-1
Clone the following repository which consists of Pretrained SRGAN Model in your Notebook:-

``` !git clone https://github.com/krasserm/super-resolution ```

## STEP-2
Create a directory named Super Resolution by using the command given below :-

```cd /content/super-resolution```
## STEP-3
The pretrained weights required for running the model can be  downloaded from the link given below:-

[weights-srgan.tar.gz]

After downloading the pretrained weights, upload it in your notebook and then run the command below to extract the weights into the root folder-
```!tar xvfz /content/weights-srgan.tar.gz```
## STEP-4
To perform video enhancement,the input video should be converted into frames and the model can be used to obtain super resolved frames.This can be done using python codes given below.
