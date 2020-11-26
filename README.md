# FaceMaskDetector-PythonAndOpenCV

## Table of content
1. [Face Mask Detector Demo Video](https://www.youtube.com/watch?v=0mpYdT4xCQ4)
2. [License](https://github.com/Inzimam-Tariq/FaceMaskDetector-PythonAndOpenCV/blob/main/LICENSE)
3. [System and version used](#system-and-versions-used)
4. [Requirements](https://github.com/Inzimam-Tariq/FaceMaskDetector-PythonAndOpenCV/blob/main/requirements.txt)
5. [How to build](#how-to-build-on-your-system)
6. [Multi-face mask detection proof](#multiple-face-mask-detection-proof)

## Demo Video
<div align="center">
      <a href="https://www.youtube.com/watch?v=0mpYdT4xCQ4">
     <img 
      src="https://github.com/Inzimam-Tariq/FaceMaskDetector-PythonAndOpenCV/blob/main/images/face%20mask%20detection%20application%20in%20python%20with%20opencv%20preview%20img.PNG" 
      alt="Face Mask Detector App in Python using OpenCV" 
      style="width:100%;">
      </a>
    </div>
    <br>

## System and versions used
I used 
- windows 10 OS
- Python 3.7 (because tensorflow is not currently available for Python 3.9)
- Architecture is 64-bit (Windows, Python, OpenCV)
- For versions of dependencies you can read [requirements.txt](https://github.com/Inzimam-Tariq/FaceMaskDetector-PythonAndOpenCV/blob/main/requirements.txt)

## How to build on your system
1. Clone the repo or Download and extract
2. Open project in any code editor (you can also open the cmd in the folder where you clone or extract code)
3. Run "pip install -r requirements.txt" command without qoute (it will install all the dependencies)
4. Open train_mask_detector.py file and change the path of dataset i.e. on my system its "D:\Web\FaceMaskDetector-PythonAndOpenCV\dataset"
5. If everything goes normal you can proceed to step 7
6. OpenCV may not be istalled properly if so, download and install OpenCv
[Here is a good documentation](https://pysource.com/2019/03/15/how-to-install-python-3-and-opencv-4-on-windows)
7. run "python train_mask_detector.py" to train your model. (It will take quite a long time.)
8. run the "detect_mask_video.py" to open camera and see the app working. (It will take quite a long time.)

That's it :smile:.

## Multiple face mask detection proof
![Multi-face mask detection](https://github.com/Inzimam-Tariq/FaceMaskDetector-PythonAndOpenCV/blob/main/images/multiple%20face%20mask%20detection.png)

