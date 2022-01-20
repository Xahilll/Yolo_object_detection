# Object detection using pre-trained deep learning models with OpenCV and Python 

OpenCV `dnn` module supports running inference on pre-trained deep learning models. 

When it comes to object detection,I have used popular detection framework
* YOLO
 ## Dependencies
  * opencv
  * numpy 
  * Streamlit   

 *You can find more details about the Dependencies in their respective official documentation.

`pip install numpy opencv-python streamlit`

> :warning: You need to have CUDA Toolkit which is provided by NVIDIA for running the following project.
you can download it from this [link](https://developer.nvidia.com/cuda-toolkit)
###  YOLO (You Only Look Once)
 
 Download the pre-trained YOLO v3 weights file (pre-trained deep learning model which uses learned features of deep convolutional neural network) from this [link](https://drive.google.com/file/d/1RsQnPpiOu9J9Ohl2iaVPoRyzzI3muJGm/view?usp=sharing) and place it in the current directory or you can directly download to the current directory in terminal using
 
 `$ wget https://drive.google.com/file/d/1RsQnPpiOu9J9Ohl2iaVPoRyzzI3muJGm/view?usp=sharing`
 
 You can view the more details regarding YOLO over this [link](https://github.com/ultralytics/yolov3)

 **For Initiating the "Streamlit" at LocalHost Use command:**

 `streamlit run yolo_opencv.py`

 The following window will be initialized at LocalHost in Browser
 
 **TIP: You can assess the local host either by Local URL or Network URL.**

![](homepage.jpeg)

> Image You are looking at the start of code is by default input named as dog.jpg

*Selection of the image input proceeds to result display on page itself with output images and tags of objects detected*

![](output.png)

>TIP: The directory of input image and weights file should be same.


**This is all about the project you also add your own updated version down here in repo.**
