○ Subject: 산삼인식 드론

○ Dataset : `Google Crawling`

○ Project Schedule : 23.9.12 ~ 23.10.6(약 3주)

<br>

### <b>Yolo와 U_net을 기반으로 한 산삼탐지드론 프로젝트</b>

<br><br>

## 1. Collaborator
- 팀장 : 김가은
- 팀원 : 김동신 | 남소민 | 이정호

<br><br>

## 2. Tech
- Skills
  <br><br>
  `Object Dectection`,`Segmentation`,`EDA`,`Augmentation`,`Crawling`
<br>

- Tool
  <br><br>
  `Visual Studio`,`Google Colab`,`RoboFlow`,`notion`,`git-hub`
<br><br>

## 3. Project Management (23.10.31~23.11.21(약 4주))
### 프로젝트 개발 방식
 
  - #### `AI Model`

    `Python`의 `Yolo`와 `U_net`을 메인으로 산삼 탐지.
    
    <br>


## 4. 프로젝트 상세 내용
<div align='center'>

  
  |팀원 소개|
  |---|
  |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/7b8fd5cf-870f-4a73-914a-7e4e9143a8f6)|
  
  |기획|
  |---|
  |<div align='center'>`선정배경`</div>|
  |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/5b81bfce-c3dc-4f19-b069-a9bde2c50f40)|
  |<div align='center'>`구현도`</div>|
  |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/1e2477b4-c8d6-4096-a789-b609cff39067)|
  <br>
  
  |AI Model|
  |---|
  |<div align='center'>`YOLOV4`</div>|
  |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/f1f7a7b9-1761-4122-af11-b5d0ac152e20)|
   |<div align='center'>`YOLOV5`</div>|
   |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/c3143bc2-e893-4b8e-b7d3-677bd8d86ab7)|
   |<div align='center'>`YOLOV7`</div>|
   |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/4ae6bbca-ac61-4f81-8c05-900356b2f80d)|
   |<div align='center'>`U_net`</div>|
   |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/2d7cb562-5a08-4cef-97f6-f35a321adb31)|
  <br>
  
  |수행절차 & Flow Chart|
  |---|
  |<div align='center'>`수행절차`</div>|
  |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/1edddeb6-2a40-42a2-a47d-deb85d55106d)|
  |<div align='center'>`Flow Chart`</div>|
  |![image](https://github.com/KimDong-gue/Ginseng_dectection/assets/116249934/1aaa5dd9-934e-4f0e-bb70-eab8025aebce)|
  <br>

  |아쉬운 점 / 개선 사항|
  |---|
  |<div align='center'>아쉬운 점</div>|
  |-높은 `mAP`에 비해 `dectection` 성능의 아쉬움
   -`DeepLab V3+` 적용을 못 해본점
   -`Model Handling`의 어려움|
  |<div align='center'>개선 사항 & 참고 객원<div>|
  |-데이터 개선: `Resized`, `Crawling`을 통한 데이터 증강, 증강처리(Filp,Cut-out,Mosaic,Cut-Mix,Bringht)
  -성능 개선: 모델 아키텍처 수정, 학습률(learning rate) 조절 `Callbacks` 활용, 전이학습
  -농업회사법인 한국산삼주식회사 대표 전병무님, 산삼농원 '비학농원' 운영자 장재기님|
  <br>
  
</div>
