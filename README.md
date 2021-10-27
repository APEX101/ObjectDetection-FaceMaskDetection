
# FaceMaskDetector- YOLOv3, Darknet, OpenCV , Transfer Learning
![](demo.gif)

## 📝 Overview
Trained the YOLOv3 model on custom facemask detection kaggle dataset using Darknet on GoogleColab.The model predicts three
classes  mask on , no mask , mask worn incorrectly with great accuracy and stable fps.Finally
finalized the model using OpenCV and Cuda.The model is designed for real time detection but also can
detect on images and videos.


## 🧰 Technical Aspects

- Trained on GoogleColab.
- Collected the image data and preprocessed it in Yolov3 format.
- Trained Yolov3 model using Darknet with TransferLearning pretrained Weights (darknet53.conv.74).
- After testing the accuracy depoloyed the model using OpenCV and Cuda for realtime boundingbox
  creation with confidence level of detection.
- Tested on realTime Webcam feed as well as on Videos and images.

## ⏳ DataSet
https://www.kaggle.com/andrewmvd/face-mask-detection

## 🔥 TransferLearningWeights

https://github.com/AlexeyAB/darknet

## 💡TrainedWeights
https://drive.google.com/file/d/1-3QX6x2phhM_yyBV2m3A7CoUttBC5P1p/view?usp=sharing

## 🖥️ Installation
### 🛠️ Requirement

* Yolov3
* Darknet
* Numpy
* OpenCV and CUDA.



    
## ⚙️ Tech Stack
<p float="left">
<img src="https://camo.githubusercontent.com/6b3c6c1109586f5f3ddf8967fa4eaf787c7b45fe3df6d89111d6f9c7c1045769/687474703a2f2f706a7265646469652e636f6d2f6d656469612f66696c65732f6461726b6e65742d626c61636b2d736d616c6c2e706e67" width="20%" >
<img src="https://pjreddie.com/media/image/yologo_2.png" width="30%" >
<img src="https://pyimagesearch.com/wp-content/uploads/2016/07/install_opencv_cuda_logos.jpg" width="40%" >
<img src="https://www.kindpng.com/picc/m/713-7136289_rougier-numpy-logo-name-below-02-python-numpy.png" width="20%" >
<img src="https://miro.medium.com/max/986/1*pimj8lXWwZnqLs2xVCV2Aw.png" width="70%" >

</p>


