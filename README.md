# 2020 NIMS 산업수학 아카데미

## 주제 1 - 공유 자전거 데이터를 이용한 산업수학 문제정의 및 해결

- 2020년 11월 5일(목) ~ 8일(일)
- 부산시 해운대구 벡스코 제 1 전시장 315호
- 진행: 조진환, 김민중, 양승환 (국가수리과학연구소 산업수학혁신센터)
- GitHub: https://github.com/chofchof/2020-nims-academy

## 따릉이 데이터를 이용한 데이터 분석

- 목적: 서울시 따릉이 데이터를 이용한 [탐색적 자료 분석](https://ko.wikipedia.org/wiki/탐색적_자료_분석) ([EDA; Exploratory Data Analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis)) 실습

- 출처: 블로그 - 하나씩 점을 찍어 나가며 by 흠시 https://dailyheumsi.tistory.com
  1. [All about 따릉이 EDA, 1편] 대여소 살펴보기 https://dailyheumsi.tistory.com/86
  2. [All about 따릉이 EDA, 2편] 따릉이, 이용량은 얼마나 변했을까?
https://dailyheumsi.tistory.com/87
  3. [All about 따릉이 EDA, 3편] 따릉이 이용량 더 자세하게 살펴보기
https://dailyheumsi.tistory.com/88
  4. [All about 따릉이 EDA, 4편] 따릉이, 유저 분석해보기
https://dailyheumsi.tistory.com/104
  5. [All about 따릉이 EDA, 5편] 마포구, 따릉이는 얼마나 어떻게 이용되고 있을까?
https://dailyheumsi.tistory.com/91
  6. [All about 따릉이 EDA, 6편] 대여소별 따릉이 대여건수 예측
https://dailyheumsi.tistory.com/95
  7. GitHub https://github.com/heumsi/Seoul-Public-bicycles-EDA

## 실습 환경

- **Anaconda Individual Edition** (Python 3.8)
  - Anaconda: https://www.anaconda.com/products/individual#Downloads
  - Miniconda: https://repo.anaconda.com/miniconda/
- 가상환경
  ```bash
  conda create -n nims_academy python=3.8 numpy pandas matplotlib jupyterlab seaborn xlrd
  ```
- 실습환경
  ```bash
  conda activate nims_academy
  jupyter lab
  ```
