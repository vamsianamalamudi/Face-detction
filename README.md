# Face-detction
Setup
>>> pip install dlib
#OUTPUT: Requirement already satisfied: dlib in /usr/local/lib/python3.6/dist-packages (19.16.0)


>>> pip install opencv-python
#OUTPUT: Requirement already satisfied: opencv-python in /usr/local/lib/python3.6/dist-packages (3.4.5.20)
         Requirement already satisfied: numpy>=1.11.3 in /usr/local/lib/python3.6/dist-packages (from opencv-python) (1.16.4)
         
>>> !pip install face_recognition
#OUTPUT: Collecting face_recognition
  Downloading https://files.pythonhosted.org/packages/3f/ed/ad9a28042f373d4633fc8b49109b623597d6f193d3bbbef7780a5ee8eef2/face_recognition-1.2.3-py2.py3-none-any.whl
Requirement already satisfied: Pillow in /usr/local/lib/python3.6/dist-packages (from face_recognition) (4.3.0)
Collecting face-recognition-models>=0.3.0 (from face_recognition)
  Downloading https://files.pythonhosted.org/packages/cf/3b/4fd8c534f6c0d1b80ce0973d01331525538045084c73c153ee6df20224cf/face_recognition_models-0.3.0.tar.gz (100.1MB)
     |████████████████████████████████| 100.2MB 1.4MB/s 
Requirement already satisfied: numpy in /usr/local/lib/python3.6/dist-packages (from face_recognition) (1.16.4)
Requirement already satisfied: Click>=6.0 in /usr/local/lib/python3.6/dist-packages (from face_recognition) (7.0)
Requirement already satisfied: dlib>=19.7 in /usr/local/lib/python3.6/dist-packages (from face_recognition) (19.16.0)
Requirement already satisfied: olefile in /usr/local/lib/python3.6/dist-packages (from Pillow->face_recognition) (0.46)
Building wheels for collected packages: face-recognition-models
  Building wheel for face-recognition-models (setup.py) ... done
  Created wheel for face-recognition-models: filename=face_recognition_models-0.3.0-py2.py3-none-any.whl size=100566174 sha256=dd03182b4dd485cce19fcac2aee14fef23074a39c82cab33c49a2b0d46e0bd1c
  Stored in directory: /root/.cache/pip/wheels/d2/99/18/59c6c8f01e39810415c0e63f5bede7d83dfb0ffc039865465f
Successfully built face-recognition-models
Installing collected packages: face-recognition-models, face-recognition
Successfully installed face-recognition-1.2.3 face-recognition-models-0.3.0
