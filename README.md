<h3 align="center">
  골프의 민족
</h3>
<h4 align="center">작업기간: 2023.12.08 ~ 2024.1.15
<h6 align="center">바쁜 일상 속에서 온라인 예약 시스템과 쇼핑 솔루션을 <br/>언제 어디서나 쉽고 편리하게 이용할 수 있는 것이 목표입니다.</h6>
<p align="center">
  <img src="https://github.com/jungyeon53/Golf/assets/150405152/5c7ea9c7-1706-4449-a05c-75af85abaa5c" style="width:1200px">
</p>

<h2 align="center">Language</h2>
<div align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-007396?&style=for-the-badge&logo=Java&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?&style=for-the-badge&logo=JavaScript&logoColor=white"/>
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?&style=for-the-badge&logo=React&logoColor=white"/>

  <br/>
  <img alt="SCSS" src="https://img.shields.io/badge/SCSS-CC6699?&style=for-the-badge&logo=Sass&logoColor=white"/>
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?&style=for-the-badge&logo=CSS3&logoColor=white"/>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?&style=for-the-badge&logo=HTML5&logoColor=white"/>
  <br/>
  <img alt="Material-UI" src="https://img.shields.io/badge/Material--UI-0081CB?&style=for-the-badge&logo=Material-UI&logoColor=white"/>
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?&style=for-the-badge&logo=MariaDB&logoColor=white"/>
  <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-7952B3?&style=for-the-badge&logo=Bootstrap&logoColor=white"/>
  <br/>
  <img alt="Tomcat" src="https://img.shields.io/badge/Tomcat-F8DC75?&style=for-the-badge&logo=Apache%20Tomcat&logoColor=black"/>
  <img alt="MyBatis" src="https://img.shields.io/badge/MyBatis-007396?&style=for-the-badge&logo=Apache%20MyBatis&logoColor=white"/>
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?&style=for-the-badge&logo=Amazon%20AWS&logoColor=white"/>

</div>

## 골프의민족 프로젝트 목차

1. [프로젝트 개요](#프로젝트-개요)
   - [골프의 민족이란?](#골프의 민족이란?)
   
2. [설계](#설계)
   - [요구사항 정의서](#요구사항-정의서)
   - [데이터 베이스](#데이터-베이스)
   - [와이어프레임] (#와이어-프레임)
   - [프로토타입] (#프로토-타입)
   - [배포] (#배포)

3. [골프의민족 기능](#골프의민족-기능)
4. [이슈사항 및 리뷰](#이슈사항-및-리뷰)

<br/>

## 프로젝트 개요

개발기간 : 2023.12.08 ~ 2024.1.15<br/>
버전 정보 :
Java 17
SpringBoot
React
<br/>

### 프로젝트 선정 배경

골프가 인기를 끌면서 다양한 연령대의 골퍼들을 위한 서비스를 기획했습니다. <br />
골프의 민족은 고객님들이 골프를 좀 더 편안하게 즐길 수 있도록 골프장 예약 및 클럽 구매를 한번에 해결할 수 있는 서비스를 제공합니다.<br />
프로젝트명인 골프의민족은 골프 클럽을 사면 배달해서 받는다는 점이 배달의 민족이 생각이 나서 골프의민족으로 결정하였습니다.

### 골프의 민족이란?

- 바쁜 일상 속에서 효과적인 시간 효율성을 추구하여 예약과 쇼핑을 한번에 이용
- 온라인 예약 시스템과 쇼핑 솔루션을 선호하며, 언제 어디서나 쉽고 편리하게 서비스를 이용
- 주요 타겟은 골프를 즐기는 소비자이며 골프 관련 온라인 플랫폼을 기획
<br/>

## Team Project

**김정연(본인) <br />
DB, 회원 & 소셜로그인, 마이페이지, 골프장 예약 & 취소, 골프장 & 코스 CRUD, <br />
코스 자동등록 이벤트, 회원 탈퇴 트리거, 상품 목록, 백엔드 전반**

이길호(팀장) <br />
DB, 데이터 크롤링, 골프장 리스트, 골프장 상세페이지, 상품 배송 & 결제 , 깃허브 관리

박주영 <br />
메인페이지, 관리자페이지, 회원 등급관리, 골프장 관리, 코스관리
<br/>

## 설계

### 요구사항 정의서
[요구사항 정의서](https://docs.google.com/spreadsheets/d/11xJt0YuB2y7jEehkfivjPkPyFJYvaQPjaBfB6qJ9VMo/edit?pli=1#gid=0)
<p align="">
  <img src="https://github.com/jungyeon53/Golf/assets/150405152/3893a7cb-0975-4cb6-8d07-f276b984455e" style="width:800px">
</p>

### 주요기능
1. 회원
   - 회원가입
   - 로그인
   - 소셜로그인
   - 마이페이지
   - 회원 정보 수정
   - 회원 탈퇴 
2. 골프장
   - 골프장 목록
   - 상세페이지
   - 코스 예약
   - 코스 취소
   - 예약 내역
   - 예약 취소 내역 
3. 관리자
   - 골프장, 코스 CRUD
   - 골프장 검색
   - 코스 검색
   - 회원 등급관리
   - 예약 내역 관리

### 데이터 베이스
[테이블 명세서](https://docs.google.com/spreadsheets/d/11xJt0YuB2y7jEehkfivjPkPyFJYvaQPjaBfB6qJ9VMo/edit#gid=1110240720)<br/>
<img src="https://github.com/jungyeon53/Golf/assets/150405152/629d5c71-3b84-464e-a708-dc1a84038b77" style="width:800px">

## 골프의 민족 정연이가 신경 쓴 기능 🐹

1. 회원가입
   - 이메일 중복검사 : 회원 테이블과 회원 탈퇴 테이블에서 이메일을 가져와 비동기로 중복검사
   - 이메일 인증 : 중복검사를 통과하면 인증 버튼 활성화 후 인증코드 전송 
   - 인증코드 체크 : 인증 버튼 클릭하면 버튼이 자동으로 활성화되고, 실제 코드와 비교
   - 약관동의 : 필수 약관과 선택 약관을 나누어 필수 약관을 체크하지 않으면 alert 작동 
2. 로그인 & 아이디/비밀번호 찾기
   - jwt 토큰을 로컬 스토리지에 저장하는 방식
   - 시큐리티로 비밀번호는 복호화 하여 저장 
   - 카카오 로그인과 네이버 로그인 구현 완료 후 토큰 발행 
   - 이메일 찾기는 인증 수단이 이메일 밖에 없으므로 이메일을 통해 가입한 이메일 전송
   - 비밀번호는 인증 후 새 비밀번호 등록
3. 마이페이지
   - 결제 완료된 상품의 갯수, 예약 완료된 예약 갯수
   - 예약 내역, 취소내역 확인 가능
   - 비밀번호를 한번 더 입력해야 개인정보 수정이 가능 
   - 소셜 로그인 회원은 비밀번호가 없기 때문에 비밀번호 input 비활성화
   - 오류코드를 활용해 비밀번호가 맞지 않음, 새 비밀번호와 비밀번호 체크가 다름 등 을 구현
   - 닉네임 변경 가능 
4. 회원 탈퇴
   - 탈퇴 후 30일 동안 가입 불가능하게 처리
   - 탈퇴 신청 시 트리거를 활용하여 회원 테이블에서는 삭제, 회원탈퇴 테이블에서는 업데이트로 회원 정보 백업
   - 탈퇴일로 30일이 경과하면 이벤트를 활용해 자동 회원 삭제
   - 회원 탈퇴시 데이터 베이스에서 fk의 값들도 자동 삭제 
5. 코스 예약
   - 예약 가능 날짜는 내일부터 3주 뒤까지 날짜 선택 버튼 활성화
   - 날짜를 선택하고 골프장을 선택하면 예약 가능 코스 비동기로 보여줌
   - 중복 예약방지를 위해 예약 신청 시 예약 가능여부를 데이터 베이스에서 조회 하고 예약 신청 완료처리
   - 만약 먼저 신청한 사람이 있다면 "이미 예약이 완료된 코스입니다" 라는 알림창 띄움
   - 과도한 예약 방지를 위해 계정 1개당 하루에 예약 3개만 가능
   - 예약 신청 시 예약 취소가능일을 알려주고, 취소 불가능한 예약은 "취소가 불가능한 예약" 으로 알려줌 
6. 코스 예약 확인 및 취소
   - 무분별한 예약 취소 방지를 위해 예약 확인 페이지에서 예약일 기준 7일전까지 예약 취소버튼 활성화 (그외는 비활성화)
   - 예약취소날짜와 시간을 취소내역에서 확인할 수 있음
7. 코스 자동 등록 이벤트
   - 일정한 코스를 매일 오전 7시에 데이터 베이스 이벤트로 10개 골프장에 각 10개의 코스가 등록됌
8. 상품 목록
   - 사용자 입장에서 상품의 갯수를 눈으로 확인할 수 있음
   - 사용자의 편의성을 위해 클럽의 종류는 버튼 클릭 비동기로 처리
   - 브랜드는 단일선택, 복수선택으로 사용자가 원하는 브랜드를 볼 수 있고, 초기화 버튼으로 원상복구 가능
   - pc 화면에서는 30개의 상품을 볼 수 있고 모바일 환경에서는 과도한 스크롤을 줄이기 위해 10개의 상품을 볼 수 있게 구현
   - 상품이 총 600개가 넘어가므로 페이징 처리 
9. aws 배포
   - 프로젝트 세팅을 jar 로 하여 war를 뽑기 위해 war 추가
   - 배포 이후 이미지 404 이슈로 nginx에서 직접 이미지 경로 설정 > 골프의 민족 이미지는 백엔드에 있음 
   - nginx가 이미지 경로의 실행 권한이 없어 403 오류 > nginx에게 실행권한을 줌
   - 시큐리티 적용을 확실히 하기 위해 url 한번 더 정리
   - 배포 성공.
     <br />
   <a href="https://velog.io/@jungyeon53/AWS-%EB%A6%AC%EB%88%85%EC%8A%A4-%EB%B0%B0%ED%8F%AC%EC%8B%9C-404-%EC%98%A4%EB%A5%98-1">[Velog Link]</a>
   자세한 내용은 velog를 참고해주세요 
## 이슈사항 및 리뷰

### 첫번째 초반 api 설계와 url 명세서를 작성했지만 시큐리티를 적용하면 403 오류 발생
프론트는 /member/login, 백엔드는 /api/member/login으로 백엔드에 적용해야 할 시큐리티 url을 따로 빼놓지 않아 발생 > 전체적인 기능 url 재정비
<br />
### 두번째 코스 예약시 동시예약 이슈 & 1명이 모든 예약을 다한다면? <br />
실시간으로 예약을 체크하는 방법과 예약 신청시 예약 상태를 조회하고 예약 가능 상태일 때만 예약이 가능하게 하는 방법이 있었는데<br />
비교적 단순한 방법인 조회 하고 예약 하는 방법을 선택<br />1명의 과도한 예약 방지를 위해 1개의 계정은 하루에 3개의 예약만 가능하게 헀습니다.<br />
<br />
### 세번째 코스등록은 관리자가 매일매일 해야한다 vs 자동으로 코스를 추가하게 하는 코드를 작성하자 <br />
매일 3주뒤의 코스가 오픈되는 상황에서 자동 코스등록이 좋아보였지만 문제는 테이블을 어떻게 짤까 였습니다.
<br />골프 예약날짜 테이블, 골프 코스 테이블 두개를 짜서 결합시킬 것인지<br />
아니면 6개월치의 코스를 한번에 등록할지 고민했습니다.<br />
제 생각에는 매일 100개의 코스가 자동으로 등록되는 것이 좋은 방법이라고 생각했고 쉽게 구현할 수 있는 방법을 찾던 중 이벤트를 발견하고 활용했습니다.
<br />
### 네번째 예약 취소 가능일 <br />
당일 예약취소 , 쉬운 예약 방지를 위해 예약일 기준 7일전까지 취소 가능<br />
예약 취소 버튼 활성화, 비활성화로 리액트에서 활용<br />
<br />





