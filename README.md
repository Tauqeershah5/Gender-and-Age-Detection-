Gender and Age Detection with OpenCV & Deep Learning

This project is a Python-based application that detects human faces in images or webcam input and predicts their **gender** and **age range** using pre-trained deep learning models. It uses OpenCV's `dnn` module to process and display results in real time.

---

Features

- Detects human faces using a pre-trained OpenCV face detection model
- Predicts gender: **Male** or **Female**
- Predicts age range: **(0-2), (4-6), (8-12), (15-20), (25-32), (38-43), (48-53), (60-100)**
- Works on images or webcam input
- Displays results visually and prints to the console

---

#Models Used

- Face Detection: `opencv_face_detector.pb`, `opencv_face_detector.pbtxt`
- Age Prediction: `age_net.caffemodel`, `age_deploy.prototxt`
- Gender Prediction: `gender_net.caffemodel`, `gender_deploy.prototxt`

---Requirements

Install the dependencies using pip:

```bash
pip install opencv-python opencv-contrib-python
