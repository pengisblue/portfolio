# 푸른 : 아이와 함께 성장하는 화분
> 삼성 청년 SW 아카데미 (SSAFY) 10기 공통 PJT </br>
> 식물상태 정보 제공 및 아이와 소통이 가능한 스마트 화분 </br>
> 2024.01.08 ~ 2024.02.16 (6주) </br>
> [🔗 푸른 Notion 바로가기](https://pengisblue.notion.site/E101-132c697bfe734b22b0640fc0aaec8c80?pvs=4)

### TOC
1. [TEAM](#팀소개)
2. [서비스 소개](#서비스-소개)
3. [UCC](#ucc)
4. [Overview](#overview)
    - [홈화면](#홈화면)
    - [화분 정보](#화분-정보)
    - [아이 정보](#아이-정보)
    - [대화](#대화)
    - [컬렉션](#컬렉션)
5. [기술 스택](#기술-스택)
    - [아키텍처](#아키텍처)
    - [통신 환경](#통신-환경)
4. [Commit Convention](#commit-convention)


## 팀소개

|김해인<br>(팀장)|한성주<br>(팀원)|김연빈<br>(팀원)|이동호<br>(팀원)|최진우<br>(팀원)|박종국<br>(팀원)
|:--:|:--:|:--:|:--:|:--:|:--:|
|Frontend|Embedded|Embedded|Frontend|Backend|Backend|

## 서비스 소개
![푸른이](https://github.com/RosaDamascena/Pureun/assets/95911613/e61a9384-0dd5-4ca1-981e-4fe728d8684d)

### 아이와 대화하기
호출어 ("푸른아!")로 푸른이를 부를 수 있습니다.<br>

안내음이 들린 뒤 말을 걸면, 푸른이가 친절하게 대답해줍니다. 응답을 들은 뒤 다시 말을 걸어 대화를 이어갈 수 있습니다.<br>

웹에서는 아이와 화분이 나눈 대화를 텍스트와 음성으로 확인할 수 있습니다.

### 온도, 습도 관리
화분을 등록하고 관리할 수 있습니다.<br>

현재의 온도, 습도와 어제의 상태를 그래프로 확인하고 관리할 수 있게 돕습니다.<br>

만약 등록한 식물이 적정 온도나 습도를 벗어나는 경우. 화분의 표정이 변화하여 간단하게 상태를 파악할 수 있습니다. 

### 기타 상호작용
가까이 다가가면 손을들어 인사해줍니다.!<br>
아주아주 귀엽습니다.

## UCC
### [푸른이의 하루 보러가기!](https://youtu.be/fuwtwcdx7YY?si=M9KMLYXY5HIp1sCQ)

## Overview
### 홈화면
|부모|키즈모드|
|:--:|:--:|
|<img src="readme.assets/main.png" alt="메인" width="200">|<img src="readme.assets/main_kids.png" alt="메인" width="200">|

### 화분 정보
|부모 - 화분목록|부모 - 화분상세|키즈모드 - 화분|
|:--:|:--:|:--:|
|<img src="readme.assets/pot_list.png" alt="화분목록" width="200">|<img src="readme.assets/pot_d1.png" alt="화분상세" width="200">|<img src="readme.assets/pot_d_k.png" alt="키즈화분" width="200">|

### 아이 정보
|아이 목록|아이 상세|
|:--:|:--:|
|<img src="readme.assets/kid_list.png" alt="아이목록" width="200">|<img src="readme.assets/kid.png" alt="아이상세" width="200">|

### 대화
|대화 목록|대화 상세|
|:--:|:--:|
|<img src="readme.assets/talk_list.png" alt="대화 목록" width="200">|<img src="readme.assets/talk.png" alt="대화 상세" width="200" height="500">|

### 컬렉션
|부모 - 컬렉션|키즈모드 - 컬렉션|
|:--:|:--:|
|<img src="readme.assets/col.png" alt="컬렉션" width="200"></br><img src="readme.assets/col2.png" alt="컬렉션" width="200">|<img src="readme.assets/col_kid.png" alt="키즈모드 컬렉션" width="200">|


## 기술 스택
### ⚙ Management Tool

![Jira](https://img.shields.io/badge/jira-3776AB.svg?&style=for-the-badge&logo=jira&logoColor=white)
![Gitlab](https://img.shields.io/badge/gitlab-3776AB.svg?&style=for-the-badge&logo=gitlab&logoColor=white&color=orange)
![Mattermost](https://img.shields.io/badge/Mattermost-3776AB.svg?&style=for-the-badge&logo=Mattermost&logoColor=white)
![figma](https://img.shields.io/badge/figma-3776AB.svg?&style=for-the-badge&logo=figma&logoColor=white&color=red)
![notion](https://img.shields.io/badge/notion-3776AB.svg?&style=for-the-badge&logo=notion&logoColor=white&color=black)

### 💻 IDE

![vscode](https://img.shields.io/badge/vscode-3776AB.svg?&style=for-the-badge&logo=visualstudiocode&logoColor=white&)

### 🔑 Infra
![amazonAWS](https://img.shields.io/badge/amazon%20AWS-232F3E?&style=for-the-badge&logo=amazonAWS&logoColor=white)
![jenkins](https://img.shields.io/badge/jenkins-d24939?style=for-the-badge&logo=jenkins&logoColor=white)
![docker](https://img.shields.io/badge/docker-3776AB.svg?&style=for-the-badge&logo=docker&logoColor=white&color=2496ED)
![nginx](https://img.shields.io/badge/nginx-3776AB.svg?&style=for-the-badge&logo=nginx&logoColor=white&color=009639)

### 🥽 Embedded

![python](https://img.shields.io/badge/python-3776AB.svg?&style=for-the-badge&logo=python&logoColor=white&color=3776AB)
![c](https://img.shields.io/badge/c-3776AB.svg?&style=for-the-badge&logo=c&logoColor=white&color=A8B9CC)
![raspberrypi](https://img.shields.io/badge/RaspberryPi-3776AB.svg?&style=for-the-badge&logo=RaspberryPi&logoColor=white&color=A22846)
![arduino](https://img.shields.io/badge/Arduino-3776AB.svg?&style=for-the-badge&logo=Arduino&logoColor=white&color=00878F)
![RealVNC](https://img.shields.io/badge/RealVNC-3776AB.svg?&style=for-the-badge&logo=RealVNC&logoColor=white&color=blue)

### 📱 FrontEnd

![react](https://img.shields.io/badge/react-3776AB.svg?&style=for-the-badge&logo=react&logoColor=black&color=61DAFB)
![css](https://img.shields.io/badge/css-3776AB.svg?&style=for-the-badge&logo=css3&logoColor=white&color=1572B6)
![tailwind](https://img.shields.io/badge/tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![redux](https://img.shields.io/badge/redux-3776AB.svg?&style=for-the-badge&logo=redux&logoColor=white&color=764ABC)

### 📋 BackEnd

![nodejs](https://img.shields.io/badge/nodejs-3776AB.svg?&style=for-the-badge&logo=Node.js&logoColor=white&color=339933)
![nestjs](https://img.shields.io/badge/nestjs-3776AB.svg?&style=for-the-badge&logo=nest.js&logoColor=white&color=E0234E)
![typeorm](https://img.shields.io/badge/typeorm-3776AB.svg?&style=for-the-badge&logo=typeorm&logoColor=white&color=262627)
![mysql](https://img.shields.io/badge/mysql-3776AB.svg?&style=for-the-badge&logo=mysql&logoColor=blue&color=4479A1)
![swagger](https://img.shields.io/badge/swagger-3776AB.svg?&style=for-the-badge&logo=swagger&logoColor=white&swagger=85EA2D)

### 아키텍처

![아키텍처](https://github.com/RosaDamascena/Pureun/assets/95911613/3b6d93d8-e79c-4d4b-b3a5-d88b9eba50d6)

### 통신 환경

![기술](https://github.com/RosaDamascena/Pureun/assets/95911613/802bcba0-8e69-4aab-b6a0-3ad38a3cc661)

## Commit Convention

|Tag Name|Description|
|:--:|:--|
|feat|새로운 기능을 추가|
|fix|버그 수정|
|design|CSS 등 사용자 UI 디자인 변경|
|!BREAKING<br/>CHANGE|커다란 API 변경|
|!HOTFIX|급하게 치명적인 버그를 고쳐야하는 경우|
|style|코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우|
|refactor|프로덕션 코드 리팩토링|
|comment|필요한 주석 추가 및 변경|
|docs|문서 수정|
|test|테스트 코드, 리팩토링 테스트 코드 추가, <br/>Production Code(실제로 사용하는 코드) 변경 없음|
|chore|빌드 업무 수정, 패키지 매니저 수정, 패키지 관리자 구성 등 업데이트, <br/>Production Code 변경 없음|
|rename|파일 혹은 폴더명을 수정하거나 옮기는 작업만 수행한 경우|
|remove|파일을 삭제하는 작업만 수행한 경우|