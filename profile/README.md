

# Techeer Market
<img width="980" alt="techeermarkte" src="https://github.com/Techeer-market/.github/assets/95288297/7f17d217-85a3-4f24-a5a1-c77ee8b8d6a0">


<br>

## 🎀 Introduction

테커 내 중고거래를 위한 웹 플랫폼, 테커 마켓 👩🏻‍🌾
<br>
<br>

<br>

## 📚 Tech Stack

| Frontend | Backend | Database&Storage | DevOps |
| --- | --- | --- | --- |
| <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white"><br><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"><br><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"><br><img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white"><br><img src="https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white"><br> | <br><img src="https://img.shields.io/badge/Postman-FF6600?style=for-the-badge&logo=Postman&logoColor=white"><br><img src="https://img.shields.io/badge/SpringBoot-37814A?style=for-the-badge&logo=SpringBoot&logoColor=white"><br> | <img src="https://img.shields.io/badge/PostgreSQL-blue?style=for-the-badge&logo=PostgreSQL&logoColor=white"><br><img src="https://img.shields.io/badge/AWS-S3Bucket-yellow?style=for-the-badge&logo=Amazon"><br> | <img src="https://img.shields.io/badge/AWS-ElasticBeanstalk-orange?style=for-the-badge&logo=AWS-ElasticBeanstalk&logoColor=white"><br><img src="https://img.shields.io/badge/AWS-EC2-D1743D?style=for-the-badge&logo=AWS-EC2&logoColor=white"><br> |


<br>

## ⛺️ ERD

![TecheerMacket drawio](https://github.com/Techeer-market/.github/assets/95288297/90b69081-2ea4-468b-80a8-b9f548b80fe7)


<br>

### 🔍 기능 구현 범위

- **회원**
    - 회원 가입 / 로그인
    - 마이페이지
        - 판매 / 구매 내역 리스트 확인
        - 좋아요 게시물 목록
        - 판매자 정보
- **중고 거래 시스템**
    - 중고거래 게시물 글쓰기
        - 판매할 물건 사진 업로드
        - 게시물 내용 (제목, 가격, 사진, 내용, 원하는 거래 위치)
    - 구매
        - 채팅 (판매자, 구매자 간 1:1 채팅)
        - 게시물 상태 (판매중→예약중→구매완료)
        - 상세 게시물 페이지
    - 상품 검색 (키워드)

<br>

## 💻 Installation Process

> <b>Docker repository clone </b>
> 

```
git clone --recursive <https://github.com/Techeer-market/Frontend.git>
git clone --recursive <https://github.com/Techeer-market/Backend.git>
```

<br>

> <b>Set .env in the backend folder </b>
> 

```
CLOUD_AWS_DB_HOST=
CLOUD_AWS_DB_DATABASE_NAME=
CLOUD_AWS_DB_USERNAME=
CLOUD_AWS_DB_PASSWORD=

CLOUD_AWS_S3_BUCKETNAME=
CLOUD_AWS_S3_REGION=       
CLOUD_AWS_ACCESS_KEY_ID=
CLOUD_AWS_SECRET_ACCESS_KEY=
```

<br>

## 📊 Flowchart

![flowchart](https://github.com/Techeer-market/.github/assets/95288297/1228566c-f532-40a8-9e26-1ed69d17caf1)


## 🔍 Features

<br>

**회원가입/ 로그인** 

- JWT토큰을 이용한 회원가입/로그인 페이지

<br>

**메인페이지**

- InfiniteScroll을 이용한 게시물의 목록을 보여주는 페이지

<br>

**전체 카테고리 페이지**

<br>

**검색기능**

<br>

**게시물 작성**

- 대표이미지를 선택하여 지정할 수 있고, 갯수를 제한하여 총 4개 사진 게시 가능
- 카카오맵API를 이용하여 지도상 거래 희망 장소를 선정 가능

<br>

**게시물 상세보기** 

- 카카오맵API를 이용하여 지도상 거래 희망 장소 확인 가능
- 좋아요 기능을 통해 게시물을 좋아요 목록에서 관리 가능

<br>

**마이페이지**

- 좋아요 목록, 판매내역, 구매내역 선택하여 확인
- 계정/정보 관리에서 이메일, 비밀번호, 생년월일 등의 정보 수정 가능

<br>

**판매내역/구매내역**

- 사용자의 판매 내역과 구매내역을 관리 가능
- 판매내역에서는 판매 중, 거래 완료 상태로 구분하여 관리 가능

  <br>

## ⛹🏼‍♀️ Postman

Frontend와 Backend 통신을 위한 API 문서화는 Postman과 노션을 사용했다

https://documenter.getpostman.com/view/27567744/2s9Ykn9N3U

https://documenter.getpostman.com/view/27567744/2s9Ykn9N3V

[API 명세서](https://www.notion.so/API-9e28dd92dc194e1c85f6e801877a2432?pvs=21) 

<br>
<br>

## Member 
| 이름 | 홍다연 | 임성한 | 김유라 | 조은주 | 하재민 |
| --- | --- | --- | --- | --- | --- |
| 역할  | Leader, Backend | Backend | Frontend | Frontend | Frontend |
| 깃허브 | [Dayeon-Hong](https://github.com/Dayeon-Hong) | [seonghanIm](https://github.com/seonghanIm) | [yura0302](https://github.com/yura0302) | [dmswn1004](https://github.com/dmswn1004) | [penloo](https://github.com/penloo) |

<br>
