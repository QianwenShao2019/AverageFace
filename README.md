# README

## Data (demo)

>./female_demo/
>
>./male_demo/
>
>./shape_predictor_68_face_landmarks.dat/shape_predictor_68_face_landmarks.dat

## Detect landmarks

> Detect 68 landmarks from picture using 0_face_landmark_detection.py
>
> Result_files:
>
> './female_demo/*.jpg.txt/'
>
> './male_demo/*.jpg.txt/'

```cmd
python 0_face_landmark_detection.py ./shape_predictor_68_face_landmarks.dat/shape_predictor_68_face_landmarks.dat ./female_demo # python 3.6.7
```

```cmd
python 0_face_landmark_detection.py ./shape_predictor_68_face_landmarks.dat/shape_predictor_68_face_landmarks.dat ./male_demo # python 3.6.7
```

## Face average

> Using 1_faceAverage.py
>
> Result_files:
>
> './female_demo_result_faceAverage*'
>
> './male_demo_result_faceAverage*'

```cmd
python 1_faceAverage.py # python 2.7
```

## Reference

> https://www.learnopencv.com/average-face-opencv-c-python-tutorial/
>
> http://dlib.net/face_landmark_detection.py.html
