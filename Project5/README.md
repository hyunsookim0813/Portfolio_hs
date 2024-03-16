## 2023년 지역사회 문제해결형 빅데이터/AI활용 공모전

`대전시 대중교통 통행수요 예측`

### 1. 프로젝트 목적 및 배경

#### 목적
- 대전 스마트카드 데이터를 활용하여 1시간 단위 발생 통행량을 예측

#### 배경
- 대전광역시에서 수집할 수 있는 공공데이터를 사용해 사회 현안을 풀 수 있는 머신러닝 모델을 구축하는 경진대회

### 2. 데이터 출처 및 설명
 - ### 출처
   - [공공데이터포털](https://www.data.go.kr/index.do)
   - [2023년 6~8월 대전시 대중교통 승하차 수요 데이터](https://www.data.go.kr/data/15060591/fileData.do)
   - [격자데이터](https://map.ngii.go.kr/ms/map/NlipMap.do?tabGb=total)
     
 - ### 설명
   - 컬럼명세
     - GID: 격자번호
     - DATE: 일자
     - TIME: 시간(시)
     - RIDE_DEMAND: 승차 수요 (Target Variable)
     - ALIGHT_DEMAND: 하차 수요

### 3. 참고 (Refrences)
![image](https://github.com/hyunsookim0813/Portfolio_hs/assets/100894661/efe089a5-8ad8-4c52-9792-8397bb3b4216)

![image](https://github.com/hyunsookim0813/Portfolio_hs/assets/100894661/7a0b444c-51b9-4e32-b399-19ab4d8048d6)


### 4. 프로젝트 참여 인원
- 김현수(개인프로젝트)

### 5. 한계점 및 회고
해당 공모전을 준비을 한 기간이 하루 밖에 되지 않아 다양한 방법을 시도하지 못하여 아쉬웠음

DACON의 공모전에 참여하면서 평가산식이 MAE인 정량적인 예측은 주로 AUTOGLUON이라는 모델이 성능이 좋다는 것을 알고 있었기에 이를 주로 사용했음

model의 학습시간의 한계도 존재해서 기본 파라미터로 모델을 학습하여 예측을 하였음
