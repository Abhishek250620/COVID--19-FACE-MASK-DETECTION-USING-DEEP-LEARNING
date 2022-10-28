In this pandemic government urges people to wear masks. If at all it is mandatory, 
some people are not properly wearing masks. This model is helpful to detect the people who are 
not wearing it properly, The corona virus COVID-19 pandemic is causing a global health crisis 
so the effective protection method is wearing a mask in public areas according to World Health 
Organization (WHO).Wearing a protective face mask has become a new normal. In the future, 
many public service providers will ask the customers to wear masks currently to avail of their 
services. Therefore, face mask detection has become a crucial task to help global society. The 
COVID-19 pandemic forced governments across the World to impose lockdown to prevent 
virus transmission. Reports indicate that wearing face masks while at work clearly reduces the 
risk of transmission. An efficient and economic approach of using AI to create a safe 
environment in manufacture setup. A face mask detection data set consist of people images 
mask and without mask images, OpenCV is used in real-time face detection from a live stream 
via our webcam. We will use the data set to build a COVID-19 face mask detector with 
computer vision using Python, OpenCV, and TensorFlow and Keras. Our goal is to identify 
whether the person on image/video stream is wearing a mask 

steps to run the project

1) open command promt(cmd)and go to project directory
Note: first you have to check what is the name of your project directory
$cd facemask-detection

2) Install dependencies:
pip install -r requirements.txt

3) Open terminal. Go into the cloned project directory and type the following command:
 python train_mask_detector.py --dataset dataset

4)  To detect face masks in an image type the following command:

 python detect_mask_image.py --image images/pic1.jpeg

5)To detect face masks in real-time video streams type the following command:
python detect_mask_video.py

frameworks we used

All the dependencies and required libraries are
tensorflow>=2.5.0*
keras==2.4.3
imutils==0.5.4
numpy==1.19.5
opencv-python>=4.2.0.32
matplotlib==3.4.1
argparse==1.4.0
scipy==1.6.2
scikit-learn==0.24.1
pillow>=8.3.2
streamlit==0.79.0
onnx==1.10.1
tf2onnx==1.9.3

Developer's = Abhishek M R, Harshitha, Sagar N C, Saniya bhanu
Guide- Mrs. Komala K V , Asst professor GEC Ramanagar