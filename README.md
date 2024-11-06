# 사사정보 개체명 인식 데이터
논문, 보고서, 특허 등에 기재되어있는 사사(Acknowledgements) 텍스트에서 사업명, 과제명, 과제번호, 연도, 기관 개체명을 자동으로 추출하기 위한 데이터셋이다.

## 데이터 포맷
- CONLL TXT

## 데이터 통계
- 데이터 개수: 2,000건의 사사
- 레이블 수: 11개
![사사](https://github.com/user-attachments/assets/c8018c96-6732-489b-94ea-6445c9e5ef89)
- 인스턴스 수: 5,597개(사업명: 933개, 과제명: 393개, 과제번호: 384개, 연도: 920개, 기관명: 1,967개)

## 데이터 예제
![사사2](https://github.com/user-attachments/assets/257b11b6-76f5-409f-8309-d66da1ccd199)


## 데이터 구축 방법
- KISTI에서 관리하는 국내 학술지 논문 중 최신 논문 11,687건에 나오는 사사 텍스트를 수집하여 이 중 랜덤하게 선택한 사사 텍스트에 존재하는 개체명을 태깅

##  데이터 다운로드
http://doi.org/10.23057/90

## 라이선스
비영리 이용, 출처 표기, 재배포 금지
