# 2021 서울특별시 빅데이터 캠퍼스 공모전
식용 곤충 대중화를 위한 서울시 벅스 스테이션 최적 입지 분석
-------------
* 팀명 : 프리밀웜
* 팀원 : [김명훈](https://github.com/minghoona) [김영욱](https://github.com/kjfms) [유혜림](https://github.com/YuHyeRim) [장건희](https://github.com/kuma987)
* 기간 : 2021.9.6 ~ 2021.10.21
* 분석도구 : python, R, QGIS, Excel


### 1. 추진 배경 및 필요성

* 식용곤충 산업의 성장
  - 전 세계적으로 식량문제가 대두되고 있으며, 앞으로 더욱 심각해질 전망
  - *UN 에 따르면, 2020년 6월 기준 만성적인 식량 부족에 시달리는 빈민은 세계 8억 2천만명(2020.06)
  - 이러한 미래 식량 부족 문제의 대안으로, '식용 곤충'이 크게 부각되고 있으며, 전세계 뿐 아니라 국내에서도 식용곤충에 대한 관심과 시장은 확대되는 추세 

<p align="center"><img src = https://user-images.githubusercontent.com/68065313/140670355-b3fac443-2e15-49c0-b6be-5b77e327f1b7.png width="500" height="300"/>


* 식용 곤충에 대한 부정적 인식
  - 식용 곤충의 중요도가 커짐에 따라 이에 대한 인식률은 올라가는 반면, 실제 구매율은 매우 낮은 실정
  - 이러한 현상은 주로 곤충의 외형적인 측면에서 오는 혐오감에서 기인

* 식용곤충에 대한 인식 개선을 위한 연구
  - 식용 곤충에 대한 부정적 인식을 개선하기 위해 다양한 분야에서 연구가 활발히 진행
  - ‘식용 곤충에 대한 소비자들의 인식과 메뉴 개발을 통한 대중화 활성화 방안 연구’에 따르면, 식용 곤충의 대중화 및 활성화 방안의 하나로 ‘식용 곤충 전문점의 다양성 및 용이한 접근성 필요’가 제시됨
  - 이러한 연구 결과들을 바탕으로 식용 곤충의 대중화 및 활성화를 위해 소비자들이 식용 곤충을 다양한 방면에서 접근하고, 체험 및 경험이 가능한 홍보 공간이 필요함을 알 수 있음

* 식용 곤충와 MZ세대
  - MZ세대가 미래 식용 곤충 소비의 주 축이 될것임에도 불구하고, 연령대가 낮아질수록 식용 곤충의 구매, 섭취 경험 및 의사는 떨어지는 실태
  - 향후 구매 및 섭취 의사 또한 2,30대 22.5%, 4.50대 44.6%, 60대 이상 70.9%로 연령이 증가할수록 높음 

<p align="center"><img src = https://user-images.githubusercontent.com/68065313/140671009-8404c4a2-0005-4036-8161-17adba3e38eb.png width="500" height="300"/>
  - ‘에코워리어’, ‘그린슈머’, ‘제로웨이스트 챌린지’ 등 MZ세대를 중심으로 나타나는 소비 트렌드는 MZ세대의 미래 환경 관심도가 높다는 것을 나타냄

<p align="center"><img src = https://user-images.githubusercontent.com/68065313/140671154-d2c71cc8-c3f8-4b7d-a03c-9f664739c71d.png width="500" height="380"/>
  - 이에 따라 MZ세대를 설득하는 것이 성공적인 식용 곤충 대중화를 위한 최우선 과제로 나타남

* 지하철 역사 내 유휴공간 활용
  - 지하철은 2020년 기준 하루 평균 379만 1,368명의 시민이 이용하는 대중교통수단으로서, 역사 내 유휴공간은 시민들에게 접근성이 매우 높은 공간
  - 역사 내 유휴공간은 우수한 접근성을 바탕으로 상점, 문화공간, 휴식공간과 같이, 단순한 도심 기반 시설을 넘어 시민들에게 다양한 서비스를 제공하는 다목적 문화공간으로 활용되고 있음
  - 또한 코로나19 이후 지하철 수요 감소에 따라 역사 내 공실이 증가하며 넓은 공간 확보가 가능해졌고, 정부의 임대료 감면 혜택을 통해 재정적 측면에서도 이점을 지님

#### 따라서 본 조는 식용 곤충 인식 개선 및 소비 활성화를 위해 식용 곤충 소비에 영향을 미치는 요인들을 바탕으로 벅스 스테이션* 최적 입지를 분석하고자 함 
* (가칭) 벅스 스테이션 (Bugs Station) : 원데이 클래스, 인플루언서와의 콘텐츠 제작, 식용 곤충 굿즈 판매 등과 같이, 식용 곤충 체험 기회 제공 및 홍보할 수 있는 공간


### 2. 분석 준비

##### 분석 개요
<p align="center"><img src =https://user-images.githubusercontent.com/82136585/140672780-b5a68280-86ad-4cb2-88a3-a67b79e8a794.PNG width="1000" height="500"/>
