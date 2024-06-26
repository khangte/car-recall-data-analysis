# 자동차 리콜 데이터 분석

## 프로젝트 목표
   ① 한국교통안전공단 자동차 결함 리콜데이터를 분석하여 유의미한 정보 도출
   
   ② 탐색적 데이터 분석을 수행하기 위한 데이터 정제, 시각화 방법 학습
<br><br>

## 주제 선정

 리콜(recall)은 제품의 설계, 제조 단계에서 결함이 발견되었을 시 문제 예방의 차원에서 판매자가 무상으로 수리, 점검 및 교환을 해주는 소비자 보호 제도입니다. 집집마다 개인용 자동차를 보유하게 되면서 자동차는 어느덧 우리 삶의 일상재가 되었지만. 안전성에 대해서는 산발적인 문제 제기가 계속되고 있고, 이에 따라 전격적인 자동차 리콜 사태도 종종 발생하여 화제가 되곤 합니다.
 이번 과제에서는 한국교통안전공단에서 제공한 2022년 자동차 결함 리콜 데이터를 활용하여 유의미한 패턴 및 인사이트를 발굴하고 시각화하는 실습을 진행하도록 하겠습니다.
<Br><Br>

## 데이터 분석 순서

 #### (1) 데이터 읽기 : 자동차 리콜 데이터를 불러오고 Dataframe 구조를 확인

   (1)-1. 패키지 설치 및 import
   
   (1)-2. 데이터 불러오기
   
   (1)-3. 출력 설정 및 데이터 확인

 #### (2) 데이터 정제 : 결측치 확인 및 기초적인 데이터 변형

   (2)-1. 결측치 확인
   
   (2)-2. 중복값 확인
   
   (2)-3. 기초적인 데이터 변형

 #### (3) 데이터 시각화 : 각 변수 별로 추가적인 정제 또는 feature engineering 과정을 거치고 시각화를 통하여 데이터의 특성 파악

   (3)-1. 제조사별 리콜 현황 출력
   
   (3)-2. 모델별 리콜 현황 출력
   
   (3)-3. 월별 리콜 현황 출력
   
   (3)-4. 생산연도별 리콜 현황 출력
<br><br>

## 결론

 본 보고서는 한국교통안전공단에서 제공한 2022년 자동차 결함 리콜 데이터를 활용하여 제조사별, 모델별, 월별, 생산연도별로의 리콜 현황을 분석했습니다.
 제조사별 리콜 횟수는 비엠더블유코리아(주), 메르세데스벹츠코리아(주), 폭스바겐그룹코리아 주식회사 순으로 많은 것으로 확인되었습니다.
 모델별 리콜 횟수는 328i, TGX, TGS, C 300, 328xi, S 580 4MATIC 순으로 많은 것으로 확인되었습니다.
 월별 리콜 횟수는 2월, 4월, 6월 순으로 많은 것으로 확인되었습니다.
 생산연도별 리콜 횟수는 2017년 68건, 2018년 113건, 2019년 197건, 2020년 273건, 2021년 276건으로 2019년 이후 생산된 차량들의 리콜 횟수가 급격하게 증가하여 2020년과 2021년 가장 높은 리콜 차량이 생산된 것이 확인되었습니다.
<br><br>
 
 ### *참고문헌*

 데이터 출처 https://www.data.go.kr/data/3048950/fileData.do
