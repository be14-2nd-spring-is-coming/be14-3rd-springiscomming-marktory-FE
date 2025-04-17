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


### 1️⃣ 논리모델링
<img src="https://github.com/user-attachments/assets/bf47f0ca-7cf4-49d7-92cd-6c14674ebc37" >

### 2️⃣  물리모델링
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

![WBS.png](docs/image/testcase/테스트케이스.png)


<br>

## 결과화면

### 🍏 admin
<details>
   <summary>공지사항삭제</summary>
   <img src="./docs/result/admin/공지사항삭제-1.gif" width=700>
</details>

<details>
   <summary>공지사항조회</summary>
   <img src="./docs/result/admin/공지사항조회-1.gif" width=700>
</details>

<details>
   <summary>관리자로그아웃</summary>
   <img src="./docs/result/admin/관리자로그아웃-1.gif" width=700>
</details>

<details>
   <summary>관리자페이지방문</summary>
   <img src="./docs/result/admin/관리자페이지방문-1.gif" width=700>
</details>

<details>
   <summary>신고관리회원조회</summary>
   <img src="./docs/result/admin/신고관리회원조회-1.gif" width=700>
</details>

<details>
   <summary>회원이용제한</summary>
   <img src="./docs/result/admin/회원이용제한-1.gif" width=700>
</details>

### 🍏 Category

<details>
   <summary>카테고리 등록</summary>
   <img src="./docs/result/category/카테고리생성-1.gif" width=700>
</details>

<details>
   <summary>카테고리 수정</summary>
   <img src="./docs/result/category/카테고리 수정-1.gif" width=700>
</details>

<details>
   <summary>카테고리 삭제</summary>
   <img src="./docs/result/category/카테고리삭제-1.gif" width=700>
</details>

### 🍏 Comment
<details>
   <summary>댓글쓰기</summary>
   <img src="./docs/result/comment/댓글쓰기.gif" width=700>
</details>

### 🍏 email_find
<details>
   <summary>비밀번호 찾기</summary>
   <img src="./docs/result/pw_find/비밀번호 찾고 재로그인-1.gif" width=700>
</details>

### 🍏 pw_find
<details>
   <summary>비밀번호찾고</summary>
   <img src="./docs/result/email_find/회원 이메일 찾기-1.gif" width=700>
</details>

### 🍏 login
<details>
   <summary>관리자로그인</summary>
   <img src="./docs/result/login/관리자 로그인-1.gif" width=700>
</details>

<details>
   <summary>비밀번호불일치</summary>
   <img src="./docs/result/login/비밀번호불일치-1.gif" width=700>
</details>

<details>
   <summary>일반회원로그인</summary>
   <img src="./docs/result/login/일반 회원 로그인-1.gif" width=700>
</details>

<details>
   <summary>비밀번호 찾기</summary>
   <img src="./docs/result/pw_find/비밀번호 찾고 재로그인-1.gif" width=700>
</details>

### 🍏 logout
<details>
   <summary>회원로그아웃</summary>
   <img src="./docs/result/logout/회원 로그아웃-1.gif" width=700>
</details>

### 🍏 signup
<details>
   <summary>이메일예외처리</summary>
   <img src="./docs/result/signup/이메일예외처리.gif" width=700>
</details>

<details>
   <summary>회원가입완료</summary>
   <img src="./docs/result/signup/회원가입 완료-1.gif" width=700>
</details>

<details>
   <summary>회원가입 이메일 받기</summary>
   <img src="./docs/result/signup/회원가입 이메일 받기-1.gif" width=700>
</details>

### 🍏 myactivity
<details>
   <summary>내가 작성한 댓글</summary>
   <img src="./docs/result/myactivity/내가작성한댓글-1.gif" width=700>
</details>

<details>
   <summary>내가좋아요한게시글</summary>
   <img src="./docs/result/myactivity/내가좋아요한게시글-1.gif" width=700>
</details>

<details>
   <summary>내가좋아요한댓글</summary>
   <img src="./docs/result/myactivity/내가좋아요한댓글-1.gif" width=700>
</details>

### 🍏 mypage

<details>
   <summary>내가 작성한 게시글 조회</summary>
   <img src="./docs/result/mypage/내가작성한게시글-1.gif" width=700>
</details>

<details>
   <summary>내가 작성한 템플릿 조회</summary>
   <img src="./docs/result/mypage/내가작성한템플릿-1.gif" width=700>
</details>

<details>
   <summary>다른 사람의 마이페이지 방문</summary>
   <img src="./docs/result/mypage/다른사람의마이페이지방문-1.gif" width=700>
</details>

<details>
   <summary>다른사람이 작성한 게시글 조회</summary>
   <img src="./docs/result/mypage/다른사람이작성한게시글조회-1.gif" width=700>
</details>

<details>
   <summary>다른사람이 작성한 템플릿 조회</summary>
   <img src="./docs/result/mypage/다른사람이작성한템플릿조회-1.gif" width=700>
</details>

<details>
   <summary>팔로워 조회</summary>
   <img src="./docs/result/mypage/팔로워조회-1.gif" width=700>
</details>

<details>
   <summary>팔로잉 조회</summary>
   <img src="./docs/result/mypage/팔로잉조회-1.gif" width=700>
</details>

### 🍏 Post
<details>
   <summary>게시글 작성</summary>
   <img src="./docs/result/post/글쓰기.gif" width=700>
</details>

<details>
   <summary>전체 게시글 조회</summary>
   <img src="./docs/result/post_select/게시글전체.gif" width=700>
</details>

<details>
   <summary>게시글 좋아요순 조회</summary>
   <img src="./docs/result/post_select/게시글좋아요.gif" width=700>
</details>

<details>
   <summary>게시글 최신순 조회</summary>
   <img src="./docs/result/post_select/게시글최신순.gif" width=700>
</details>

### 🍏 Template
<details>
   <summary>템플릿 전체 조회</summary>
   <img src="./docs/result/template_select/템플릿전체.gif" width=700>
</details>

<details>
   <summary>템플릿 사용순 조회</summary>
   <img src="./docs/result/template_select/템플릿사용순.gif" width=700>
</details>

<details>
   <summary>템플릿 최신순 조회</summary>
   <img src="./docs/result/template_select/템플릿최신순.gif" width=700>
</details>

### 🍏 Setting

<details>
   <summary>회원 설정페이지 조회</summary>
   <img src="./docs/result/setting/설정방문-1.gif" width=700>
</details>

<details>
   <summary>설정페이지 내 회원탈퇴</summary>
   <img src="./docs/result/setting/회원탈퇴-1 복사본.gif" width=700>
</details>

<details>
   <summary>회원탈퇴시 비밀번호 작성 예외처리 </summary>
   <img src="./docs/result/setting/회원탈퇴비밀번호틀림-1 복사본.gif" width=700>
</details>

<br>

<hr>

<br>

# 4. Peer Review
### 주아현
| Team Member | Peer Review |
|-------------|-------------|
| 강이도은      | 본인 컨디션보다 팀원들 컨디션을 챙겨주고, 피곤하고 힘들어도 미소를 유지한 채 따뜻하게 대해주셔서 감사합니다. 덕분에 큰 힘이 되었습니다. 또, 팀원들의 소통이 원활하지 않을 때 먼저 나서서 정리하고 팀의 중심에 서서 소통해 주셔서 큰 다툼 없이 프로젝트가 흘러갔습니다. 항상 자세한 내용까지 기록해 주셔서 모든 프로젝트의 변동 사항을 알 수 있었고, 잦은 변동 사항으로 혼동이 왔을 때 바로잡아주셔서 감사합니다. 프로젝트의 전반적인 흐름을 인지하고 계셔서 의지가 많이 되었고, 도움도 많이 받았습니다. 최고!!             |
| 곽우석       | 아현 님께서는 팀원들 간의 관계를 위해 항상 노력해주셨습니다. 팀원들에게 요즘 힘든 건 없는지, 잘 지내고 있는지 자주 물어봐 주시며 분위기를 따뜻하게 만들어 주셨습니다. 또 어려운 관리자 페이지 작업도 책임감 있게 맡아 멋지게 마무리해 주셔서 정말 든든했어요. 함께하면서 배울 점이 많았던 우리 조장님 Kasey, 진심으로 감사드립니다!            |
| 이상모       | 이번 프로젝트에서 아현님은 팀의 중심 역할을 확실하게 해주셨습니다. 공지사항 구현이라는 기능적인 부분에서도 안정적으로 마무리하셨고, 회의나 일정 중간중간 따뜻한 말 한마디로 분위기를 잘 이끌어주셨던 모습이 인상 깊었습니다. 특히 팀원 모두를 아우르는 포용력 덕분에 각자의 역할에 더 집중할 수 있었던 것 같습니다. 프로젝트 중반 체력적으로도 쉽지 않았던 상황에서도 끝까지 팀 전체의 방향을 놓지 않고 챙겨주셔서 고맙다는 말을 꼭 전하고 싶습니다.            |
| 정동한       | 이번 프런트엔드 프로젝트에서도, 항상 팀원들을 이해하는 마음과 소통에서 최선을 다해준 고마운 팀장님입니다. 팀장님이 중간 조율로 인해 스트레스도 많이 받으셨을 거 같은데, 정말, 열심히 하는 자세와 소통 능력은 우리 팀이 잘 돌아갈 수 있도록 아현 님의 능력 덕분이었습니다. PM으로서 가능성이 높은 멋진 PM! 주아현 화이팅. 굳세어라 주아현.            |
| 한윤상       | 항상 팀을 위한 책임감을 잃지 않고, 맡은 업무를 끝까지 하려고 노력하는 모습이 매우 인상적이었습니다. 프로젝트를 진행하면서 밤을 새워서라도 모든 일을 마무리하려는 자세는 팀원들에게 큰 동기부여가 되었고, 문서 작업같은 귀찮을 수 있는 일들도 주도적으로 나서서 해결해 주셨습니다. 덕분에 팀 전체가 믿고 따를 수 있었고, 흔들림 없이 프로젝트를 이끌어갈 수 있었습니다. 묵묵하지만 열정적인 리더십으로 팀을 하나로 모아준, 정말 든든한 팀장이었습니다.            |

### 강이도은
| Team Member | Peer Review |
|-------------|-------------|
| 주아현       | ‘주밀정치’ 세밀하고 정교하게, 빈틈없이 완벽하게 다듬는다는 뜻의 사자성어처럼, UI 설계와 Vue 기반 프론트엔드 구조를 체계적으로 구축하며 전체 프로젝트의 틀을 꼼꼼하게 잡아주었습니다. 세심함과 집중력 덕분에 팀 전체가 방향을 정립하는 데 큰 도움이 되었고, 안정적인 기반을 마련해준 고마운 존재였습니다.            |
| 곽우석       |도은님은 뛰어난 미적 감각을 바탕으로 피그마 작업에서 큰 도움을 주셨습니다. 제가 부족했던 디자인 부분에서 많은 것을 배울 수 있었고, 작업을 마친 뒤에도 다른 팀원들의 업무를 도와주며 배려심 있는 모습을 보여주셨습니다. 프로젝트 기간 동안 맡은 역할에 끝까지 열정을 가지고 책임감 있게 마무리하시는 모습이 특히 인상 깊었습니다. 모든 작업을 꼼꼼하게 처리하는 모습에서 많은 것을 느꼈고, 이번 프로젝트를 통해 새롭게 생긴 저의 롤모델 중 한 분입니다.             |
| 이상모       | 도은님은 이번 프로젝트에서 문서화나 피그마 작업을 통해 팀 전체의 흐름을 잡아주는 데 큰 역할을 해주셨습니다. 본인이 맡은 영역뿐 아니라, 다른 파트에도 자연스럽게 관심을 가지며 전체 구조를 함께 고민해주는 모습이 인상 깊었습니다. 개발 외적인 부분에서도 기준이 확실했고, 작업 하나하나에서 꼼꼼하고 세심한 태도가 느껴졌습니다. 특히 기억에 남는 건 팀원 간의 갈등이 있었던 상황에서, 그걸 회피하지 않고 직접 소통하려는 모습을 보여주셨던 점입니다. 예민해질 수 있는 상황에서도 차분하게 정리해 나가며 오히려 팀 분위기를 더 단단하게 만들어주셨습니다. 함께 일하면서 신뢰가 깊어졌고, 여러모로 많이 배울 수 있었던 팀원입니다. |
| 정동한       | UI 디자인의 신이라 부를 수 있을 것 같습니다. 자리를 부득이하게 비우게 되었는데, 그 점에서 UI 설계에 많이 빠지게 되어서 죄송했는데 오히려 내가 끼면 디자인이 망쳐질 거 같다는 느낌처럼 디자인에서 팀이 가져가고 싶은 것을 전부 가져가면서 이쁜 디자인으로 피그마를 열었을 때 눈이 확 갔습니다 정말 수고많았습니다. 열심히 UI 만들어주던 모습 감명 깊었습니다. 같이 한다는 약속 전 지켰어요 D~            |
| 한윤상       | 항상 자신의 업무를 빠르고 완성도 높게 마무리하며, 팀 전체의 진행 속도를 자연스럽게 끌어올렸습니다. 개인적인 일정도 뒤로 미루고 프로젝트 완성을 위해 밤낮없이 몰입하는 모습이 매우 인상 깊었으며, 사소한 디테일까지 꼼꼼히 챙기며 프로젝트의 전체적인 완성도를 높이는 데 큰 역할을 했습니다. 특히 프론트 디자인 초안을 가장 먼저 구성하고 전체적인 구조와 흐름을 잡아준 덕분에 이후 작업이 훨씬 수월하게 진행될 수 있었고, 디자인 감각도 뛰어나 화면 구성이나 UI적인 측면에서도 많은 참고가 되었습니다. 무엇보다 본인의 업무를 빠르게 마친 후에도 여유를 가지기보다는, 다른 팀원들의 업무를 자연스럽게 도와주셔서 감사했습니다. 배려심 깊고 책임감 있는 태도 덕분에 원활하게 프로젝트 진행을 할 수 있었습니다.            |

### 곽우석
| Team Member | Peer Review |
|-------------|------------|
| 주아현       | '적극진취' 적극적으로 나아가고 새로움을 받아들인다는 의미처럼, 프로젝트 내내 모르는 부분은 주저하지 않고 질문하고, 먼저 다가가 소통하며 능동적인 태도로 팀 분위기를 이끌었습니다. 적극적인 참여와 긍정적인 자세가 인상 깊었고, 모두가 함께 성장할 수 있는 환경을 만들어 주었습니다.|
| 강이도은      | 저번 평가에서도 언급했지만, 먼저, 혼자서 문제를 해결해 보려는 자세가 정말 멋진 팀원입니다. 어려움이 생겼을 때에는 포기하지 않고 끝까지 고민해 보는 끈기를 가지고 있으며, 문제 해결을 위해서는 질문을 아끼지 않고 적극적으로 배우려는 자세를 지니고 있습니다. 덕분에 저도 같이 옆에서 불타올라 열정적으로 프로젝트에 임할 수 있었습니다. 또, 팀 내의 현재 상황을 파악하려 하고, 필요하면 먼저 다가서서 소통하려 했으며, 특유의 장난스러움으로 예민할 수 있는 상황을 유연하게 만들어 주는 소통왕입니다. 따봉           |
| 이상모       | 우석님은 팀 안에서 소통을 주도해주는 역할을 해주셨습니다. 회의 중간중간 자연스럽게 이야기를 이어가거나, 가벼운 농담으로 분위기를 환기해주는 순간들이 많았고, 그 덕분에 부담스러운 상황에서도 팀원들이 조금 더 편하게 의견을 낼 수 있었던 것 같습니다. 설정 페이지도 맡은 역할 안에서 책임감 있게 잘 구현해주셨고, 특히 헷갈릴 수 있는 흐름이나 정리가 필요한 부분에서 중심을 잘 잡아주셨습니다.           |
| 정동한       | 2번을 잇따른 프로젝트에서 열심히 하는 자세를 보며 배울 점이 많았던 팀원입니다. 부족하다고 말하면서, 본인이 맡은 책임감에서 확실하게 일이 끝내고자 하는 의지와 팀원들을 도움을 주고자 하는 자세는 오히려 기본적인 자세이지만, 안 지켜질 수 있는 부분이라고 생각합니다. 이러한 자세를 많이 배웠고 끝까지 유지하면 저보다 훨씬 더 성장 할 수 있다는 생각을 하게 만들었습니다.           |
| 한윤상       | 팀 분위기가 다소 무거워질 때마다 농담을 던지며 분위기를 전환해주어, 팀의 활력을 불어넣어 주었습니다. 맡은 업무에 있어서는 끝까지 책임감을 가지고 마치려 하였고, 모르는 부분이 생겨도 스스로 끝까지 파고들어 해결하려는 모습을 보여주셨습니다. 또한, 필요한 부분에서는 주저 없이 질문하고 소통하려는 자세가 팀원들에게 긍정적인 자극이 되었습니다.           |

### 이상모
| Team Member | Peer Review |
|------------|-------------|
| 주아현        | '묵이성지' 말없이 묵묵히 자신의 일을 완수한다는 뜻처럼, 마크다운 기반의 글쓰기 기능을 Vue로 차분히 구현해내며 항상 묵묵히 그러나 맡은 일을 해내기위해 노력하신 모습이 인상깊었습니다. 상모님 덕에 프론트엔드의 틀을 잡을 수 있어 프로젝트가 원활히 진행될 수 있었습니다.            |
| 강이도은       | 항상 묵묵히 저희 프로젝트의 시작을 먼저 해주시고, 큰 틀을 잡아주셔서 감사합니다. 덕분에 팀원들이 감을 잡고 틀에 맞춰 개발할 수 있었습니다. 마크토리의 핵심 기능인 마크다운 언어를 활용한 글쓰기를 맡아주셨는데, 어려운 부분임에도 완벽. 구현해 주셨습니다. 다양한 라이브러리가 있었는데, 저희 프로젝트에 맞게 깊이 생각한 모습이 느껴졌습니다. 또 , 발표 당일에는 라우터 설정이 꼬여 다들 허둥지둥거렸는데 빠르게 방법을 찾고 ngrox을 사용하여 해결해 주신 모습이 멋있었습니다!            |
| 곽우석        | 프론트엔드 작업에 대해 상모님을 보며 정말 많이 배울 수 있었습니다. 피곤한 상황 속에서도 끝까지 자리를 지키며 작업을 마무리하시는 모습이 인상 깊었고, 특히 집이 멀어서 힘드셨을 텐데도 책임감 있게 임해주셔서 감사했습니다.            |
| 정동한        | 어려운 부분인 게시글 작성에 에디터 라이브러리를 맡아주셔서 정말 감사했습니다. 확실히 코드를  보며 프론트엔드 개발을 이렇게 해야하는 거구나 라는 시야를 넓게 해주셨습니다. 항상 팀원들이 편하게 실행할 수 있는 실행 환경을 만들어주시는 것도 감사하다고 전하고 싶습니다.            |
| 한윤상        | 기술적으로 어려운 구현 부분이 나올 때마다 주저하지 않고 먼저 나서서 맡아주어 큰 도움이 되었습니다. 알고 있는 지식의 폭도 넓고 이해도 깊어, 개발 전반에 걸쳐 팀원들의 의사결정과 작업에 실질적인 도움을 주었습니다. 복잡한 문제를 차분히 분석하고 해결해 나가는 모습 덕분에 프로젝트의 완성도가 한층 더 높아졌습니다. 팀 전체의 기술적 중심을 잡아주셔서 감사했습니다. |

### 정동한
| Team Member | Peer Review |
|-------------|-------------|
| 주아현         | '극기봉공' 자신을 이겨내고 팀을 위해 헌신한다는 뜻처럼, 프론트와 백엔드 연동이라는 어려운 작업에도 끈기 있게 임하며, 항상 “해보겠다”는 태도로 문제에 도전하는 모습이 큰 귀감이 되었습니다. 헌신적인 자세와 기술에 대한 책임감이 프로젝트 완성도를 높이는 데 결정적인 역할을 했습니다.            |
| 강이도은        | 프론트 개발 일정이 빠듯해 백엔드 연동을 포기하고 json server로만 구현하려다, 동한님의 한 번 해볼게요. 라는 말에 일부 백엔드 연동을 시도했습니다. 전체는 아니더라도 로그인, 회원가입, SMTP 연동을 해주셔서 완성도 있는 마크토리가 되었습니다. 매번 못하겠다, 안하겠다는 말없이 본인 일에 책임감을 강하게 가지고 있다고 느꼈으며, 밤을 새우면서도 할 수 있을 때까지 시도하고 본인이 목표치한 만큼 해내는 모습을 보여줬습니다. 본인이 맡은 부분에 대한 이해도도 높아 팀원들이나 발표 시 질문에도 잘 답변해주었습니다. 백엔드 담당 Dong 최고였습니다!            |
| 곽우석         | ‘백엔드의 신’ 동한님과 함께 프로젝트를 하며 정말 많은 것을 배울 수 있었습니다. 제가 모르는 부분에 대해 질문할 때마다 늘 자기 일처럼 친절하게 설명해 주셨고, 정말 모르는 게 없으신 분이라는 생각이 들었습니다. 특히 동한님이 구현하신 로그인과 회원가입 기능 덕분에 프로젝트 결과물이 훨씬 풍성해질 수 있었습니다. 실력도 뛰어나고 성격까지 좋은 Dong 샘난다.. 샘나..            |     
| 이상모         | 동한님은 백엔드 전반을 이끌면서 회원가입과 로그인, 보안 설정 같은 핵심 기능을 책임지고 완성도 있게 마무리하셨습니다. 기술적으로 어려운 부분이 많았을 텐데, 항상 묵묵하게 해결해나가는 모습이 인상적이었고, 덕분에 전체 시스템이 안정적으로 동작할 수 있었습니다. 평소 밝은 이미지 덕분에 팀 분위기도 한결 부드러웠고, 기술적인 부분에서도 많이 배울 수 있는 시간이었습니다.            |
| 한윤상         | 회원 파트를 백엔드와 연동하며 프로젝트의 핵심 기능 중 하나를 안정적으로 구현해주었습니다. 꼭 해야 하는 일이 아니었음에도 자발적으로 나서서 맡아주는 모습에서 프로젝트에 대한 애정과 책임감을 느낄 수 있었습니다. 백엔드 작업을 진행하면서도 프론트 작업까지 병행하며 빠르게 업무를 마무리했고, 그 과정에서 다른 팀원들을 도와주는 모습이 매우 인상적이었습니다. 항상 밝고 긍정적인 태도로 팀의 분위기가 쳐지지 않게 해주셨습니다.  |

### 한윤상
| Team Member | Peer Review |
|-------------|-------|
| 주아현       |'인고극난' 괴로움을 참고 어려움을 이겨낸다는 의미처럼, 건강이 좋지 않은 상황 속에서도 맡은 발표를 끝까지 책임지며 궂은일도 마다하지 않고 묵묵히 해내는 모습에 책임감을 느낄 수 있었습니다. 흔들림 없이 맡은 부분을 성실하게 처리하는 모습은 팀에 큰 신뢰감을 주었고, 내실 있는 협업의 좋은 예가 되었습니다.|
| 강이도은      |figma interaction 설명을 미흡하게 알려주었는데, 금방 숙지하고 제가 모르는 부분까지 공부하고 공유해 주셔서 감사합니다. UI 설계 시 같이 밤을 새가며 도움을 주셔서 빠르고 좋은 퀄리티로 완성할 수 있었습니다. 발표 전날, 몸이 아팠음에도 밤을 새우면서 본인이 맡은 부분을 끝까지, 책임감 있게 구현하고 팀의 전체적인 개발 디테일도 잡아주었습니다. 또, 발표 자료가 늦어졌는데도 발표를 유연하고 원활하게 잘 해주셨습니다. 발표 시 저희가 만든 프로젝트의 디테일을 꼼꼼하게 짚어주셔서 팀과 프로젝트의 애정이 느껴졌고 큰 감동이었습니다.|
| 곽우석       |“이 분은 쉬는 시간이 없나…”라는 생각이 들 정도로, 정말 열정적이고 책임감 있는 분이었습니다. 맡은 일에 항상 최선을 다하셨고, 작업 중에도 꼼꼼함과 집중력이 눈에 띄었습니다. 몸이 아프신 상황에서도 작업을 멈추지 않으시고, 다음 날 발표까지 완벽하게 준비해 오셔서 정말 멋진 발표를 보여주셨습니다. 이번 프로젝트를 통해 새롭게 생긴 저의 롤모델 중 한 분입니다.|
| 이상모       |윤상님은 말없이 묵묵히 자기 일을 끝까지 책임지는 분이었습니다. 마이페이지 구현은 구조도 잘 짜여 있었고, 디테일도 놓치지 않으려는 꼼꼼함이 느껴졌습니다. 발표 때도 내용 전달이 명확했고, 정돈된 톤으로 전체 흐름을 잘 정리해주셔서 프로젝트를 보는 시선이 더 신뢰감 있게 느껴졌습니다. 눈에 잘 띄지는 않지만 팀이 안정적으로 흘러가도록 도와주는 사람이었다고 생각합니다.|
| 정동한       |프론트엔드 UI를 실제 구현할 때 작업 속도에서 엄청나게 빠른 부분으로 정말 듬직한 팀원이었다고 말할 수 있는 팀원이었습니다. 아픈데도, 계속해서 PR을 날려주는 자세 또한, 난 아직 협업의 자세가 부족하다는 것을 느끼게 해주었고 발표에서 계속해서 프로젝트를 하다 보니 까먹은 부분도 많았는데, 팀원들이 노력한 부분을 최대한 언급해 주면서 팀원들의 고생을 알아주셔서 감사하다고 전하고 싶습니다.|
