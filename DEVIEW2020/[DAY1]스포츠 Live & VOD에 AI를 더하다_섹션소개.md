## 스포츠 Live & VOD에 AI를 더하다!!!
###### #ML/AI #Computer Vision

스포츠 팬들의 경우 생중계를 보면서 종목별로 발생하는 이벤트 즉, 야구라면 홈런이나 득점, 축구라면 골장면 등을 실시간으로 보고 싶은 needs가 있습니다. 또한, 생중계 이벤트를 보지 못한 스포츠 팬들의 경우 응원하는 팀의 이벤트를 수동 편집으로 인한 오랜 기다림 없이 경기 종료 후 수 분 이내에 원하는 득점 영상을 보고 싶은 needs도 상당히 많다고 생각됩니다. 이러한 스포츠 팬들의 needs를 만족시키기 위해 스포츠 Live 및 VOD 영상에 딥러닝 기술을 적용하였습니다.

본 세션에서는 스포츠 Live 및 VOD 영상에 적용된 딥러닝 기술을 자세하게 소개해 드리고자 합니다. 또한 적용된 딥러닝 기술을 활용하여 오픈한 서비스는 어떠한 것들이 있는지도 알려드립니다. 추가적으로 서비스를 오픈하면서 발생한 이슈들을 해결하기 위해 수없이 고민했던 이슈 troubleshooting에 대해서도 공유하고자 합니다.

<br>

**목차**

1. 스포츠 Live&VOD 목표
- 사용자 가치 전달
- 신속한 전달
<br>
2. 적용 서비스
- KBO(국내 프로야구)
- 축구(해외축구&K리그2)
- 골프 & 생중계 광고 썸네일 제거
- 언론 보도 현황
<br>
3. 시스템 아키텍처
- 생중계 타임머신내 득점 위치 자동 표시
- 경기 풀영상 타석별 보기
<br>
4. 관련 기반기술
- Computer Vision
- Action Recognition
- Scene Classification
- Live Text Synchronization
-  Real-Time Analysis
<br>
5. 이슈 트러블슈팅
- Pitch Motion 오인식
- Object Detection 모델 변경
- 스코어 자동인식 추가
- 긴급 상황을 위한 Contingency Plan
<br>
6. 향후 리서치 공유
- Player : Panoptic Segmentation & Player Tracking
- Action : Pose Estimation & Action Prediction

<br>

**강연 대상**

- 네이버 스포츠 영상을 어떤 과정으로 분석하고 이용하는지 궁금하신 분들

- 네이버 스포츠 데이터를 활용하여 딥러닝 기술과 접목하여 서비스에 어떻게 적용되었는지 궁금하신 분들

- 네이버 스포츠 KBO와 해외축구, 골프 영상을 분석하면서 재미있게 시청하고자 하시는 분들