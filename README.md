# BANKIDZ-DEPLOY
뱅키즈 배포 레포지토리입니다.

---
![image](https://user-images.githubusercontent.com/63996052/180037052-29f57dd5-ef81-4062-8326-472c7c2b27be.png)


<div align="center"> 
💰 실전 금융 경험을 통해 어린이 금융 리터러시를 향상시키다, <b>BANKIDZ</b> 🐷
</div>

---

## Project Architecture of Deploy
![KakaoTalk_Photo_2022-07-11-20-35-48](https://user-images.githubusercontent.com/59060780/178255707-814eb2ac-be3a-4350-940c-f060890c2420.jpeg)

## 배포 상황

### 2022-07-20 ### 
메인 첫 merge / 배포 후 테스트

### 2022-07-21 ###
클라이언트 이미지 업데이트

### 2022-07-23 ###
v0.0.2 클라이언트 에러 해결, 서버 돈길 완주 성공 / 실패 기능 추가

### 2022-07-25 ###
aT, rT 인증 및 리프레시 체크

### 2022-07-29 ###
* v0.0.6
* BE 수정 사항
  * 돈길 삭제 API response 수정
  * 돈길 삭제 API Validation 시 거절당한 돈길은 제외
  * 돈길 계약하기 / 돈길 수락 및 거절하기 API는 일요일엔 이용 불가 Validation 추가
  * API별로 접근 가능한 유저들 권한 검사 Validation 추가 

### 2022-07-31 ###
* v0.1.0
* BE 수정 사항
  * 돈길 삭제 API 수정
  * 돈길 걷기 API requestBody 삭제
  * challengeDTO 수정

* v0.1.1
* BE 수정 사항
  * 돈길 삭제 API 성공 시 돈길의 정보를 return
  * 돈길 리스트 API 시, 이자율에 따른 실패 돈길은 param이 accept일 때, 갖고오기
  * 스웨거 수정
---
###### 2022 Bankidz
