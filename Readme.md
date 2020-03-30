<img width="871" alt="MI2RL_logo" src="https://user-images.githubusercontent.com/55417425/77146652-e4a44700-6ace-11ea-9e69-3d38b3f35392.png">
<br>

# 내용 업데이트중

# Safety devices with 3D printing
* 해당 프로젝트는 코로나19(SARS-CoV-2)를 극복하기위해 서울아산병원 MI2RL 연구실에서 진행하고 있습니다.
* 코로나19(SARS-CoV-2) 팬데믹으로 의료진에게 필요한 의료장비가 심각한 고갈에 시달리고 있고, 사회적 거리두기를 실현하기 위해 마스크, 손소독제 그 이상의 something new 를 개발하고, 보급하는 것을 목적으로 합니다.
* 업로드 된 STL 파일은 3D modeling program 인 3-matics (Materialise) 와 Solidworks s/w를 이용하여 제작되거나 수정되었습니다.
* 필요하신 분들은 링크 된 STL 파일을 마음대로 다운받으셔서 출력하셔도 됩니다
* 그 밖의 문의사항 등은 dyhong.89@gmail.com 으로 연락주시기 바랍니다.

# Medical device reverse engineering
* 코로나19를 극복할 수 있는 다양한 아이디어를 3D 프린팅 기술로 실현할 수 있습니다.
* 임상에서 충족되지 못한 다양한 needs를 받아, 필요한 medical device를 제작 할 수 있습니다.
* CT 혹은 3D 스캐너 등을 통해 3D 영상을 얻고 동일한 형상의 파트 혹은 맞춤형 파트를 제작하여 적합한 물성의 3D 프린팅 재료로 출력합니다.


# 관련 기사 링크
  * http://www.ddaily.co.kr/news/article/?no=193388
  * https://www.3dprintingmedia.network/covid-19-3d-printed-valve-for-reanimation-device/
  * https://n.news.naver.com/article/079/0003337612?lfrom=facebook&fbclid=IwAR1js5SM82ElAQBNUQR367zVMiWv7pU1yacDihFWC1HrOnLwkd0WZHZ15oc
  * https://www.cnet.co.kr/view/?no=20200322231554
  * http://www.hellot.net/new_hellot/magazine/magazine_read.html?code=201&sub=004&idx=51228
  * http://www.hkn24.com/news/articleView.html?idxno=310340

## 1. safety mask (haman-specific)

   * 이 장치는 다양한 사이즈의 마스크를 제작하고, 개인 맞춤형 마스크를 공급하기위해 개발되었습니다.
   * 개인의 3D scan 영상을 획득하여, 얼굴 형상에 맞게 조정되어 적용할 수 있으며, AMC_MI2RL 의 자체모델링으로 개발되었습니다.
   * FDM 프린터의 TPU 재료로 flexible 하게 출력하기를 권장드립니다.
   * STL 링크 (준비중)
              
### 1. version 1
![image](https://user-images.githubusercontent.com/62414626/77871868-6723c800-7280-11ea-8e5c-c9951e9a5ac6.png)

              
   
## 2. Door handle v1

   * 이 장치는 닫힌 문을 열 때, 접촉 오염을 줄이고자 개발되었으며 손을 사용하지않고 문을 개폐할 수 있도록 제안되었습니다.
   * 관련 동영상링크 ()
   * 이 장치는 STRATASYS 사의 모델링을 참고하여 개발되었으며, FDM 프린터의 PLA, ABS 등 견고한 아크릴 소재로 출력하기를 권장드립니다.
   * 관련 기사 링크 http://www.hellot.net/new_hellot/magazine/magazine_read.html?code=201&sub=004&idx=51142
   * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/Doorhandle__a.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/Doorhandle__b.stl
              
   ![image](https://user-images.githubusercontent.com/62414626/77599063-e8a8ec80-6f46-11ea-8994-5fe0217d318d.png)

## 3. Door handle v2

   * 이 장치는 문을 개폐할 때, 엘레베이터나 벨 등을 누를 때 등 다양한 생활 접촉 오염을 줄이고자 개발되었으며 손을 대신하여 사용할 수 있는 작은 사이즈의 툴입니다.
   * 이 장치는 AMC_MI2RL 의 자체모델링으로 개발되었으며, FDM 프린터의 PLA, ABS 등 견고한 아크릴 소재로 출력하기를 권장드립니다.
      * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/keyring%20type-L_cut.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/keyring%20type-S_cut.stl
        
   ![image](https://user-images.githubusercontent.com/62414626/77602335-89e87080-6f50-11ea-8599-f841b1d4c20d.png)

## 4. Ear safety (Mask controler)

   * 이 장치는 장시간 착용하는 마스크로 인한 귀통증을 줄여주기위해 개발되었습니다.
   * 이 장치는 일명 '맥심손잡이'로 불리는 귀보호 대체용품에서 착안하여, AMC_MI2RL 의 자체모델링으로 개발되었습니다.
   * 머리카락에 미끄러지지않게 돌기를 추가하였으며, 얼굴 사이즈에 따라 3단계로 조절하여 착용할 수 있습니다.
   * 관련 기사 링크 https://www.hankyung.com/economy/article/2020031819441
   * FDM 프린터의 TPU 재료로 flexible 하게 출력하기를 권장드립니다.
   * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/ear_safety_v3%200.5MI2RL.stl
              
   ![image](https://user-images.githubusercontent.com/62414626/77731241-e37e9700-7045-11ea-9db1-046706f7e3b1.png)
   
## 5. Safety glasses frame

   * 이 장치는 바이러스로부터 안구와 얼굴전체를 보호하기위한 보호용구로서 개발되었습니다.
   * 이 장치의 프레임에 안면 보호 가능한 투명아크릴지 등을 고정하여, 사용할 수 있습니다.
   * Thingiverse 배포 된 모델링을 기반으로 수정되었으며, FDM 프린터의 PLA 재료로 견고하게 출력하기를 권장드립니다.
   * STL 링크 
   
                https://github.com/mi2rl/3DP-COVID19/blob/master/safety_glaases%20v1.stl    
    
   ![image](https://user-images.githubusercontent.com/62414626/77722724-e66f8c80-7031-11ea-8c56-8570985a36af.png)
  
  ## 6. Auto hand cleaner dispenser housing

   * 이 장치는 MI2RL 에서 개발한 자동분사 손세정제 (DONT Push Dispenser) 의 하우징을 위해 제작되었습니다.
   * 관련 개발품 링크 https://github.com/mi2rl/DONT_dispenser
   * 이 장치는 다양한 사이즈의 손세정제를 적용하여 사용할 수 있으며, AMC_MI2RL 의 자체모델링으로 개발되었습니다.
   * FDM 프린터의 PLA 재료로 견고하게 출력하기를 권장드립니다.
   * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/dispenser%20housing_BODY.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/dispenser%20housing_PLATE.stl
    
   ![image](https://user-images.githubusercontent.com/62414626/77607620-48f75880-6f5e-11ea-8bb5-7362fb3d59cd.png)
  
  
# Contributer
* 모델링 및 출력
* 홍다영(dyhong.89@gmail.com) 김태훈(taehun416@gmail.com)
* 기획 및 총괄
* 김남국([namkugkim@gmail.com](mailto:namkugkim@gmail.com))
