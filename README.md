# YOLOv3-tiny-custom
## Mask Detection Model
- YOLOv3-tiny.cfg 파일을 수정해서 마스크 착용 여부를 인식하는 custom 모델을 생성

## 모델 정의 (cfg 파일 수정)
> 1. 기준 모델: width & height = 416 / subdivisions = 36  
> 2. 이미지 크기 상향 모델: width & height = 736 / subdivisions = 36 
> 3. subdivisions 값 하향 모델: width & height = 416 / subdivisions = 4 

<img src="https://github.com/CAUCV/YOLOv3-tiny-custom/blob/main/result.PNG?raw=true" width="800px">
- [Mask detection 학습 결과](https://drive.google.com/drive/folders/1WIMAW8P3mh8zlINm_OFZR-xNFQpx-uM6?usp=sharing)
