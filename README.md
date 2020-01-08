# 서울시 공휴일 약국 운영현황 분석
## 1. 설명
빅데이터 수업의 최종 결과물인 "공공데이터를 활용한 빅데이터 분석 프로젝트"를 진행하면서 만든 프로젝트 결과물 입니다.
기본적인 분석 내용은 **"2017 서울시빅캠상시공모전 - 서울 시민 및 관광객들의 주말/휴일 의료 공백 해소를 위한 휴일지킴이약국제 효율화 필요성 및 정책/서비스 제안"** (https://bit.ly/2Odh2uL) 을 참고하여 제작하였습니다.

## 2. 주제 선정 의의
1. 휴일 또는 주말에도 의료서비스(약국)을 받아야 하지만 당번약국 이외에는 문을 열지 않아 급할 때 약을 구하기 어려움의 문제가 있습니다.
2. 현재 휴일에 운용하고 있는 약국의 현황이 어떠한지 확인하기 위해 서울시 공공데이터 csv 파일과 약국 정보 API를 활용하여 현황을 분석하였습니다.

## 3. 구현하고자 하는 기능
1. 서울시 약국 전체 현황 서울시 구별 분석 및 지도 시각화
2. 서울시 휴일제 약국 현황 서울시 구별 분석 및 지도 시각화
3. 서울시 휴일제 약국 현황 데이터를 토대로 인수구 비례 취약 지역 확인 및 지도 시각화

## 4. 분석 시스템 현황
1. IDE : Jupyer Notebook
2. Programming : Python 3.x
3. System : Intel I5-4210H CPU 2.90Ghz, 12GB RAM, Windows 10 Education

## 5. 참고문헌 및 데이터
1. 참고문헌
* 2017서울시빅캠상시공모전 – 서울 시민 및 관광객들의 주말/휴일 의료 공백 해소를 위한 휴일지킴이약국제 효율화 필요성 및 정책/서비스 제안   (https://bit.ly/2Odh2uL)
* Pharmacy at a glance (2015–2017) - FIP
* 파이썬으로 데이터 주무르기 – 민형기 지음

2. 데이터 셋
* 서울시 약국 데이터 셋 - 서울열린데이터 광장
(http://data.seoul.go.kr/dataList/datasetView.do?infId=OA-15154&srvType=S&serviceKind=1&currentPageNo=1)
* 서울시 약국 정보 조회 서비스 - 국립중앙의료원, 공공데이터포털 오픈 API Key 사용
(https://www.data.go.kr/dataset/15000576/openapi.do)
* 서울시 구별 인원 정보 - 공공데이터포털, 서울열린데이터 광장
(https://data.seoul.go.kr/dataList/datasetView.do?serviceKind=2&infId=419&srvType=S&stcSrl=419)
