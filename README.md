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

### 2022-08-01 ###
* v0.1.2
* BE 수정 사항
  * 자녀의 돈길 리스트 API에 pathVariable, query parameter 하나씩 추가
  * 가족 정보 조회 API에 유저를 가족에서 제외하고 리스트 반환
  * 자녀 리스트 조회 API에 kidId 추가

### 2022-08-03 ###
* v0.1.3
* BE 수정 사항
  * 시간 로직 전면 수정
  * S3 추가
  * parent의 totalCahllenge / savings 컬럼 삭제
  * 그 외 자잘한 에러 수정

### 2022-08-04 ###
* v0.1.4
* FE / BE QA 1차 반영

### 2022-08-31 ###
* BE v0.3.0 버전 배포
  * 애플 소셜 로그인 / 푸시 알림 기능 추가

### 2022-09-05 ###
* BE v0.4.0 버전 배포
  * 푸시 알림 완성 및 완주 돈길 리스트 및 이자지급 API 추가

### 2022-09-07 ###
* BE v0.6.0 버전 배포
  * 푸시알림 리스트업 페이지네이션 처리 버전 및 에러 수정 버전
---

###### 2022 Bankidz
