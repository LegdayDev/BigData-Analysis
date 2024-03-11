## 2일차 학습

### 데이터 분석 기초

#### Pandas 학습(1일차에서 계속)
2. `Pandas` 내용 통합(merge, concat)
   - ![concat](https://github.com/LegdayDev/BigData-Analysis/blob/master/day02/images/ba002.png)
#### Numpy 학습
- `Numpy` 는 _**행렬처리 수치 계산을 손쉽게**_ 할 수 있도록 도와주는 계산관련 라이브러리
- `Scipy` 는 과학쪽에 특화된 계산관련 라이브러리
- `DataFrame` 에서 수치적으로 처리할 게 있으면 numpy로 변경한 다음 다시 DF로 변경
#### `Matplot.lib` / `Seaborn` 학습
- `Matplot.lib` 은 데이터 시각화 라이브러리 
- `Seaborn` 은 Matplotlib 의 서드파티 라이브러리

#### Selenium 학습
- 크롬 드라이버 버전확인
  - ![크롬버전확인](https://github.com/LegdayDev/BigData-Analysis/blob/master/day02/images/ba003.png)
- 크롬 드라이버를 버전에 맞게 설치하고 설치파일을 `/usr/local/bin` 으로 이동
- `BeatifulSoup` 라이브러리를 이용하여 크롤링한 데이터를 HTML 모형으로 변경
---

##### Pandas 2.0 이상 문제

> pandas 2.x 버전 이상에서는 `append()` -> `concat()` 으로 대체됨!