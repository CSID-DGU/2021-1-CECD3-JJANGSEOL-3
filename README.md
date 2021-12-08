# 2021-1-CECD3-JJANGSEOL-3
##  HRV데이터와 SVM을 활용한 스트레스 판단 모델 구현 with 고그린테크

## 짱설팀
* <b> 2013112016 노승수(팀장) </b>
* <b> 2016110413 박희상 <b>

## 1. 개발 배경
### 1. 독거노인의 증가, 독거노인의 높은 자살률

2000년 ~ 2020년 독거노인 비율             |  OECD 주요국 65세 이상 자살률
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/46514182/122636989-3058fc80-d127-11eb-867d-00ba987d220d.png) |  <img width = 350 src = "https://user-images.githubusercontent.com/46514182/122637041-7ada7900-d127-11eb-9ecc-e09a05b416c1.png">

독거노인은 경제상황이나 신체 건강의 어려움도 있지만 정신건강도 매우 취약하다.  
한국은 OECD 국가들 중 노인 자살률이 높은 국가이다.  
한국 노인 중 독거노인의 자살률은 더 높다.

### 2. 이에 따른 사회복지공무원의 업무 부담 증가로 늘어나는 독거노인의 수를 감당할 대안 필요

복지사 1명당 담당하는 대상자             |  읍면동 사회복지공무원 확충 계획
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/46514182/122637283-b3c71d80-d128-11eb-8008-9dd314d7c161.png) |  <img width = 350 src = "https://user-images.githubusercontent.com/46514182/122637222-65b21a00-d128-11eb-9ab9-1463f3377399.png">

## 2. 개발 목적
### Swell Dataset의 심박 변이 데이터(HRV 데이터)를 활용하여, SVM을 통한 사용자의 스트레스 유무를 판단할 수 있는 시스템과 어플리케이션을 개발해 사용자에게 시각적으로 스트레스 유무를 알려준다.

## 3. 작동원리
<b> 안드로이드 앱에 저장된 HRV데이터를 서버로 전송하여 분류한 뒤 데이터를 전송받아 앱내의 데이터베이스에 저장후 그래프로 표시 </b>

<img width = 900 src="https://user-images.githubusercontent.com/81959099/145167689-813bdd88-3fec-4521-8d9c-fe7fd2292aeb.png">



## 4. 개발환경
<p>
<img height = 30 src="https://img.shields.io/badge/Java-orange">
<img height = 30 src="https://img.shields.io/badge/AndroidStudio-green">
<img height = 30 src="https://img.shields.io/badge/Flask-blue">
<img height = 30 src="https://img.shields.io/badge/python-purple">
</p>

## 5. 주요 기능
* 사용자 맞춤형 UI 제공
* 119 응급전화 버튼
* 스트레스 유무를 그래프로 표현

## 6. UI
1. 메인
<img width = 900 src="https://user-images.githubusercontent.com/81959099/145168728-f4b64221-0f69-4585-a842-432d0cdea48b.png">

2. 그래프
<img width = 900 src="https://user-images.githubusercontent.com/81959099/145168807-6f2055fe-a633-4452-9589-e1dc43dbcde1.png">

