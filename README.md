학습시킨 파일의 데이터와 ppt는 용량 문제로 업로드 실패

아이디어 : 횡단보도를 건너는 교통약자의 특징을 인식 후 신호등 시간 조정

과정 :
1. 학습시킬 사진 또는 데이터셋을 train.yolov9 파일을 통해 학습
2. 학습된 yolov9을 OpenVino로 변환 convert.yolov9 사용
3.  YOLOv9 Inferencing.pdf에서 동영상 인식
4.  파이썬 코드를 이용해 객체를 인식했을 때 신호등 시간 조정
