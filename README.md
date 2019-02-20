# RA_code

## 'Eye Tracking Data Recalibration and Visualization'  

02-19 8주차 활동 내역

1. Hidden Layer 추가 실험  
* ANN 레이어 및 노드 개수 실험  
1) 레이어 3개 노드 (20,20,20)
2) 레이어 4개 노드 (10,10,10,10)

2. 실제 데이터 확인  
* 실제 데이터 파이썬에 올려서 확인중 
* frame과 ATT를 맞춰야할듯

3. 영상 calibration 아이디어 생각중
* visual saliency? 사용? - Calibration-free gaze sensing using saliency maps(Yusuke Sugano at el)에서 영감을 얻음

![Alt text0](test saliency.png)


7주차 활동 내역  

1. ANN 구현 및 확인  
* ANN 레이어 및 노드 개수 실험  
1) 레이어 1개 노드 10, 20, 30개  
2) 레이어 2개 노드 (20, 10), (20, 20)  

![Alt text](architecture.png)  

* 다른 데이터에 적용할 때 어떠한 결과인지 확인  
* 다른 눈 데이터에 적용할 때 어떠한 결과인지 확인  

2. SVR 구현 및 확인  
* SVR 파라메터 튜닝  
* 다른 데이터에 적용할 떄 어떠한 결과인지 확인  
* 다른 눈 데이터에 적용할 때 어떠한 결과인지 확인  

3. Video 파이썬에 올리고 시각화  
* 만든 패러다임으로 아예 범용화 코드를 만드는 중  

* 패러다임 모습

[![Alt text1](https://img.youtube.com/vi/ROtto1Jh6Bk/0.jpg)](https://www.youtube.com/watch?v=ROtto1Jh6Bk)  

* 원본 데이터 시각화

[![Alt text2](https://img.youtube.com/vi/xrPvZJagrxA/0.jpg)](https://www.youtube.com/watch?v=xrPvZJagrxA)  

* 수정 후 데이터 시각화

[![Alt text3](https://img.youtube.com/vi/husFOFL9-ts/0.jpg)](https://www.youtube.com/watch?v=husFOFL9-ts)  

4. 영상 데이터 확인 및 시선이 집중될 만한 장면 찾기 
* 영상마다 시선이 집중될만한 장면 시간 체크 중..  
