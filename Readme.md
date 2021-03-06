<img width="871" alt="MI2RL_logo" src="https://user-images.githubusercontent.com/55417425/77146652-e4a44700-6ace-11ea-9e69-3d38b3f35392.png">
<br>

#### * Read this in English : https://github.com/mi2rl/3DP-COVID19/blob/master/Readme_ENG.md

## Contents
	Safety Devices with 3D Printing
	Medical Device Reverse Engineering
	 1. Customized Mask
	 2. Forearm Door Opener
	 3. Portable Door Opener
	 4. Mask-Strap Holder
	 5. Face/ Eye Protector
	 6. Automatic hand dispenser housing
	Contributers



# Safety devices with 3D printing
* 해당 프로젝트는 신종코로나바이러스(코로나19, SARS-CoV-19)를 극복하기위해 서울아산병원 MI2RL 연구실(이하 AMC_MI2RL)에서 진행하고 있습니다.
* 코로나바이러스감염증의 팬데믹으로 인해 전세계적으로 의료종사자들이 의료장비의 고갈에 시달리고 있습니다. 이에 본 프로젝트는 해당 상황에 대처하기 위해 기존의 마스크나 손소독제의 단점을 보완할 수 있는 장비들 뿐만 아니라, 현 상황에 필요한 기존에 없던 새로운 장비를 개발하고 보급하는 것을 목적으로 합니다.
* 업로드 된 STL 파일은 3D modeling program 인 3-matics (Materialise) 와 Solidworks s/w를 이용하여 제작되거나 수정되었습니다.
* 필요하신 분들은 링크 된 STL 파일을 무료로 다운받으셔서 출력하셔도 됩니다. (Copyright 2020. Univeristy of Ulsan College of Medicine. All right reserved according to FreeBSD License.)
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

## 1. 개인 얼굴 맞춤형 마스크 (Human-specific mask)

   * 이 장치는 얼굴을 3D scan 하여, 개인얼굴 맞춤형 마스크를 공급하기 위해 개발되었습니다.
   * 특징: 저가, 헤파필터 교환형, 살균 가능, 얼굴 맞춤형
   * AMC_MI2RL 의 자체모델링으로 개발되었으며, FDM 프린터의 Flexible 한 TPU 재료로 출력하기를 권장드립니다.
   * STL 링크 (준비중)
   
   ![image](https://user-images.githubusercontent.com/62414626/78964722-104aa800-7b36-11ea-96d0-7a5c85ec4e3a.png)
              
              
   
## 2.  팔로 여는 문고리 (Forearm door opener)

   * 이 장치는 문을 열고 닫을 때 생길 수 있는 접촉 오염을 줄이고자 개발되었습니다. 손을 사용하지 않고 문을 개폐할 수 있는 방식을 제안합니다.
   * 관련 동영상링크 https://youtu.be/Ut0sYw5X-XA
   * 이 장치는 STRATASYS 사의 모델링을 참고하였으며, 사용자의 편의와 설치 안정성을 보완하기 위해 MI2RL의 추가 모델링을 통해 제작되었습니다. FDM 프린터의 PLA, ABS 등 견고한 아크릴 소재로 출력하기를 권장드립니다.
   * 관련 기사 링크 http://www.hellot.net/new_hellot/magazine/magazine_read.html?code=201&sub=004&idx=51142
   * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/Doorhandle__a.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/Doorhandle__b.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/Doorhandle_support.stl
              
  ![image](https://user-images.githubusercontent.com/62414626/79185342-95dd9900-7e51-11ea-924b-257d3027fb1e.png)


   
   
## 3. 휴대용 문고리 (Portable Untact Tool; PUT)

   * 이 장치는 여러명이 사용하는 손세정제, 엘리베이터 버튼이나, 문을 개폐할 때 등과 같이 교차감염이 우려되는 다양한 생활 접촉 오염을 줄이고자 개발되었으며, 네임택 목걸이에 걸고 다니면서 손을 대신하여 사용할 수 있는 도구입니다.
   * 사용법: Finger holder에 검지손가락을 고정하여 사용합니다 (그림참고). Button은 엘리베이터 버튼 등을 누를 때 이용하며, Door는 특히 당기는 문 개폐 시 고리에 걸어 사용할 수 있습니다. 해당 도구는 keyring에 사원증 목걸이나 개인키링에 걸어서 사용할 수 있도록 휴대성을 높였습니다.
   * 이 장치는 AMC_MI2RL 의 자체모델링으로 개발되었으며, FDM 프린터의 PLA, ABS 등 견고한 아크릴 소재로 출력하기를 권장드립니다.
      * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/mobile%20door%20opner.stl
        
   ![image](https://user-images.githubusercontent.com/62414626/79720900-75fc1880-831c-11ea-8097-042e56ec015f.png)


## 4. 마스크 고리 (Size-adjustable ear guard)

   * 이 장치는 장시간 착용하는 마스크로 인한 귀통증을 줄여 주기 위해 개발되었습니다.
   * 특징: Version 1은 두가지 타입으로 제작되었으며, 귀에 거는 방식은 머리카락에 미끄러지지 않게 돌기를 추가하였고 얼굴크기에 따라 3단계로 조절 가능합니다. 귀에 걸지 않는 방식은 부드럽게 목에 닿도록 하였고 얼굴크기에 따라 3단계로 조절 가능합니다. Version 2는 귀에 걸지 않는 방식으로 얼굴크기에 따라 4단계로 조절가능하며, 2D 형태로 제작되었습니다.
   * AMC_MI2RL 의 자체모델링으로 개발되었습니다.
   * 관련 기사 링크 https://www.hankyung.com/economy/article/2020031819441
   * FDM 프린터의 flexible 한 TPU 재료로 출력하기를 권장드립니다.
   * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/ear_safety_v3%200.5MI2RL.stl
              
   ![image](https://user-images.githubusercontent.com/62414626/79721696-bf993300-831d-11ea-8c5e-ba9376fa26ae.png)
   
   
## 5. 얼굴/눈 가리개 (Face/eye protector)

   * 이 장치는 바이러스로부터 안구와 얼굴전체를 보호하기위한 보호용구로서 개발되었습니다.
   * 이 장치의 프레임에 부착용 스펀지와 안면 보호 가능한 투명아크릴지 (OHP 필름) 등을 고정하여, 손쉽게 사용할 수 있습니다.
   * 이 장치는 3공 펀치를 이용하여 손쉽게 구멍을 뚫어 이용할 수 있게 만들어졌습니다. (규격: 93.5*93.5 mm)
   * AMC_MI2RL 의 자체모델링으로 개발되었으며, FDM 프린터의 PLA 재료로 견고하게 출력하기를 권장드립니다.
   * 개선사항: 일반적인 두상에 맞게 사이즈 조정, 피부에 닿는 면을 넙적하게 수정하여 통증이 없게 하고, 스펀지로 고정.
   * STL 링크 
   
                https://github.com/mi2rl/3DP-COVID19/blob/master/Face-eye%20protector.stl 
    
   ![image](https://user-images.githubusercontent.com/62414626/80060233-02028000-8569-11ea-8fab-d070512e8888.png)
  
  
  ## 6. 자동 손세정제 하우징 (Automatic hand dispenser housing)

   * 이 장치는 MI2RL 에서 개발한 자동분사 손세정제 (DONT Push Dispenser) 의 하우징을 위해 제작되었습니다.
   * 관련 개발품 링크 https://github.com/mi2rl/DONT_dispenser
   * 이 장치는 다양한 사이즈의 손세정제를 적용하여 사용할 수 있으며, AMC_MI2RL 의 자체모델링으로 개발되었습니다.
   * FDM 프린터의 PLA 재료로 견고하게 출력하기를 권장드립니다.
   * STL 링크 
   
              https://github.com/mi2rl/3DP-COVID19/blob/master/Automatic%20hand%20dispenser%20housing%20p1.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/Automatic%20hand%20dispenser%20housing%20p2.stl
              https://github.com/mi2rl/3DP-COVID19/blob/master/Automatic%20hand%20dispenser%20housing%20p3.stl

  
   ![image](https://user-images.githubusercontent.com/62414626/78966860-d54b7300-7b3b-11ea-9514-5be9274c2969.png)
   
  
## 6. Contributer

   
   * 모델링 및 출력
     * 홍다영([dyhong.89@gmail.com](mailto:dyhong.89@gmail.com)), 김태훈(taehun416@gmail.com) 권재영(nisroeld2@gmail.com) 권은서 (nan27es@gmail.com) 옥준혁 (jhock8755@gmail.com) 구준모 (kwjnmo7@gmail.com)   
   * 기획 및 총괄
     * 김남국([namkugkim@gmail.com](mailto:namkugkim@gmail.com))
   * 기부
     * 서울아산병원/울산의대 서준범, 김남국
