# Real Time Face Mask Detection
This repository is a task of classifying whether a person is wearing a mask or not in real time

![Mask](https://github.com/Hongyanlee0614/Face-Mask-Detection/blob/master/mask.PNG)
![No Mask](https://github.com/Hongyanlee0614/Face-Mask-Detection/blob/master/no_mask.PNG)
![Plot](https://github.com/Hongyanlee0614/Face-Mask-Detection/blob/master/plot.png)

## ✨ Features

- Real time face mask detection
- Bounding box drawn around face detected (Red color if no mask detected, green color if mask detected)
- Confidence probability according to the output (mask or no mask)

## 🚀 Getting Started and Run the Code

1. **Clone this repository**

Go to your desired directory,

```
git clone https://github.com/Hongyanlee0614/Face-Mask-Detection.git
```

2. **Create a virtual environment for this project**

Run ```pip install virtualenv``` if your computer does not have this module. This module is to enable us to create a virtual environment for installing packages only specific to this task.

Go to the desired directory,

```
cd Face-Mask-Detection-master
virtualenv facemaskdetection
```

3. **Activate your virtual environment**

```
cd facemaskdetection
cd Scripts
activate
```

Go back to the project directory

```
cd ..
cd ..
```

4. **Install libraries and packages necessary for this project**

```
pip install -r requirements.txt
```

5. **Train the model**

```
python train_mask_detector.py
```

A classification report will be shown in the output
![result]()

6. **Real time face mask detection**

```
python detect_mask_video.py
```

## 🌟 Credit and Appreciation
  - Balaji Srinivasan's [Youtube Tutorial](https://www.youtube.com/watch?v=Ax6P93r32KU) 
