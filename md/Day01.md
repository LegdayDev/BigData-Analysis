## 1일차 학습

### 빅데이터 개요
> `빅데이터(BigData)`란 ***디지털 환경에서 발생하는 대규모 데이터***를 말한다.</br>
> 대량 데이터 수집, 저장, 관리, 분석하는 HW/SW 유통, 활용까지 포함한다.

- 빅데이터의 순서는 아래와 같다.
1. 데이터 생성
2. 수집
3. 저장
4. 분석(EDA, 머신러닝, 딥러닝)
5. 표현(시각화)
- 데이터 생성 : IoT(사물인터넷), 빅데이터 플랫폼
- 데이터 수집 : 빅데이터 플랫폼(하둡, Kafka, ...)
- 데이터 저장 : 빅데이터 플랫폼(Kafka, ...)
- 데이터 분석 : 통계(EDA), 머신러닝, 딥러닝, 자연어처리, 패턴인식, 이미지 프로세싱(Spark, Power BI, Tableau...)
- 데이터 표현 : Visualization(Power BI, Tableau, ...)

### [실습자료](https://github.com/Play-with-data/datasalon)
### [파이썬 기본 리뷰](https://github.com/LegdayDev/Python-Study)
### 데이터 분석 기초
- `Pandas` : 데이터 처리 라이브러리
- `Numpy` : 수치해석, 계산용 라이브러리
- `Excel`, `CSV` 용 라이브러리 : 엑셀 , CSV, JSON 문서 데이터 로드, 저장 라이브러리
- `Selenium` : 웹 크롤링 자동화 라이브러리
- `BeautifulSoup` : 웹 데이터를 정제하는 라이브러리
- `Seaborn` : 시각화 라이브러리
- `Folium` : 지도 시각화 라이브러리
- `TensorFlow` : 머신러닝 라이브러리(Google에서 만듬)
- `PyTorch` : 머신러닝, 딥러닝 라이브러리(Meta 에서 만듬)
- ...

#### Pandas 학습
> 데이터 분석(로딩, 처리 ...) 라이브러리

1. Pandas 자료구조
    - 데이터프레임 , 시리즈
        - [데이터프레임 사용법](https://github.com/LegdayDev/BigData-DataAnalysis/blob/master/day01/da_01_pandas_basic.ipynb)
    - 데이터 통합
        - [데이터 통합 사용법](https://github.com/LegdayDev/BigData-DataAnalysis/blob/master/day01/da_02_pandas_basic.ipynb) 
    



> ##### VS Code 문제확인
> 1. Jupyter Notebook 실행 속도 느려지는 문제</br>
>    -  Ctrl + ,(설정) > Jupyter > Logging: Level -> off or Verbose로 변경(debug 기본값)
> 2. Intellisense로 느려짐</br>
>    - Ctrl + ,(설정) > TypeScript, Editor > Suggest 모두 해제
>    - 필요한 것만 체크해서 사용
