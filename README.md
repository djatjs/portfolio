# 사용자 경험을 고려한 웹 서비스 개발에 관심이 많은 신입 개발자입니다.

본 저장소는 제가 진행한 주요 프로젝트를 정리한 포트폴리오입니다.  
각 프로젝트별 설명, 사용 기술, 주요 기능, 실행 화면을 포함하고 있습니다.

---

## 1. 라이엇게임즈 전적 검색 서비스

**기간**: 2025.03.24 ~ 2025.04.25  
**역할**: TFT 전적검색 기능 구현  
**기술스택**: Java, Spring Framework, JSP, HTML, CSS, JavaScript, Riot API

### 📌 프로젝트 개요
- Riot API를 활용해 사용자의 게임 전적 데이터를 JSON 형태로 받아옴
- 데이터 파싱 및 가공 후, UI를 통해 시각적으로 제공
- 검색창에 소환사명과 태그를 입력하면 전적 정보가 실시간으로 표시됨

### 🔹 주요 기능
- 소환사명 기반 전적 검색
- 전적 결과 상세정보 시각화

### 📷 실행 화면
<img width="1181" height="968" alt="스크린샷 2025-04-15 182431" src="https://github.com/user-attachments/assets/cf93494f-da3e-44a1-9d50-4722ce1a7e8f" />

---

## 2. 웹소설 플랫폼

**기간**: 2025.05.01 ~ 2025.06.12  
**역할**: 백엔드 및 역할별 기능 페이지 개발, EPUB 파일 뷰어 기능 구현  
**기술스택**: Java, Spring Boot, HTML, CSS, JavaScript, Thymeleaf, MySQL

### 📌 프로젝트 개요
- 웹소설 작품 및 회차 관리 기능 개발
- 어드민 계정을 통한 출판사 계정 생성 기능
- 출판사 계정은 소속 에디터 등록, 작품 등록 및 회차 수정 가능
- 일반 사용자는 카카오 로그인 및 이메일 인증 가입
- 비속어/제한 닉네임 필터링, 유효성 검사 등 가입 절차 구현


### 🔹 주요 기능
- 작품/회차 CRUD 기능
- 어드민 페이지 UI 및 데이터 연동
- 조건별 작품 검색 및 정렬

### 📷 실행 화면

메인 화면
<img width="1938" height="1240" alt="image" src="https://github.com/user-attachments/assets/6628b9c5-bf1f-4476-a2cc-852ca1601b19" />

회원가입 유효성 검사
<img width="881" height="603" alt="image" src="https://github.com/user-attachments/assets/0c0b25fa-bb9c-4865-a7c2-5ecf239c9d53" />

역발별 기능 분담 원리 : 계정은 크게 관리자, 출판사, 일반 사용자 계정으로 나뉘며, 출판사는 총책임자(super), 에디터(editor)의 세부권한으로 나누어짐.
<img width="868" height="371" alt="image" src="https://github.com/user-attachments/assets/28d2a4b0-b405-4b04-8548-430ef55a3269" />

---

### 관리자
<img width="771" height="324" alt="image" src="https://github.com/user-attachments/assets/f0a85f9a-905a-414b-b335-3d3e33daba7c" />

---

### 출판사(super)

출판사 대시보드

<img width="791" height="315" alt="image" src="https://github.com/user-attachments/assets/6b4e1c46-93e1-4831-96fd-0b908ee223a6" />

자사 에디터 등록

<img width="1090" height="254" alt="image" src="https://github.com/user-attachments/assets/d868b964-b075-4985-a24a-78d80b781e91" />

에디터 관리

<img width="780" height="377" alt="image" src="https://github.com/user-attachments/assets/ed012e1e-67d4-45ff-8fe0-a2a42f429513" />

에디터 담당 도서 설정

<img width="792" height="349" alt="image" src="https://github.com/user-attachments/assets/f617043c-0bed-4406-a57f-a3f5b1d69bf7" />

---

### 출판사(editor)

에디터 도서 관리 페이지

<img width="814" height="564" alt="image" src="https://github.com/user-attachments/assets/27377dca-cc7c-4f09-82e6-678fc5002b64" />

새 도서 등록

<img width="715" height="883" alt="image" src="https://github.com/user-attachments/assets/a25b5be6-d0c8-4194-9295-c1d9b9a0dc55" />

도서 회차 관리

<img width="624" height="421" alt="image" src="https://github.com/user-attachments/assets/a17c279f-87e8-4042-8e90-d55be238f802" />

### 일반 사용자

도서 상세 페이지

<img width="1090" height="648" alt="image" src="https://github.com/user-attachments/assets/2cd75aa5-91bb-47c8-a9aa-a1182b99cb8b" />

도서 회차 구입

<img width="442" height="385" alt="image" src="https://github.com/user-attachments/assets/e7857419-32a1-45df-8bd7-dd344fedcf99" />

도서 리뷰 등록   

<img width="604" height="677" alt="image" src="https://github.com/user-attachments/assets/2770de02-1d06-47e1-827a-fd976cde73b5" />

내 서재에 담긴 도서의 회차 감상(epub.js 활용)   

<img width="551" height="837" alt="image" src="https://github.com/user-attachments/assets/ab588fb4-65f2-494d-a0a9-56582bcbfe12" />

---

## 📫 연락처
- Email: umsunil2@naver.com
- GitHub: https://github.com/djatjs
