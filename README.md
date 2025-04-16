# MarkTory, 기술을 넘어 이야기를 담는 공간

![front_banner.png](docs/banner/front_banner.png)



<br>

# 🌸 봄이오조 🌸

<table>
  <tr>
    <td><img src="./docs/member/Kasey.JPEG" width="150" height="150"/></td>
    <td><img src="./docs/member/D.JPEG" width="150" height="150"/></td>
    <td><img src="./docs/member/Alex.JPEG" width="150" height="150"/></td>
    <td><img src="./docs/member/Morris.JPEG" width="150" height="150"/></td>
    <td><img src="./docs/member/Dong.png" width="150" height="150"/></td>
    <td><img src="./docs/member/Tim.jpeg" width="150" height="150"/></td>
  </tr>
  <tr>
    <td>:crown:주아현</td>
    <td>강이도은</td>
    <td>곽우석</td>
    <td>이상모</td>
    <td>정동한</td>
    <td>한윤상</td>
  </tr>
</table>


# 기술스택

## 🛠️ Backend
![Java](https://img.shields.io/badge/Java-17-007396.svg?&logo=java&color=red)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3-6DB33F.svg?&logo=spring-boot&color=lightgreen)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F.svg?&logo=spring-data-JPA)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C.svg?&logo=hibernate)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F.svg?&logo=spring-security&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000.svg?&logo=json-web-token&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?&logo=gradle)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162.svg?&logo=junit5&logoColor=white&color=green)

## 💽 DB
<!--![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420.svg?&logo=ubuntu&logoColor=white)-->
![MariaDB](https://img.shields.io/badge/MariaDB-003545.svg?&logo=mariadb)
<img src="https://img.shields.io/badge/MyBatis-FF5733?style=flat&logo=MyBatis&logoColor=white">
<!--!![Redis](https://img.shields.io/badge/Redis-DC382D.svg?&logo=redis&logoColor=white)-->

## ⛓️ Server
<img src="https://img.shields.io/badge/Eureka%20Server-4D8FC9?style=flat&logo=Spring&logoColor=white">

## ⚙ Tool
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"> &nbsp; <img src="https://img.shields.io/badge/ERD%20cloud-%230000FF.svg?style=flat&logo=erlang&logoColor=white"> &nbsp; <img src="https://img.shields.io/badge/DA%23-0B6121.svg?style=flat&logo=draw.io&logoColor=white"> &nbsp; <!--<img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"> &nbsp; <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=Ubuntu&logoColor=white">--><img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat&logo=IntelliJ%20IDEA&logoColor=white">

<br>

<hr>

# 목차
1. [프로젝트 개요](#프로젝트-개요)
    - [개발 배경](#개발-배경)
    - [주요 기능](#주요-기능)
    - [차별성](#차별성)
2. [설계 문서](#설계-문서)
    - [WBS](#WBS)
    - [기능명세서](#기능-명세서)
    - [System Architecture](#System-Architecture)
    - [FLOW CHART](#FLOW-CHART)
    - [DDD](#DDD)
    - [DB 모델링](#DB-모델링)
3. [산출물](#산출물)
    - [와이어프레임](#와이어프레임)
    - [스토리보드](#스토리보드)
    - [TestCase](#TestCase)
    - [결과 화면](#결과화면)
4. [Peer Review](#Peer-Review)

<br>

<hr>

<br>

# 1. 프로젝트 개요
> 자기 PR의 시대, 나만의 개발자 공간을 만들다. 지루한 기술 블로그에서 벗어나 자유롭게 글을 작성하고, 나만의 스타일로 PR할 수 있는 공간!
> MarkTory는 Markdown 기반으로 간편하게 블로그를 운영하고, 개발자 간 소통과 네트워킹을 지원합니다. 기술을 공유하는 것에서 한 걸음 더 나아가, 커스텀 템플릿을 통해 나만의 색깔을 표현하고 성잘할 수 있는 커뮤니티를 제공합니다. 이제 개발자의 글쓰기는 단순한 기록이 아닌, 개인의 브랜딩과 연결되는 새로운 경험이 됩니다. 쉽고 자유로운 글쓰기, 더 넓은 개발자 네트워크! 지금 MarkTory와 함께 나만의 공간을 만들어보세요.

<br>

##  💡개발 배경
### 1️⃣ 개발자 블로그의 한계와 PR 공간의 부재
기술 블로그는 개발자의 성장과 지식 공유의 필수적인 도구이지만, 기존 플랫폼은 개발자 친화적인 기능 부족, 네트워크 제한, Markdown 지원 미흡 등의 문제를 가지고 있습니다. 또한, 개인 포트폴리오와 연결된 자기 PR 공간이 부족하여 개발자들이 자신의 기술력을 효과적으로 표현하기 어려운 상황입니다. 이에 따라, Markdown 기반의 블로그와 PR 페이지를 결합한 새로운 플랫폼이 필요합니다.

### 2️⃣ 자유로운 글쓰기와 네트워킹의 필요성
개발자들은 기술 공유뿐만 아니라 템플릿을 활용한 효율적인 글 작성, 네트워크 형성, 피드백 교류를 원합니다. 하지만 기존 블로그 플랫폼은 구독, 템플릿 공유, 개발자 간 연결 기능이 부족하여 단순한 글쓰기 공간에 머물러 있습니다. 따라서, 개발자들이 기술을 공유하면서도 서로 연결될 수 있는 새로운 커뮤니티가 필요합니다.

<br>

## 💡주요 기능
### 1️⃣ Markdown 기반의 간편한 글쓰기
개발자들이 익숙한 Markdown 문법을 사용하여 손쉽게 글을 작성하고 관리할 수 있습니다.

### 2️⃣ 커스터마이징 가능한 템플릿
다양한 템플릿을 제공하여 사용자가 자신의 스타일에 맞게 블로그를 꾸밀 수 있습니다.

### 3️⃣ 개발자 네트워킹 지원
다른 개발자들의 블로그를 구독하고, 댓글과 피드백을 주고받으며, 협업의 기회를 넓힐 수 있습니다.

### 4️⃣ 포트폴리오
자유롭게 작성한 글과 템플릿을 통해 자신만의 개성있는 포트폴리오를 만들 수 있습니다.

### 5️⃣ 다크모드
개발자에게 익숙한 다크모드로 설계하여 눈에 편안하고 몰입감 있는 환경을 제공합니다.

<br>

## 💡차별성
![necessity.png](docs/necessity/necessity.png)

### 1️⃣ 개발자 중심의 기능 제공
기존 플랫폼들이 가지는 Markdown 지원 미흡, 제한적인 커스터마이징 등의 문제를 해결하여 개발자 친화적인 환경을 제공합니다.

### 2️⃣ 네트워킹과 커뮤니티 강화
단순한 블로깅을 넘어 개발자 간의 소통과 협업을 촉진하는 기능을 제공합니다.

<br>

<hr>

<br>

# 2. 설계 문서
## [📑WBS](https://docs.google.com/spreadsheets/d/10wFU0Njthf9K6DVC--dq2i9O4aNY2OBRSh7FM0_pSks/edit?gid=1950899492#gid=1950899492)
![WBS.png](docs/image/WBS/WBS.png)


## [📑요구사항 명세서](https://docs.google.com/spreadsheets/d/1y6dd31EJpapN8iQiyh6ReCPN7Th8u9reJwvpR0xLoE8/edit?gid=1622427168#gid=1622427168)
![요구사항명세서.png](docs/image/ReQ/%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EB%AA%85%EC%84%B8%EC%84%9C.png)
<br>

## 📑 System Architecture
### Project Server 구조
![아키텍쳐이미지](./docs/architecture/server.jpg)

<br>

## 📑 FLOW CHART
![플로우차트이미지](./docs/flowchart/플로우차트_메인.png)

<br>

## 📑DDD
### 1️⃣ Bounded Context
![바운디드컨텍스트이미지](./docs/ddd/bounded.jpg)

### 2️⃣ Context Mapping
![컨텍스트메핑이미지](./docs/ddd/mapping.jpg)

<br>

# 📑DB모델링
<br>

### 1️⃣ 논리모델링
<img src="https://github.com/user-attachments/assets/bf47f0ca-7cf4-49d7-92cd-6c14674ebc37">

### 2️⃣ 물리모델링
<img src="https://github.com/user-attachments/assets/cdc3f2e9-83c3-4612-ba14-2028e9f8e311">
<br>


# 3. 산출물
##  📍와이어프레임

### 🍀 회원

<details>
   <summary>회원가입</summary>
   <img src="./docs/image/와이어프레임/회원가입_와이어프레임.png" width=700>
</details>

<details>
   <summary>약관동의</summary>
   <img src="./docs/image/와이어프레임/약관동의_와이어프레임.png" width=700>
</details>

<details>
   <summary>로그인</summary>
   <img src="./docs/image/와이어프레임/로그인_와이어프레임.png" width=700>
</details>

<details>
   <summary>아이디찾기</summary>
   <img src="./docs/image/와이어프레임/아이디찾기_와이어프레임.png" width=700>
</details>

<details>
   <summary>비밀번호찾기</summary>
   <img src="./docs/image/와이어프레임/비밀번호찾기_와이어프레임.png" width=700>
</details>

<details>
   <summary>닉네임수정</summary>
   <img src="./docs/image/와이어프레임/닉네임수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>비밀번호수정</summary>
   <img src="./docs/image/와이어프레임/비밀번호수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>프로필이미지수정</summary>
   <img src="./docs/image/와이어프레임/프로필이미지수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>회원탈퇴</summary>
   <img src="./docs/image/와이어프레임/회원탈퇴_와이어프레임.png" width=700>
</details>

<details>
   <summary>로그아웃</summary>
   <img src="./docs/image/와이어프레임/로그아웃_와이어프레임.png" width=700>
</details>

### 🍀 관리자
<details>
   <summary>관리자 로그인</summary>
   <img src="./docs/image/와이어프레임/관리자로그인_와이어프레임.png" width=700>
</details>

<details>
   <summary>회원계정상태변경</summary>
   <img src="./docs/image/와이어프레임/회원계정상태변경_와이어프레임.png" width=700>
</details>

<details>
   <summary>전체회원조회</summary>
   <img src="./docs/image/와이어프레임/전체회원조회_와이어프레임.png" width=700>
</details>

### 🍀 신고관리
<details>
   <summary>게시글신고</summary>
   <img src="./docs/image/와이어프레임/게시글신고_와이어프레임.png" width=700>
</details>

<details>
   <summary>댓글신고</summary>
   <img src="./docs/image/와이어프레임/댓글신고_와이어프레임.png" width=700>
</details>

<details>
   <summary>템플릿신고</summary>
   <img src="./docs/image/와이어프레임/템플릿신고_와이어프레임.png" width=700>
</details>

<details>
   <summary>신고내역조회</summary>
   <img src="./docs/image/와이어프레임/신고내역조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>신고처리</summary>
   <img src="./docs/image/와이어프레임/신고처리_와이어프레임.png" width=700>
</details>


### 🍀 게시글

<details>
   <summary>본인게시글조회</summary>
   <img src="./docs/image/와이어프레임/본인게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>좋아요누른게시글조회</summary>
   <img src="./docs/image/와이어프레임/좋아요누른게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>타회원게시글조회</summary>
   <img src="./docs/image/와이어프레임/타회원게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글작성</summary>
   <img src="./docs/image/와이어프레임/게시글작성_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글수정</summary>
   <img src="./docs/image/와이어프레임/좋아요누른게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글삭제</summary>
   <img src="./docs/image/와이어프레임/게시글삭제_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글카테고리적용</summary>
   <img src="./docs/image/와이어프레임/게시글카테고리적용_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글해시태그등록</summary>
   <img src="./docs/image/와이어프레임/게시글해시태그등록_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글공개범위설정</summary>
   <img src="./docs/image/와이어프레임/게시글공개범위설정_와이어프레임.png" width=700>
</details>

<details>
   <summary>게시글좋아요</summary>
   <img src="./docs/image/와이어프레임/게시글좋아요_와이어프레임.png" width=700>
</details>


### 🍀 템플릿

<details>
   <summary>템플릿선택</summary>
   <img src="./docs/image/와이어프레임/템플릿선택_와이어프레임.png" width=700>
</details>

<details>
   <summary>템플릿조회</summary>
   <img src="./docs/image/와이어프레임/템플릿조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>템플릿작성</summary>
   <img src="./docs/image/와이어프레임/템플릿작성_와이어프레임.png" width=700>
</details>

<details>
   <summary>템플릿수정</summary>
   <img src="./docs/image/와이어프레임/템플릿수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>템플릿삭제</summary>
   <img src="./docs/image/와이어프레임/템플릿삭제_와이어프레임.png" width=700>
</details>

### 🍀 마이페이지

<details>
   <summary>본인게시글조회</summary>
   <img src="./docs/image/와이어프레임/본인게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>본인템플릿조회</summary>
   <img src="./docs/image/와이어프레임/본인템플릿조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>타회원게시글조회</summary>
   <img src="./docs/image/와이어프레임/타회원게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>타회원템플릿조회</summary>
   <img src="./docs/image/와이어프레임/타회원템플릿조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>좋아요누른게시글조회</summary>
   <img src="./docs/image/와이어프레임/좋아요누른게시글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>좋아요누른댓글조회</summary>
   <img src="./docs/image/와이어프레임/좋아요누른댓글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>내가남긴댓글조회</summary>
   <img src="./docs/image/와이어프레임/내가남긴댓글조회_와이어프레임.png" width=700>
</details>

### 🍀 카테고리

<details>
   <summary>카테고리조회</summary>
   <img src="./docs/image/와이어프레임/카테고리조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>카테고리등록</summary>
   <img src="./docs/image/와이어프레임/카테고리등록_와이어프레임.png" width=700>
</details>

<details>
   <summary>카테고리수정</summary>
   <img src="./docs/image/와이어프레임/카테고리수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>카테고리삭제</summary>
   <img src="./docs/image/와이어프레임/카테고리삭제_와이어프레임.png" width=700>
</details>

### 🍀 댓글

<details>
   <summary>댓글조회</summary>
   <img src="./docs/image/와이어프레임/댓글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>댓글등록</summary>
   <img src="./docs/image/와이어프레임/댓글등록_와이어프레임.png" width=700>
</details>

<details>
   <summary>댓글수정</summary>
   <img src="./docs/image/와이어프레임/댓글수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>댓글삭제</summary>
   <img src="./docs/image/와이어프레임/댓글삭제_와이어프레임.png" width=700>
</details>

<details>
   <summary>대댓글조회</summary>
   <img src="./docs/image/와이어프레임/대댓글조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>대댓글등록</summary>
   <img src="./docs/image/와이어프레임/대댓글등록_와이어프레임.png" width=700>
</details>

<details>
   <summary>대댓글수정</summary>
   <img src="./docs/image/와이어프레임/대댓글수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>대댓글삭제</summary>
   <img src="./docs/image/와이어프레임/대댓글삭제_와이어프레임.png" width=700>
</details>

<details>
   <summary>댓글좋아요</summary>
   <img src="./docs/image/와이어프레임/댓글좋아요_와이어프레임.png" width=700>
</details>

<details>
   <summary>댓글좋아요취소</summary>
   <img src="./docs/image/와이어프레임/댓글좋아요취소_와이어프레임.png" width=700>
</details>

### 🍀 구독

<details>
   <summary>본인을구독한목록조회</summary>
   <img src="./docs/image/와이어프레임/본인을구독한목록 조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>본인이구독한목록조회</summary>
   <img src="./docs/image/와이어프레임/본인이구독한목록조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>구독추가</summary>
   <img src="./docs/image/와이어프레임/구독취소_와이어프레임.png" width=700>
</details>

<details>
   <summary>구독취소</summary>
   <img src="./docs/image/와이어프레임/구독취소_와이어프레임.png" width=700>
</details>

### 🍀 공지사항

<details>
   <summary>공지사항조회</summary>
   <img src="./docs/image/와이어프레임/공지사항조회_와이어프레임.png" width=700>
</details>

<details>
   <summary>공지사항작성</summary>
   <img src="./docs/image/와이어프레임/공지사항작성_와이어프레임.png" width=700>
</details>

<details>
   <summary>공지사항수정</summary>
   <img src="./docs/image/와이어프레임/공지사항수정_와이어프레임.png" width=700>
</details>

<details>
   <summary>공지사항삭제</summary>
   <img src="./docs/image/와이어프레임/공지사항삭제_와이어프레임.png" width=700>
</details>

<br>

## 📍스토리보드

### 🍀 회원관리

<details>
   <summary>회원가입</summary>
   <img src="./docs/image/스토리보드/회원가입_스토리보드.png" width=700>
</details>

<details>
   <summary>약관동의</summary>
   <img src="./docs/image/스토리보드/약관동의_스토리보드.png" width=700>
</details>

<details>
   <summary>로그인</summary>
   <img src="./docs/image/스토리보드/로그인_스토리보드.png" width=700>
</details>

<details>
   <summary>아이디찾기</summary>
   <img src="./docs/image/스토리보드/아이디찾기_스토리보드.png" width=700>
</details>

<details>
   <summary>비밀번호찾기</summary>
   <img src="./docs/image/스토리보드/비밀번호찾기_스토리보드.png" width=700>
</details>

<details>
   <summary>닉네임수정</summary>
   <img src="./docs/image/스토리보드/닉네임수정_스토리보드.png" width=700>
</details>

<details>
   <summary>비밀번호수정</summary>
   <img src="./docs/image/스토리보드/비밀번호수정_스토리보드.png" width=700>
</details>

<details>
   <summary>프로필이미지수정</summary>
   <img src="./docs/image/스토리보드/프로필이미지수정_스토리보드.png" width=700>
</details>

<details>
   <summary>회원탈퇴</summary>
   <img src="./docs/image/스토리보드/회원탈퇴_스토리보드.png" width=700>
</details>

<details>
   <summary>로그아웃</summary>
   <img src="./docs/image/스토리보드/로그아웃_스토리보드.png" width=700>
</details>

### 🍀 관리자

<details>
   <summary>관리자 로그인</summary>
   <img src="./docs/image/스토리보드/관리자로그인_스토리보드.png" width=700>
</details>

<details>
   <summary>회원계정상태변경</summary>
   <img src="./docs/image/스토리보드/회원계정상태변경_스토리보드.png" width=700>
</details>

<details>
   <summary>전체회원조회</summary>
   <img src="./docs/image/스토리보드/전체회원조회_스토리보드.png" width=700>
</details>

### 🍀 신고관리

<details>
   <summary>게시글신고</summary>
   <img src="./docs/image/스토리보드/게시글신고_스토리보드.png" width=700>
</details>

<details>
   <summary>댓글신고</summary>
   <img src="./docs/image/스토리보드/댓글신고_스토리보드.png" width=700>
</details>

<details>
   <summary>템플릿신고</summary>
   <img src="./docs/image/스토리보드/템플릿신고_스토리보드.png" width=700>
</details>

<details>
   <summary>신고내역조회</summary>
   <img src="./docs/image/스토리보드/신고내역조회_스토리보드.png" width=700>
</details>

<details>
   <summary>신고처리</summary>
   <img src="./docs/image/스토리보드/신고처리_스토리보드.png" width=700>
</details>


### 🍀 게시글

<details>
   <summary>본인게시글조회</summary>
   <img src="./docs/image/스토리보드/본인게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>좋아요누른게시글조회</summary>
   <img src="./docs/image/스토리보드/좋아요누른게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>타회원게시글조회</summary>
   <img src="./docs/image/스토리보드/타회원게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글작성</summary>
   <img src="./docs/image/스토리보드/게시글작성_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글수정</summary>
   <img src="./docs/image/스토리보드/좋아요누른게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글삭제</summary>
   <img src="./docs/image/스토리보드/게시글삭제_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글카테고리적용</summary>
   <img src="./docs/image/스토리보드/게시글카테고리적용_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글해시태그등록</summary>
   <img src="./docs/image/스토리보드/게시글해시태그등록_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글공개범위설정</summary>
   <img src="./docs/image/스토리보드/게시글공개범위설정_스토리보드.png" width=700>
</details>

<details>
   <summary>게시글좋아요</summary>
   <img src="./docs/image/스토리보드/게시글좋아요_스토리보드.png" width=700>
</details>


### 🍀 템플릿

<details>
   <summary>템플릿선택</summary>
   <img src="./docs/image/스토리보드/템플릿선택_스토리보드.png" width=700>
</details>

<details>
   <summary>템플릿조회</summary>
   <img src="./docs/image/스토리보드/템플릿조회_스토리보드.png" width=700>
</details>

<details>
   <summary>템플릿작성</summary>
   <img src="./docs/image/스토리보드/템플릿작성_스토리보드.png" width=700>
</details>

<details>
   <summary>템플릿수정</summary>
   <img src="./docs/image/스토리보드/템플릿수정_스토리보드.png" width=700>
</details>

<details>
   <summary>템플릿삭제</summary>
   <img src="./docs/image/스토리보드/템플릿삭제_스토리보드.png" width=700>
</details>

### 🍀 마이페이지

<details>
   <summary>본인게시글조회</summary>
   <img src="./docs/image/스토리보드/본인게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>본인템플릿조회</summary>
   <img src="./docs/image/스토리보드/본인템플릿조회_스토리보드.png" width=700>
</details>

<details>
   <summary>타회원게시글조회</summary>
   <img src="./docs/image/스토리보드/타회원게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>타회원템플릿조회</summary>
   <img src="./docs/image/스토리보드/타회원템플릿조회_스토리보드.png" width=700>
</details>

<details>
   <summary>좋아요누른게시글조회</summary>
   <img src="./docs/image/스토리보드/좋아요누른게시글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>좋아요누른댓글조회</summary>
   <img src="./docs/image/스토리보드/좋아요누른댓글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>내가남긴댓글조회</summary>
   <img src="./docs/image/스토리보드/내가남긴댓글조회_스토리보드.png" width=700>
</details>

### 🍀 카테고리

<details>
   <summary>카테고리조회</summary>
   <img src="./docs/image/스토리보드/카테고리조회_스토리보드.png" width=700>
</details>

<details>
   <summary>카테고리등록</summary>
   <img src="./docs/image/스토리보드/카테고리등록_스토리보드.png" width=700>
</details>

<details>
   <summary>카테고리수정</summary>
   <img src="./docs/image/스토리보드/카테고리수정_스토리보드.png" width=700>
</details>

<details>
   <summary>카테고리삭제</summary>
   <img src="./docs/image/스토리보드/카테고리삭제_스토리보드.png" width=700>
</details>

### 🍀 댓글

<details>
   <summary>댓글조회</summary>
   <img src="./docs/image/스토리보드/댓글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>댓글등록</summary>
   <img src="./docs/image/스토리보드/댓글등록_스토리보드.png" width=700>
</details>

<details>
   <summary>댓글수정</summary>
   <img src="./docs/image/스토리보드/댓글수정_스토리보드.png" width=700>
</details>

<details>
   <summary>댓글삭제</summary>
   <img src="./docs/image/스토리보드/댓글삭제_스토리보드.png" width=700>
</details>

<details>
   <summary>대댓글조회</summary>
   <img src="./docs/image/스토리보드/대댓글조회_스토리보드.png" width=700>
</details>

<details>
   <summary>대댓글등록</summary>
   <img src="./docs/image/스토리보드/대댓글등록_스토리보드.png" width=700>
</details>

<details>
   <summary>대댓글수정</summary>
   <img src="./docs/image/스토리보드/대댓글수정_스토리보드.png" width=700>
</details>

<details>
   <summary>대댓글삭제</summary>
   <img src="./docs/image/스토리보드/대댓글삭제_스토리보드.png" width=700>
</details>

<details>
   <summary>댓글좋아요</summary>
   <img src="./docs/image/스토리보드/댓글좋아요_스토리보드.png" width=700>
</details>

<details>
   <summary>댓글좋아요취소</summary>
   <img src="./docs/image/스토리보드/댓글좋아요취소_스토리보드.png" width=700>
</details>

### 🍀 구독

<details>
   <summary>본인을구독한목록조회</summary>
   <img src="./docs/image/스토리보드/본인을구독한목록조회_스토리보드.png" width=700>
</details>

<details>
   <summary>본인이구독한목록조회</summary>
   <img src="./docs/image/스토리보드/본인이구독한목록조회_스토리보드.png" width=700>
</details>

<details>
   <summary>구독추가</summary>
   <img src="./docs/image/스토리보드/구독취소_스토리보드.png" width=700>
</details>

<details>
   <summary>구독취소</summary>
   <img src="./docs/image/스토리보드/구독취소_스토리보드.png" width=700>
</details>

### 🍀 공지사항

<details>
   <summary>공지사항조회</summary>
   <img src="./docs/image/스토리보드/공지사항조회_스토리보드.png" width=700>
</details>

<details>
   <summary>공지사항작성</summary>
   <img src="./docs/image/스토리보드/공지사항작성_스토리보드.png" width=700>
</details>

<details>
   <summary>공지사항수정</summary>
   <img src="./docs/image/스토리보드/공지사항수정_스토리보드.png" width=700>
</details>

<details>
   <summary>공지사항삭제</summary>
   <img src="./docs/image/스토리보드/공지사항삭제_스토리보드.png" width=700>
</details>

<br>

## [📍Test Case](https://docs.google.com/spreadsheets/d/1_wK79gFhs6kM5uMWQg5YFL_vusLwLg0lMSjNjLFVfWg/edit?gid=1748785766#gid=1748785766)

![WBS.png](docs/image/WBS/WBS.png)


<br>

## 📍 결과화면

### 🫧 Category

<details>
   <summary>카테고리 등록</summary>
   <img src="docs/result/admin/카테고리생성-1.gif" width=700>
</details>

<details>
   <summary>카테고리 수정</summary>
   <img src="docs/result/admin/카테고리 수정-1.gif" width=700>
</details>

<details>
   <summary>카테고리 삭제</summary>
   <img src="docs/result/admin/카테고리삭제-1.gif" width=700>
</details>

### 🫧 Comment
<details>
   <summary>댓글쓰기</summary>
   <img src="docs/result/admin/댓글쓰기.gif" width=700>
</details>

### Member

<details>
   <summary>이메일인증 예외처리</summary>
   <img src="docs/result/admin/이메일예외처리.gif" width=700>
</details>

<details>
   <summary>회원가입 이메일 받기</summary>
   <img src="docs/result/admin/회원가입 이메일 받기-1.gif" width=700>
</details>

<details>
   <summary>회원가입</summary>
   <img src="docs/result/admin/회원가입완료-1.gif" width=700>
</details>

<details>
   <summary>일반 회원 로그인</summary>
   <img src="docs/result/admin/일반 회원 로그인-1.gif" width=700>
</details>

<details>
   <summary>비밀번호 불일치 </summary>
   <img src="docs/result/admin/비밀번호불일치-1.gif" width=700>
</details>

<details>
   <summary>회원 이메일 찾기</summary>
   <img src="docs/result/admin/회원 이메일 찾기-1.gif" width=700>
</details>

<details>
   <summary>비밀번호 찾기</summary>
   <img src="docs/result/admin/비밀번호 찾고 재로그인-1.gif" width=700>
</details>

<details>
   <summary>로그아웃</summary>
   <img src="docs/result/admin/회원 로그아웃-1.gif" width=700>
</details>

### 🫧 Myactivity

<details>
   <summary>내가 작성한 댓글 조회</summary>
   <img src="docs/result/admin/내가작성한댓글-1.gif" width=700>
</details>

<details>
   <summary>내가 좋아요한 게시글 조회</summary>
   <img src="./docs/t글stcase/admin/내가좋아요한게시-1.gif" width=700>
</details>

<details>
   <summary>내가 좋아요한 댓글 조회</summary>
   <img src="docs/result/admin/내가좋아요한댓글-1.gif" width=700>
</details>

### Mypage

<details>
   <summary>내가 작성한 게시글 조회</summary>
   <img src="docs/result/admin/내가작성한게시글-1.gif" width=700>
</details>

<details>
   <summary>내가 작성한 템플릿 조회</summary>
   <img src="docs/result/admin/내가작성한템플릿-1.gif" width=700>
</details>

<details>
   <summary>다른 사람의 마이페이지 방문</summary>
   <img src="docs/result/admin/다른사람의마이페이지방문-1.gif" width=700>
</details>

<details>
   <summary>다른사람이 작성한 게시글 조회</summary>
   <img src="docs/result/admin/다른사람이작성한게시글조회-1.gif" width=700>
</details>

<details>
   <summary>다른사람이 작성한 템플릿 조회</summary>
   <img src="docs/result/admin/다른사람이작성한템플릿조회-1.gif" width=700>
</details>

<details>
   <summary>팔로워 조회</summary>
   <img src="docs/result/admin/팔로워조회-1.gif" width=700>
</details>

<details>
   <summary>팔로잉 조회</summary>
   <img src="docs/result/admin/팔로잉조회-1.gif" width=700>
</details>

### Post
<details>
   <summary>게시글 작성</summary>
   <img src="docs/result/admin/글쓰기.gif" width=700>
</details>

<details>
   <summary>전체 게시글 조회</summary>
   <img src="docs/result/admin/게시글전체.gif" width=700>
</details>

<details>
   <summary>게시글 좋아요순 조회</summary>
   <img src="docs/result/admin/게시글좋아요.gif" width=700>
</details>

<details>
   <summary>게시글 최신순 조회</summary>
   <img src="docs/result/admin/게시글최신순.gif" width=700>
</details>

### Template
<details>
   <summary>템플릿 전체 조회</summary>
   <img src="docs/result/admin/템플릿전체.gif" width=700>
</details>

<details>
   <summary>템플릿 사용순 조회</summary>
   <img src="docs/result/admin/템플릿사용순.gif" width=700>
</details>

<details>
   <summary>템플릿 최신순 조회</summary>
   <img src="docs/result/admin/템플릿최신순.gif" width=700>
</details>

### 🫧 Setting

<details>
   <summary>회원 설정페이지 조회</summary>
   <img src="docs/result/admin/설정방문.gif" width=700>
</details>

<details>
   <summary>설정페이지 내 회원탈퇴</summary>
   <img src="docs/result/admin/회원탈퇴-1 복사본.gif" width=700>
</details>

<details>
   <summary>회원탈퇴시 비밀번호 작성 예외처리 </summary>
   <img src="docs/result/admin/회원탈퇴비밀번호틀림-1 복사본.gif" width=700>
</details>

<br>

<hr>

<br>

# 4. Peer Review
### 주아현
| Team Member | Peer Review |
|-------------|-------------|
| 강이도은      |             |
| 곽우석       |             |
| 이상모       |             |
| 정동한       |             |
| 한윤상       |             |

### 강이도은
| Team Member | Peer Review |
|-------------|-------------|
| 주아현       |             |
| 곽우석       |             |
| 이상모       |             |
| 정동한       |             |
| 한윤상       |             |

### 곽우석
| Team Member | Peer Review |
|-------------|------------|
| 주아현       |            |
| 강이도은      |            |
| 이상모       |            |
| 정동한       |            |
| 한윤상       |            |

### 이상모
| Team Member | Peer Review |
|------------|-------------|
| 주아현        |             |
| 강이도은       |             |
| 곽우석        |             |
| 정동한        |             |
| 한윤상        |             |

### 정동한
| Team Member | Peer Review |
|-------------|-------------|
| 주아현         |             |                                                                                                                                                                                                                                                                                  |
| 강이도은        |             |
| 곽우석         |             |     
| 이상모         |             |
| 한윤상         |             |

### 한윤상
| Team Member | Peer Review |
|-------------|-------|
| 주아현       ||
| 강이도은      ||
| 곽우석       ||
| 이상모       ||
| 정동한       ||
