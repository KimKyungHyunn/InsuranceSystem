# 보험 설계 시스템
보험사의 요구사항 명세서를 기반하여 구축한 웹 프로젝트 <br>

## 프로젝트 기간
2020.03.10 ~ 2020.12.10 <br>

## 프로젝트 소개
보험 설계/판매, 고객 유치/관리 등의 기능을 수행하는 보험사 시스템을 웹 사이트로 구축 <br>

## 팀원
[김경현](https://github.com/KimKyungHyunn) <br>
[정석우](https://github.com/seokwoo-jeong) <br>
[함정원](https://github.com/HamJeongWon) <br>

## 사용 스택
**java, spring, MySql, MyBatis, jsp, html, css, javascript** <br>

## 시스템 설명
1. 보험의 종류는 화재, 실비, 자동차 보험으로 나뉘며 보험사는 보험 설계가 가능하다.<br><br>
2. 보험에 가입하려는 고객의 개인 정보를 입력 받아 개인의 직업, 병력 등에 따라 기존 설계한 보험 상세 내용에 따라서 보험료를 조건에 따라 계산하도록 하여 보험료에 차등을 둔다.<br><br>
3. 개인 정보가 완료되면 인수 심사를 거치는데 이때 상세 내용을 확인 후 인수 승인, 거절을 결정한다.<br><br>
4. 인수 심사가 완료되면 보험 계약서를 작성한다.<br><br>
5. 보험사는 자사의 보험에 가입한 고객들의 정보를 관리한다.<br><br>
6. 보험사는 고객의 계약서를 관리하고 만기계약자, 미납자 확인이 가능하다.<br><br>
7. 보험사는 만기 계약자의 계약을 연장할 수 있으며 계약서 내용을 수정 가능하다. <br><br>

## 구현한 기능
**1. 보험 리스트**
  - 보험 카테고리(자동차, 실비, 화재)에 해당하는 보험 정보가 리스트로 출력 <br>
 
**2. 보험 가입**
  - 보험 요율 차등 적용: 고객의 개인 정보에 따라 보험 요율 차등 계산 <br>
  (예로 직업이 군인인 경우 실비 보험비가 다른 직업을 가진 고객보다 높은 보험요율 산출되도록 계산) <br>

**3. 영업 활동**
  - 신규 고객의 보험 가입: 개인 정보 저장, 보험사의 인수 절차를 밟도록 대기
  - 기존 고객이 보험 가입: 기존 고객이 가입한 보험의 종류 확인하여 새로운 종류의 보험 선택 가입 <br>
  (예로 자동차 보험 가입자는 보험 가입 진행 시 실비, 화재 보험만을 선택할 수 있게 함) <br>
 
**4. 계약관리하기**
  - 미납자 확인 기능: 보험 납부일 지난 고객들을 확인
  - 만기계약관리 기능: 보험 계약 기간 만료된 가입자들 확인하여 재계약을 수행
  - 계약서 관리 기능: 보험 계약 만료자들의 계약을 연장, 계약서 수정  <br>
    
<br>

## 시연 화면

**- 메뉴얼 확인**<br>

![image](https://user-images.githubusercontent.com/62202364/179450380-04246374-75fa-491d-ab79-1566b11c66db.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450417-608a79bf-f113-419d-9b8d-feb35dea1836.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450422-6329a746-29cc-48bf-a90e-fe12f2b4b9d1.png)
<br>
<br>

**- 상품 가입 신청**<br>

![image](https://user-images.githubusercontent.com/62202364/179450438-e787ee19-5c7f-41e0-b97c-f5c2a7176ae0.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450504-7a2254d2-7f41-462d-8605-3df3b3accc8e.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450519-677b4f7b-fdc1-4fa1-98df-1e1b1c97c29d.png)
<br>
<br>

**- 상품 가입자 리스트**<br>

![image](https://user-images.githubusercontent.com/62202364/179450545-ec72c045-e034-44ae-a46b-de34d304b712.png)
<br>

**- 화재, 자동차 보험에 가입된 고객의 보험 가입**<br>
![image](https://user-images.githubusercontent.com/62202364/179450613-d7307453-6785-47bd-a2d7-db38f841ffd2.png)
<br>
<br>

**- 계약 관리**<br>

![image](https://user-images.githubusercontent.com/62202364/179450623-507ce62e-870b-4a12-b084-4035cf13520e.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450679-8edc8c77-7cf2-4466-b5ef-1c5740b91f16.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450684-d253885c-fb20-41a5-8c06-7d938730f527.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450725-1cde7573-700d-4f58-bbd0-a37541d004d5.png)
<br>

![image](https://user-images.githubusercontent.com/62202364/179450696-3130a4c6-e5e3-4c9c-9c01-02554b3bbc0d.png)
<br>

<br>







