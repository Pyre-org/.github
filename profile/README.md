## 🙌 Hello. Pyre is always with you!
<img src="https://cdn.discordapp.com/attachments/1214849763745202176/1214850895133679616/pyre.png?ex=65fa9d10&is=65e82810&hm=0824d809c6b9297212831b1bcac723e24bf93b2199ffbcb665e84092034a133d&" alt="drawing" width="400"/>

#### [Github 조직](https://github.com/Pyre-org)

## 🏢 TEAM
- ### Backend 
  - 허재우 (CSE, UNIST)
    - [Github](https://github.com/wodn1478)
    - Email: wodn14789@naver.com
- ### Frontend 
  - 황찬휘 (CSE, UNIST)
    - [Github](https://github.com/chan-hwi)
    - Email: gazebo5@naver.com


## ❓ Pyre란 무엇인가요?
- **Pyre**는 스크린샷 관련 기능을 강화한 애플리케이션입니다. 주요 기능은 다음과 같습니다:

  - **스크린샷 링크화 기능**: 사용자는 Pyre를 사용하여 스크린샷을 찍고, 이를 쉽게 **링크**로 변환하여 공유할 수 있습니다.

  - **스크린샷 전용 및 채팅 커뮤니티**: Pyre는 스크린샷 공유를 위한 전용 **커뮤니티**를 제공하며, 사용자들은 여기서 스크린샷을 업로드하고 **채팅**할 수 있습니다.

- 이 밖에도 **Pyre**는 다양한 **기능**을 제공합니다:

  - **단축키를 활용한 쉬운 캡처**: 사용자는 Pyre의 **단축키**를 활용하여 쉽게 스크린샷을 찍을 수 있습니다. 또한, **클립보드**에 저장된 새로운 링크를 통해 스크린샷을 손쉽게 **공유**할 수 있습니다.

  - **영역 지정 및 GIF 생성**: Pyre를 사용하면 사용자가 원하는 **영역**을 지정하여 스크린샷을 캡처하거나 짧은 **GIF**를 생성할 수 있습니다.

  - **스크린샷 커뮤니티 연동**: 사용자는 Pyre를 통해 플레이 중인 게임 커뮤니티에 스크린샷을 바로 업로드할 수 있습니다. 또한, 몇 번의 클릭만으로 게임 채널 내 자신이 운영 중인 룸에 스크린샷을 **배포**할 수 있습니다.

## 🛠 기술 스택 - Backend
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

  
## 🛠 기술 스택 - Frontend
  - Electron with Vite
  - React + Typescript
  - React Hook Form with Zod
  - Zustand for Client state management
  - React Query for Server state management
  - TailwindCss for styling
  - Shadcn/ui for component library

## 🔅 프로젝트 구조
### Backend
<img src="https://cdn.discordapp.com/attachments/393025698907947009/1219214404193882122/d51f8c7f765ef5fd.png?ex=660a7ce5&is=65f807e5&hm=348780b6d433faa213bdaee0b5e359d70b1ba34feca3eed253418572291faa07&" alt="drawing" width="600"/>

#### [PyreGateway](https://github.com/Pyre-org/PyreGateway-source.git)
  - **Gateway**: 백엔드와 프론트의 통신문
  - **기능**: API 라우팅, 유저 인증 및 권한 확인, 로드밸런싱
#### [PyreAuth](https://github.com/Pyre-org/PyreAuth-source.git)
  - **기능**: 유저 CRUD, Jwt 발급 및 저장, 이메일 센더, S3 업로드 엔드포인트 관리
#### [PyreCommunity](https://github.com/Pyre-org/PyreCommunity.git)
  - **기능**: 채널 - 룸 - 스페이스 계층 CRUD
#### [PyreFeed](https://github.com/Pyre-org/pyreFeedMvc.git)
  - **기능**: 피드 CRUD 
###### PyreChat - 구현 예정.. (kafka)

### Frontend

## 영상
### 채널 생성(채널 승인 요청)
![채널 승인 요청](https://media.discordapp.net/attachments/393025698907947009/1219229952654970900/3da16a0c86508e94.gif?ex=660a8b60&is=65f81660&hm=674e7d03ca7cf65cbf086088436f6428310023be0fd4384ddcabe4d78ceb15b4&=&width=895&height=503)
### 채널 구독 및 룸 생성
![채널 구독 및 룸 생성](https://cdn.discordapp.com/attachments/393025698907947009/1219229949911892018/d2a22948f56fd7a8.gif?ex=660a8b60&is=65f81660&hm=ae5cbd6599d5dab340d015c936a78d96b239280ff9c77986978d0560add1c0fb&)
### 룸 정보 수정
![룸 정보 수정](https://media.discordapp.net/attachments/393025698907947009/1219229950779850833/3e3d67cbdf96b7d9.gif?ex=660a8b60&is=65f81660&hm=edac4b5042f6fd24c66687f45fb97f01d4db7b4eb3d5a19d16cde302cfd3126b&=&width=895&height=503)
### 스페이스 생성
![스페이스 생성](https://media.discordapp.net/attachments/393025698907947009/1219229950381658222/315221bb75e8ef94.gif?ex=660a8b60&is=65f81660&hm=c7361e6fda4791951b040efc1a8e42b9271993925cddaac55f985babc050b93d&=&width=895&height=503)
### 스크린샷 (CTRL + SHIFT + C 영역캡처 및 자동 피드 업로드)
![피드 자동 업로드](https://media.discordapp.net/attachments/393025698907947009/1219229951622905956/a2cbc38adccb09cf.gif?ex=660a8b60&is=65f81660&hm=300c873da8a056c877c0762224375a6baa22efb6dab8c45969bc51bf1eda52fa&=&width=895&height=503)
### 스크린샷 링크화 (캡처 후 클립보드에 자동으로 저장됨)
![스크린샷 링크화](https://cdn.discordapp.com/attachments/393025698907947009/1219232242224595025/2240875837fbeaae.gif?ex=660a8d82&is=65f81882&hm=d01a68e588bdbf8e7e6681fc91a0d387e815dd20f5168742aa277c2e116abe8c&)
