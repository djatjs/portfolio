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
- 유닛의 코스트, 시너지 등급에 따른 테두리 및 아이콘 변화 매핑.

### 🔹 주요 기능
- 소환사명 기반 전적 검색
- 전적 결과 상세정보 시각화

### 실행 화면

<img width="1168" height="783" alt="image" src="https://github.com/user-attachments/assets/d7ceec90-2831-4315-a64c-689343276e5f" />

<img width="1419" height="1125" alt="image" src="https://github.com/user-attachments/assets/ce8c061e-5003-4e8b-803c-66c426cdca0c" />

<img width="2000" height="785" alt="image" src="https://github.com/user-attachments/assets/69f7574c-bad2-420f-984d-0a0157dda13b" />

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

### 실행 화면

🔹 메인 화면

<img width="2204" height="1657" alt="image" src="https://github.com/user-attachments/assets/a2337e86-ed23-42a4-b005-30ee9424bacb" />

- 로맨스, 로판, 판타지, 무협으로 나누어진 장르마다 실시간 랭킹, 기다리면 무료, 베스트 작품 리스트 나열.



🔹 회원가입 유효성 검사
<img width="881" height="603" alt="image" src="https://github.com/user-attachments/assets/0c0b25fa-bb9c-4865-a7c2-5ecf239c9d53" />

- 회원가입을 위해 이메일을 입력할 때 이메일 형식을 지켜야하고, 가입되지 않은 계정이어야 가입가능.
- 인증코드를 입력하여 인증 성공시 닉네임과 비밀번호, 가입 버튼이 활성화되어 가입가능.
- 닉네임은 사용불가능한 닉네임들을 모아둔 리스트를 만들어두어 유효성 검사로 비속어 사용을 방지.



🔹 역발별 기능 분담 원리

<img width="868" height="371" alt="image" src="https://github.com/user-attachments/assets/28d2a4b0-b405-4b04-8548-430ef55a3269" />

- 계정은 크게 관리자, 출판사, 일반 사용자 계정으로 나뉘며, 출판사는 총책임자(super), 에디터(editor)의 세부권한으로 나누어짐.
  
---

### 관리자
🔹 관리자 대시보드

<img width="980" height="718" alt="image" src="https://github.com/user-attachments/assets/d57bb0f7-643f-4999-98c3-04c677478bd3" />

🔹 출판사 관리

<img width="1188" height="848" alt="image" src="https://github.com/user-attachments/assets/80ccbb5b-3a96-484e-b39a-eccdbc64d913" />

<img width="1176" height="677" alt="image" src="https://github.com/user-attachments/assets/3db9a15a-ab8c-471e-90c6-74feb27433db" />

- 관리자 계정은 출판사 계정을 새로 발급하거나 출판사 계정을 삭제 시킬 수 있음.

---

### 출판사(super)

🔹 출판사 대시보드

<img width="1120" height="677" alt="image" src="https://github.com/user-attachments/assets/15cabcb1-aa27-42ea-bbf1-79b1a47c6be8" />

- 자사의 에디터 수와 연재중인 도서, 완결 도서를 확인 및 에디터 관리 가능.

🔹 에디터 관리

<img width="1312" height="1057" alt="image" src="https://github.com/user-attachments/assets/21484fc2-f784-4e1d-8973-ff606659069c" />

- 자사에 소속된 에디터를 삭제하거나 일반 사용자의 닉네임을 검색하여 에디터로 전환가능.


🔹 에디터 담당 도서 설정

<img width="1005" height="1056" alt="image" src="https://github.com/user-attachments/assets/b3900088-0aec-4072-8d31-265d83c4375d" />

- 도서를 담당할 에디터를 교체 및 보관 가능. 여기서 보관은 담당 회차를 등록할 에디터 지정 없이 출판사에서 임시로 보관해두는 기능으로 담당할 에디터가 없을 때 사용. 
  
---

### 출판사(editor)

🔹 에디터 도서 관리 페이지

<img width="1168" height="1037" alt="image" src="https://github.com/user-attachments/assets/0d8ab878-41d8-47ce-9b76-7b08d9b2b296" />

- 에디터는 자신이 담당하고 있는 도서를 관리하거나 새 도서를 등록할 수 있음.

🔹 새 도서 등록

<img width="645" height="1117" alt="image" src="https://github.com/user-attachments/assets/4f47397a-6566-47db-9c10-1cde3617fc8a" />


🔹 도서 회차 관리

<img width="1185" height="1013" alt="image" src="https://github.com/user-attachments/assets/93c9b258-9855-47a2-9b2b-99d57d9366ba" />

- 회차 등록 : 해당 회차의 내용을 담은 epub파일과 최신 썸네일로 사용할 이미지(미리보기 기능)를 등록하여 회차 등록 가능.

<img width="1185" height="1290" alt="image" src="https://github.com/user-attachments/assets/9bbf676a-4ad9-4b6b-9e54-a3bed3c94b2a" />


### 일반 사용자

🔹 도서 상세 페이지

<img width="1018" height="839" alt="image" src="https://github.com/user-attachments/assets/2b8c9c9a-0306-44f5-a5c4-52a055dee02a" />

- 무료 회차는 바로 소장 및 열람 가능. 유료 회차는 도서 회차 결제 절차를 통해 소장하여 열람 가능.
- 결제된 회차는 내 서재에 담겨 사용자가 구입한 도서의 회차를 열람 가능하도록 설계.

🔹 도서 회차 구입

<img width="1800" height="1129" alt="image" src="https://github.com/user-attachments/assets/c571c49d-36ca-4e37-a39c-5a0bd0ee1c21" />


🔹 도서 리뷰 등록   

<img width="1072" height="839" alt="image" src="https://github.com/user-attachments/assets/9da0c53b-f9c5-4ae6-9acb-2ffc240e122a" />

- 별점과 함께 등록하는 리뷰이기 때문에 ID당 한 번의 리뷰 작성 가능.



🔹 내 서재에 담긴 도서의 회차 감상(epub.js 활용)   
<img width="881" height="1029" alt="image" src="https://github.com/user-attachments/assets/cabc7fae-1598-4aeb-becd-737aa6e68c57" />

<img width="796" height="1029" alt="image" src="https://github.com/user-attachments/assets/01f12c27-79e6-4d1d-a32b-57356bdf3aaf" />

- 회차 마다의 댓글을 남길 수 있음. 평점과 관련 없는 부분이기 때문에 댓글 여러개 작성 가능.

---

## 📫 연락처
- Email: umsunil2@naver.com
- GitHub: https://github.com/djatjs
