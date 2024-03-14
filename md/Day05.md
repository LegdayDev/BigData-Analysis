## 5일차 학습

### 데이터 분석 실습

#### 제주도 핫플레이스 웹크롤링 분석 및 시각화
> 1. 데이터 불러오기
> 2. [카카오 OpenAPI](https://developers.kakao.com) 로 장소 검색한 데이터들 엑셀로 저장
> 3. 인스타그램 크롤링한 정보와 카카오 API로 주소 검색결과정보를 병합(merge)
> 4. 병합한 데이터를 folium 라이브러리로 지도로 시각화
>> ![지도](https://github.com/LegdayDev/BigData-Analysis/blob/master/day05/images/ba009.png)

#### 스타벅스 입지 분석
> 1. 웹 크롤링으로 데이터 수집
>> - [스타벅스 사이트](https://www.starbucks.co.kr/) 에서 웹 크롤링
>> - Selenium 자동화와 bs4로 HTML을 파싱하여 필요한 데이터 수집 후 엑셀파일로 저장
>> - [서울 열린데이터 광장](https://data.seoul.go.kr/) OpenAPI 공공데이터 수집(진행중)
