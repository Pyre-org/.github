## 🙌 Hello. Pyre is always with you!
<img src="https://cdn.discordapp.com/attachments/1214849763745202176/1214850895133679616/pyre.png?ex=65fa9d10&is=65e82810&hm=0824d809c6b9297212831b1bcac723e24bf93b2199ffbcb665e84092034a133d&" alt="drawing" width="400"/>

#### 현재 파이어는 미완성 프로젝트입니다. 다운로드를 통해 파이어를 테스트할 수 있습니다.
#### [Github 조직](https://github.com/Pyre-org) 
#### 윈도우 [프로그램 다운로드 링크](http://naver.me/xc93Mkq0)


## 🏢 TEAM
- ### Backend 
  - 허재우 (CSE, UNIST)
    - [Github](https://github.com/wodn1478)
    - Email: wodn14789@naver.com
- ### Frontend 
  - 황찬휘 (CSE, UNIST)
    - [Github](https://github.com/chan-hwi)
    - Email: gazebo5@naver.com
---
---
## 목차
- [**1. Pyre 소개**](#1-pyre-소개)
- [**2. 기술 스택**](#2-기술-스택)
- [**3. 프로젝트 구조**](#3-프로젝트-구조)
- [**4. 빌드 및 실행 가이드**](#4-빌드-및-실행-가이드)
- [**5. 미디어 자료**](#5-이미지)

# 1. Pyre 소개
## ❓ Pyre란 무엇인가요?
- [파이어 이미지 보러가기](#이미지)
- [파이어 사용 GIF 보러가기](#영상)
- **Pyre**는 스크린샷 관련 기능을 강화한 애플리케이션입니다. 주요 기능은 다음과 같습니다:

  - **스크린샷 링크화 기능**: 사용자는 Pyre를 사용하여 스크린샷을 찍고, 이를 쉽게 **링크**로 변환하여 공유할 수 있습니다.

  - **스크린샷 전용 및 채팅 커뮤니티**: Pyre는 스크린샷 공유를 위한 전용 **커뮤니티**를 제공하며, 사용자들은 여기서 스크린샷을 업로드하고 **채팅**할 수 있습니다.

  - **스크린샷 링크화** (캡처 후 클립보드에 자동으로 저장됨) : GIF를 재생해보세요. 

  ![스크린샷 링크화](https://cdn.discordapp.com/attachments/393025698907947009/1219232242224595025/2240875837fbeaae.gif?ex=660a8d82&is=65f81882&hm=d01a68e588bdbf8e7e6681fc91a0d387e815dd20f5168742aa277c2e116abe8c&)
  - **피드 자동 업로드 예시** (캡처 후 커뮤니티에 자동으로 업로드됨. 별도 개인설정 필요) : GIF를 재생해보세요.

  ![피드 자동 업로드](https://media.discordapp.net/attachments/393025698907947009/1219229951622905956/a2cbc38adccb09cf.gif?ex=660a8b60&is=65f81660&hm=300c873da8a056c877c0762224375a6baa22efb6dab8c45969bc51bf1eda52fa&=&width=895&height=503)

- 이 밖에도 **Pyre**는 다양한 **기능**을 제공합니다:

  - **단축키를 활용한 쉬운 캡처**: 사용자는 Pyre의 **단축키**를 활용하여 쉽게 스크린샷을 찍을 수 있습니다. 또한, **클립보드**에 저장된 새로운 링크를 통해 스크린샷을 손쉽게 **공유**할 수 있습니다.

  - **영역 지정 및 GIF 생성**: Pyre를 사용하면 사용자가 원하는 **영역**을 지정하여 스크린샷을 캡처하거나 짧은 **GIF**를 생성할 수 있습니다. **(GIF 구현 예정..)**

  - **스크린샷 커뮤니티 연동**: 사용자는 Pyre를 통해 플레이 중인 게임 커뮤니티에 스크린샷을 바로 업로드할 수 있습니다. 또한, 몇 번의 클릭만으로 게임 채널 내 자신이 운영 중인 룸에 스크린샷을 **배포**할 수 있습니다.


- **파이어 구체적 설명**:
  - **채널**: 
    - 커뮤니티에서 가장 큰 개념입니다. 
	- 채널은 여러 룸을 포함할 수 있습니다.
	- 채널은 관리자의 승인을 받아야 공개적으로 표시됩니다.
	- 채널을 구독하면 해당 채널에서 활동할 수 있습니다.
	- 채널은 기본적으로 공용 룸과 방금 캡처됨이라는 룸을 포함합니다.
  - **룸**:
  
    - 룸은 커뮤니티에서 채널 다음으로 큰 개념입니다.
  
	- 룸은 채널에 속해 있고, 여러 스페이스를 포함할 수 있습니다.
	- 룸은 누구든지 생성 가능하고, 공개/비공개 룸으로 분류할 수 있습니다.
	- 공개 룸일 경우 모든 유저가 참여 가능한 룸이 되고, 비공개일 경우 초대 링크를 통해 유저가 참여할 수 있습니다.
	- 룸은 기본적으로 일반 피드와 일반 채팅이라는 스페이스를 포함합니다. 이는 삭제할 수 없습니다.
        - 룸에 가입할 때 초대장을 통한 가입은 USER 역할을 부여받고, 공개 룸의 가입은 GUEST의 역할을 부여받습니다.
        - 룸에서 부여된 역할에 따라 사용할 수 있는 스페이스가 달라질 수 있습니다.
        - 룸 역할: ADMIN, MODE, USER, GUEST 순서로 권한이 낮아집니다.
        - MODE 역할부터 룸을 관리할 수 있으며, 자신과 동일하거나 높은 역할의 멤버는 차단 및 역할 변경을 할 수 없습니다.
        - 룸 멤버 수정을 통해 역할은 언제든지 변경 가능합니다.

  - **스페이스**:
  
    - 스페이스는 커뮤니티에서 가장 작은 개념입니다.
    
	- 스페이스는 룸에 속해 있고, 피드/채팅 스페이스로 분류됩니다.
	- 스페이스는 개별로 권한을 부여할 수 있습니다. 해당 스페이스가 가진 권한보다 높은 권한을 가진 멤버만 스페이스가 룸에 표시됩니다.
          - GUEST 권한을 가진 멤버일 경우 유저 권한의 스페이스를 사용할 수 없습니다. 
	- 피드 스페이스의 경우 권한이 있는 사용자가 피드를 업로드할 수 있고, 채팅 스페이스의 경우 권한이 있는 사용자가 채팅을 할 수 있습니다(구현 중..)
  
  - **피드**:
  
    - 피드는 피드 스페이스에서 공유되는 컨텐츠로 제목, 설명, 사진을 포함합니다.
    - 피드는 스크린샷을 캡처해서 업로드하거나 직접 스페이스에서 업로드할 수 있습니다.
  
  - **방금 캡처됨**: 방금 캡처됨 룸은 채널 당 1개씩 존재하며, 해당 채널에 속한 스페이스의 업로드된 모든 스크린샷이 업로드 됩니다. 이 기능을 비활성화 하려면 설정에서 **캡처룸 사용 여부**를 체크 해제 해주세요.
  
  - **캡처 단축키**:
  
    - 전체 영역 : CTRL + SHIFT + D
    - 영역 선텍 : CTRL + SHIFT + C
  
  - **설정**:
  
    - 설정에서 자신의 프로필이나 피드 관련 설정을 수정할 수 있습니다.
    
	- 기본 스페이스를 설정할 시 스크린샷 캡처시 자동으로 해당 스페이스에 피드가 업로드 됩니다.
	- **캡처룸 사용 여부**: 체크할 시 기본 스페이스가 속해 있는 채널의 '방금 캡처됨'룸에도 자동으로 피드가 업로드 됩니다.
	- **캡처 시 팝업 입력창 표시 여부**: 체크할 시 스크린샷 캡처시 제목 또는 설명을 작성할 수 있는 팝업창을 띄울 수 있습니다.
# 2. 기술 스택
## 🛠 Backend
  - Java 21
  - Spring Boot (3.2.2)
  - Spring Web
  - Spring Data JPA
  - Spring Cloud
  
  - Jwt
  - Spring Security
  
  - Mysql
  - Redis
  - MongoDB for PyreFeed
    
  - Open API Swagger
  
## 🛠 Frontend
  - Electron with Vite
  - React + Typescript
  - React Hook Form with Zod
  - Zustand for Client state management
  - React Query for Server state management
  - TailwindCss for styling
  - Shadcn/ui for component library

# 3. 프로젝트 구조
## 🔅 Backend
<img src="https://cdn.discordapp.com/attachments/393025698907947009/1219214404193882122/d51f8c7f765ef5fd.png?ex=660a7ce5&is=65f807e5&hm=348780b6d433faa213bdaee0b5e359d70b1ba34feca3eed253418572291faa07&" alt="drawing" width="600"/>

#### [PyreGateway](https://github.com/Pyre-org/PyreGateway-source.git)
  - **Gateway**: 백엔드와 프론트의 통신문
  - **기능**: API 라우팅, 유저 인증 및 권한 확인, 로드밸런싱
#### [PyreAuth](https://github.com/Pyre-org/PyreAuth-source.git)
  - **기능**:
    - 유저의 회원가입, 로그인 등 인증 및 인가를 관리합니다.
    - Oauth2도 함께 관리합니다.
    - JWT (access token + refresh token) 발급 및 Redis를 통해 refresh를 저장합니다.
    - 저장된 리프레시 토큰은 1번 사용되면 다시 재발급 + 재저장 됩니다.
    - 이미지 업로드를 위한 S3 업로드 서비스가 포함되어 있습니다.
    - 유저 프로필 관리 및 이메일 서비스도 함께 포함되어 있습니다.
    - Swagger API [링크](https://apis.pyre.live/auth-service/swagger-ui/index.html)
#### [PyreCommunity](https://github.com/Pyre-org/PyreCommunity.git)
  - **기능**:
    - 관계형 데이터베이스를 사용하여 파이어 커뮤니티의 채널-룸-스페이스 계층의 데이터를 관리합니다.
    - Redis를 사용하여 기간제 룸 초대권을 생성 및 관리합니다.
    - Swagger API [링크](https://apis.pyre.live/community/swagger-ui/index.html)
#### [PyreFeed](https://github.com/Pyre-org/pyreFeedMvc.git)
  - **기능**:
    - NoSQL 데이터베이스 MongoDB를 사용하여 파이어의 피드 데이터를 관리합니다.
    - 스크린샷으로부터 발생하는 피드를 저장하고, 조회할 수 있습니다.
    - Swagger API [링크](https://apis.pyre.live/feed/swagger-ui/index.html)
###### PyreChat - 구현 예정..

## 🔅 Frontend


# 4. 빌드 및 실행 가이드
### 1. 레포지토리 클론
```
git clone https://github.com/Pyre-org/Pyre-Frontend.git
```
### 2. 패키지 설치
```
npm i
```
or
```
yarn
```
### 3. Electron 빌드 커맨드 실행
### Windows
```
npm run build:win
```
or
```
yarn build:win
```

### MacOS
```
npm run build:mac
```
or
```
yarn build:mac
```
### 4. 설치 및 실행
빌드 후 생성된 dist 폴더 안의 pyre-front-1.0.0-setup 실행 파일 실행

---
---
---
### 아래에는 이해를 돕기 위한 미디어 자료들이 있습니다.

### 자세하게 GIF로도 설명되어 있으니 살펴보시기 바랍니다.
---
---
---


# 5. 이미지
### 로그인 페이지
![로그인 페이지](https://github.com/Pyre-org/.github/assets/39799541/12597fa4-8f61-4b0d-bb35-dc906759dc58)

### 회원가입 페이지 (이메일 인증 필요)
![회원가입 페이지](https://github.com/Pyre-org/.github/assets/39799541/71135512-5d7b-48fa-8973-663c120a55a7)
![image](https://github.com/Pyre-org/.github/assets/39799541/ac908e70-e05b-4756-95ae-86ed3a440902)


### 마이페이지 최신 피드
![마이페이지 최신 피드](https://github.com/Pyre-org/.github/assets/39799541/fb279aea-2e17-4528-8b7b-e3ac7db2f1a6)

### 마이페이지 나의 피드
![image](https://github.com/Pyre-org/.github/assets/39799541/178c0529-2503-4a73-a8b2-b6028484eebf)

### 채널 메인 페이지
![image](https://github.com/Pyre-org/.github/assets/39799541/9c48449c-7121-40cd-8e9e-e6d874d71dc4)

### 채널 선택 후 페이지
![image](https://github.com/Pyre-org/.github/assets/39799541/b41a3468-75cc-46e7-b0e3-8b4bb72950c1)

### 룸 방금 캡처됨 페이지
![image](https://github.com/Pyre-org/.github/assets/39799541/4de3c570-6325-4fad-bc71-5eabd88a093f)

### 프로필 페이지
![image](https://github.com/Pyre-org/.github/assets/39799541/8ba88d32-c50e-439e-8a0f-ca1b10ac6341)

### 프로필 설정 페이지
![image](https://github.com/Pyre-org/.github/assets/39799541/6c6c6483-da77-4e73-a8e8-890bad341793)
![image](https://github.com/Pyre-org/.github/assets/39799541/da5f9c86-4cd8-4f49-9bee-92e6bb0d8319)

### 다크 모드 전환
![image](https://github.com/Pyre-org/.github/assets/39799541/e4babf86-8003-4593-a0ff-04f57c9ce601)


# 영상
### 회원가입 이메일 인증
![회원가입 이메일 인증](https://github.com/Pyre-org/.github/assets/39799541/57a6e501-5c0f-4920-b31d-248cf51fd8d3)

### 프로필 수정
![프로필 수정](https://github.com/Pyre-org/.github/assets/39799541/2d0c1904-cf94-417d-8228-1dd3a1473010)

### 채널 구독
![채널 구독](https://github.com/Pyre-org/.github/assets/39799541/8517f509-ab25-41f2-88d0-cb2fbb8261bd)

### 우측 채널 검색
![우측 채널 검색](https://github.com/Pyre-org/.github/assets/39799541/b9be9461-9028-47fa-9c7f-08dbb81d1267)

### 공개 타입의 룸 검색
![공개 타입의 룸 검색](https://github.com/Pyre-org/.github/assets/39799541/0e4b6cbe-d326-4d37-a5db-db64ffa3535d)

### 룸 생성
![룸 생성](https://github.com/Pyre-org/.github/assets/39799541/c7d1b334-3683-49f6-9c60-978be38f10cc)

### 룸 수정
![룸 수정](https://github.com/Pyre-org/.github/assets/39799541/9d0d99fd-0f52-4336-8067-bd05f3c2c6ef)

### 룸 삭제
![룸 삭제](https://github.com/Pyre-org/.github/assets/39799541/6a99b847-d4ac-4328-848e-2c85755d24ff)

### 룸 참가 및 탈퇴: 룸의 주인은 탈퇴를 할 수 없습니다.
![룸 참가 및 탈퇴](https://github.com/Pyre-org/.github/assets/39799541/719172fa-4e6b-4faa-ac41-615d1ea55e17)

### 룸 위치 변경: 공용과 방금 캡처 됨 룸은 변경할 수 없습니다.
![룸 위치 변경](https://github.com/Pyre-org/.github/assets/39799541/1f66e23e-bf07-43a5-ac79-fd5088cc17d6)


### 스페이스 생성
![스페이스 생성](https://github.com/Pyre-org/.github/assets/39799541/82c1bdff-8d73-4b5b-842e-9690258a36d5)

### 스페이스 수정
![스페이스 수정](https://github.com/Pyre-org/.github/assets/39799541/3ec82f74-cdba-4ab2-b644-c501d355125e)

### 스페이스 삭제: 일반 피드와 일반 채팅 방은 삭제할 수 없습니다.
![스페이스 삭제](https://github.com/Pyre-org/.github/assets/39799541/601acf17-4a90-458e-a5b8-24b1ec9f3530)

### 스페이스 위치 변경: 일반 피드와 일반 채팅 방은 변경할 수 없습니다.
![스페이스 위치 변경](https://github.com/Pyre-org/.github/assets/39799541/71c28a9f-d3a6-4e58-8bef-8c6265199af7)

### 초대코드 생성: 비공개 룸은 초대코드를 통해 가입할 수 있습니다. 초대코드는 7일간 사용 가능하며, 재생성 시 이전 코드는 사용할 수 없습니다.
![룸 초대코드 생성](https://github.com/Pyre-org/.github/assets/39799541/26632a54-ddca-4e0f-b3f2-db4f0bdbc7ed)

초대 예시 코드: pyre://invitations/ffff76bf

### 초대코드 사용
![초대코드 사용](https://github.com/Pyre-org/.github/assets/39799541/cc7b94d5-c38c-4638-a24b-d8af0189b2f8)

### 룸 및 스페이스 전체 검색: 파이어에 공개된 룸 또는 내가 참가한 룸 및 게스트 읽기 권한이 있는 스페이스만 조회됩니다.
![룸 및 스페이스 검색](https://github.com/Pyre-org/.github/assets/39799541/c06f5ea9-695b-4b99-b2b9-da7571585628)

### 피드 업로드
![피드 업로드](https://github.com/Pyre-org/.github/assets/39799541/015af3b4-882e-4d28-b6b0-a7c149aeba5b)

### 피드 수정
![피드 수정](https://github.com/Pyre-org/.github/assets/39799541/4642e8f4-bee7-4944-806e-2fecf2c17902)

### 피드 삭제
![피드 삭제](https://github.com/Pyre-org/.github/assets/39799541/bbf74e2d-4417-4641-ab1c-6663bc683253)

### 피드 스크린샷 캡처로 업로드 (CTRL + SHIFT + D 전체 캡처, CTRL + SHIFT + C 영역 캡처)
#### 스크린샷을 통한 피드 업로드는 설정에서 기본 스페이스 설정 및 피드 팝업에 대한 설정이 필요합니다.

![피드 자동 업로드](https://media.discordapp.net/attachments/393025698907947009/1219229951622905956/a2cbc38adccb09cf.gif?ex=660a8b60&is=65f81660&hm=300c873da8a056c877c0762224375a6baa22efb6dab8c45969bc51bf1eda52fa&=&width=895&height=503)

### 스크린샷 링크화 (캡처 후 클립보드에 자동으로 저장됨)
![스크린샷 링크화](https://cdn.discordapp.com/attachments/393025698907947009/1219232242224595025/2240875837fbeaae.gif?ex=660a8d82&is=65f81882&hm=d01a68e588bdbf8e7e6681fc91a0d387e815dd20f5168742aa277c2e116abe8c&)
