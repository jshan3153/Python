# KAKAO-map-API

### 0. 준비 사항
- 실행에 앞서 pandas, requests 패키지를 설치 필요

### 1. 코드 설명
- (x, y) 경위도 좌표계를 입력으로 받고, 카카오 지도 API를 통해 해당 경위도 좌표계에 대한 주소 및 행정구역 코드를 반환하는 코드 


### 2. 데이터 설명
- 예시로 들어있는 병원.csv의 출처: https://data.seoul.go.kr/dataList/OA-20337/S/1/datasetView.do
- 해당 csv 파일에는 이미 도로명주소가 포함되어 있으므로 새로운 데이터 프레임에 기관ID와 경위도 좌표 열만 불러옴 


### 3. 주의사항
- 개인이 직접 카카오 개발자 웹사이트에 가입 후 API KEY값을 맨 위에 직접 입력해야 함 
- 경위도 좌표계가 아닌 다른 좌표계에서는 작동하지 않음
