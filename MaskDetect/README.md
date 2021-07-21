# Mask Detect

1. 이미지 혹은 비디오의 프레임을 `CaffeModel`을 이용하여 얼굴을 인식
2. 마스크를 착용하였는지 Detect하기 위해 학습된 model 파일을 이용하여 mobilenet_v2로 Mask or Nomask인지를 Detect

![](https://github.com/yannJu/Study__DeepLearning/blob/master/MaskDetect/img/Screenshot%20from%202021-07-21%2016-47-11.png)

-> Load Img

![](https://github.com/yannJu/Study__DeepLearning/blob/master/MaskDetect/img/Screenshot%20from%202021-07-21%2016-48-55.png)

-> Face Detect(use dnn.readNet)

![](https://github.com/yannJu/Study__DeepLearning/blob/master/MaskDetect/img/Screenshot%20from%202021-07-21%2016-48-59.png)

-> Detect Mask

---

1. [Mask Detect Practice](https://github.com/yannJu/Study__DeepLearning/blob/master/MaskDetect/detectMask_Project_Practice.ipynb) : 유튜브를 참고하여 작성해봄

    참고유튜브 : [마스크 썼는지 안썼는지 알아내는 인공지능](https://youtu.be/ncIyy1doSJ8)
