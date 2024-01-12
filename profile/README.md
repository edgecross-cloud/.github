# Edgecross Cloud Github
<p align="center">
  <img src="https://github.com/edgecross-cloud/.github/assets/96868951/1d192c4d-ad92-4454-bc79-dcc37660cf0e" width="80%" height="250px" />
</p>
<br>
클라우드 연구팀은 **R&D 연구센터에 소속**되어  모드링크(IoT Device)를 기반으로 IoT 생태계를 구축하는 일에 함께 하고 있습니다. 모드링크(IoT Device)를 기반으로 확보된 다양한 기계 설비 데이터는 Wifi, Ethernet, LTE 통신을 통해 클라우드 서버로 전송되며, 이 지점으로부터 클라우드 연구팀으로 업무가 연계됩니다.

클라우드 연구팀은 클라우드 서버로 도달한 **데이터를 AWS를 활용하여 수집 및 적재하고, 이를 추출, 변환, 로드하는 업무를 하며, 웹 및 앱에 사용자 친화적으로 데이터를 조회, 분석, 관리할 수 있는 서비스를 개발**하고 있습니다.

<br></br>
## 🐦Team Cloud 
| <img src="https://github.com/edgecross-cloud/.github/assets/96868951/be26cd16-d3b7-430b-9826-39fa50ea9e94" width="80" height="80" />  <br> 최창서 연구원 <br> (팀장) | <img src="https://github.com/edgecross-cloud/.github/assets/96868951/40df59aa-9943-49a7-bc4e-5853265971f8" width="80" height="80" /> <br> 유승근 연구원 <br> (팀원) | <img src="https://github.com/edgecross-cloud/.github/assets/96868951/18cc7ef1-77e8-43fe-b544-05c9035a5654" width="80" height="80" /> <br> 고민지 연구원 <br> (팀원) | <img src="https://github.com/edgecross-cloud/.github/assets/96868951/2020e122-58df-4b1c-8371-13f5e986d54c" width="80" height="80" /> <br> 김진성 연구원 <br> (팀원) |
|:---:|:---:|:---:|:---:|

<br></br>
## 🐦Project

### V-OLA
1. [vola-web-integration](https://github.com/edgecross-cloud/vola-web-integration) - V-OLA Web Service 입니다. Frontend(JQuery), Backend(Java Spring)가 함께 구성되어 있는 프로젝트입니다.
2. [vola-admin-integration](https://github.com/edgecross-cloud/vola-admin-integration) - V-OLA 관리자 Service 입니다. Frontend(JQuery), Backend(Java Spring)가 함께 구성되어 있는 프로젝트입니다.

### PROGIX
1. [progix-web-server](https://github.com/edgecross-cloud/progix-web-server)
2. [progix-haccp-server](https://github.com/edgecross-cloud/progix-haccp-server)
3. [progix-push-server](https://github.com/edgecross-cloud/progix-push-server)
4. [progix-web-client](https://github.com/edgecross-cloud/progix-web-client)
5. [progix-alarmlist-server](https://github.com/edgecross-cloud/progix-alarmlist-server)
6. [progix-react-native](https://github.com/edgecross-cloud/progix-react-native)

### SCAUTR 
1. [scautr-web-client](https://github.com/edgecross-cloud/scautr-web-server) - SCAUTR의 Frontend 서버입니다.
2. [scautr-web-server](https://github.com/edgecross-cloud/scautr-web-client) - SCAUTR의 Backend 서버입니다. 

### RELAYPOINT
1. [relaypoint-web-server](https://github.com/edgecross-cloud/relaypoint-web-server)
2. [relaypoint-web-client](https://github.com/edgecross-cloud/relaypoint-web-client)
3. [relaypoint-webview-client](https://github.com/edgecross-cloud/relaypoint-web-client)
4. [relaypoint-native-client](https://github.com/edgecross-cloud/relaypoint-native-client)
5. [relaypoint-push-server](https://github.com/edgecross-cloud/relaypoint-push-server)

### Rocket
1. [rocket-api-server](https://github.com/edgecross-cloud/rocket-api-server) - Rocket의 API 서버로, Cosmos DB를 사용합니다.
2. [rocket-function-server](https://github.com/edgecross-cloud/rocket-function-server) - Azure Function에서 사용하는 Rocket 소스코드입니다.
3. [rocket-migration-script](https://github.com/edgecross-cloud/rocket-migration-script) - Bespin IoTOps에서 Azure Cosmos로 마이그레이션하는 소스코드입니다. Vola-status는 javascript로 그 외엔 python으로 구성되어있습니다.

<br></br>
## 🐦Github Rules

### Repository Naming Rules
- 소문자 + 하이픈(-) 만 사용
- [서비스명]-[서비스 기능]-[서비스 역할] 형식으로 작성
- ex. progix-web-server
- ex. progix-web-client
- ex. progix-push-server
- ex. v-ola-app-ios

### Repository Branch Rules
- <b>main branch</b>
  - 실제 배포/운영 브랜치
  - 실제 배포된 버전의 소스코드로 유지

- <b>develop branch</b>
  - 전체 개발 브랜치 
  - 모든 개발은 develop branch를 중심으로 진행
  - develop branch는 완성되어 배포가 확정된 코드로 유지
  - feature branch에서 개발하여 pull request로 merge를 진행

- <b>feature branch</b>
  - 세부 기능 개발 브랜치
  - feature branch를 생성하는법
    1. 개발하려는 기능으로 Github Issue 생성하기 
    2. Github Issue Number을 확인하기
    3. feature/[github-issue-number]-[개발하려는 기능] 형식으로 브랜치 생성하기 ex. feature/3-alarm


### Commit convention
- To be determined
