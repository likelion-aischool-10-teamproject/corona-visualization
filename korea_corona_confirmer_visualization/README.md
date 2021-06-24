# 대한민국 시도별 코로나 

## 목표
대한민국 시도별 코로나 확진자 지도 시각화

#### 참조 링크
1)  [코로나19(COVID-19) 실시간 상황판](https://coronaboard.kr/)
2)  [전국 시도별 geojson](https://neurowhai.tistory.com/350)

## 과정
- 주요 라이브러리 : `selenium` `bs4` `pandas` `folium` `json`  
1. *1) 사이트*에서 국가별 코로나 사망률과 완치율 정보를 가져온다  
2. *2) 사이트*에서 국가 이름과 그 국가가 속한 대륙 이름을 가져온다.  
3. 국가별 사망률과 완치율, 국가가 속한 대륙 이름을 DataFrame으로 묶는다.  
4. 대륙별로 평균 사망률과 완치율의 평균을 구한다.  
5. 시각화한다.

## 결과
| 전국 확진자|인구대비 전국 확진자|
|----------|-------------|
|<img src = "https://user-images.githubusercontent.com/39752251/123236554-da65c980-d517-11eb-9fae-c974a32dadf1.png" width="100%">|<img src = "https://user-images.githubusercontent.com/39752251/123236564-dcc82380-d517-11eb-844e-8d46cb036dcb.png" width="100%">|

## 해석 및 향후 개선 사항
- 
