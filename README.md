# Realtime_FacialRecognition
Real time Facial Recognition using the face_recognition module and ip cameras.


[![License](https://img.shields.io/github/license/KiLJ4EdeN/Realtime_FacialRecognition)](https://img.shields.io/github/license/KiLJ4EdeN/Realtime_FacialRecognition) [![Version](https://img.shields.io/github/v/tag/KiLJ4EdeN/Realtime_FacialRecognition)](https://img.shields.io/github/v/tag/KiLJ4EdeN/Realtime_FacialRecognition) [![Code size](https://img.shields.io/github/languages/code-size/KiLJ4EdeN/Realtime_FacialRecognition)](https://img.shields.io/github/languages/code-size/KiLJ4EdeN/Realtime_FacialRecognition) [![Repo size](https://img.shields.io/github/repo-size/KiLJ4EdeN/Realtime_FacialRecognition)](https://img.shields.io/github/repo-size/KiLJ4EdeN/Realtime_FacialRecognition) [![Issue open](https://img.shields.io/github/issues/KiLJ4EdeN/Realtime_FacialRecognition)](https://img.shields.io/github/issues/KiLJ4EdeN/Realtime_FacialRecognition)
![Issue closed](https://img.shields.io/github/issues-closed/KiLJ4EdeN/Realtime_FacialRecognition)
Prerequisites:

1 - Python

2 - OpenCV

3 - Sklearn

4 - PIL (pillow)

5 - numpy


How to Use:

1 - Clone the repo.

2 - Install the required libraries.

3 - Find your camera ip and change it in the code, in a rare case when opencv can't crack open your ip camera url, use specific my repo for acquiring images from ip cams using urrlib at https://github.com/KiLJ4EdeN/IPCAM_urllib.

4 - To add training examples of your own, Go to knn_examples/train,
each folder name represents a person and inside that folder will be images related to that person for the knn  to be trained.

5 - Run facerec_ipcamera_knn.py.

6 - Use q to quit the stream anytime.
