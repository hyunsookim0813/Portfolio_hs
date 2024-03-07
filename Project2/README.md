## 2022년 1학기 데이터시각화 기말프로젝트
`배달음식 주문 데이터 분석`

- data_viz_final.ipynb
  - 데이터 전처리
    - 필요 없는 변수 제거
    - 날짜 데이터 형식으로 변환
    - 요일 변수 추가
    - 총_배달건수 컬럼 추가
  - 데이터 시각화
    - 휴가 전 주와 휴가 시즌 총 배달 음식 주문 수 비교
    - 시간대별 배달 음식 주문량 패턴
    - 음식 카테고리 트리맵 시각화
   
- data_viz_ggd.ipynb [맑은 날과 비가 오는 날의 평균 배달 음식 주문 수 비교]
  - 데이터 전처리
    - 위와 동일
    - 경기도만 필터링
    - 맑은 날과 비가 오는 날 분리하여 날씨_분류 컬럼 생성
  - 데이터 분석
    - t-test 검정을 사용하여 비가 배달 주문에 영향이 있는 지 확인
    - 비가 오는 날 총 배달건수가 적은 것은 확인하였으나, P-value: 0.2527로 유의미한 차이가 없다고 판단.


### 📌 사용 데이터

- 날씨별 배달 품목차이 [KT 통신 빅데이터 플랫폼]

### 📌 개요

- 비가 오는 날 배달 음식 주문량은 증가할까?
    
    ![output.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e62146ac-e6f2-425f-b60d-69c847aa67e1/df5c52fc-1389-45b7-88a6-4dd9380f04ea/output.png)
    
- 검정
    
    T-검정 결과:
    
    - T-통계량: -1.15
    - P-value: 0.2527
    
    맑은 날과 비가 온 날의 총_평균_배달건수에서 유의미한 차이가 없음
    
- 연휴 기간과 평일 배달 음식 주문량의 차이
    
    ![output.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e62146ac-e6f2-425f-b60d-69c847aa67e1/8141e34f-5d11-4ada-ad26-c417a2720c42/output.png)
    
- 시간대별 배달 음식 주문량 패턴
    
    ![output.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e62146ac-e6f2-425f-b60d-69c847aa67e1/c58cbd7d-1952-42b3-90e2-2957c67924e4/output.png)
    
- 피크타임 음식 카테고리 분포
