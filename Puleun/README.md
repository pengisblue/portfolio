# 푸른 : 아이와 함께 성장하는 화분
`보안상의 이유로 소스코드는 없습니다`
> 삼성 청년 SW 아카데미 (SSAFY) 10기 공통 PJT </br>
> 식물상태 정보 제공 및 아이와 소통이 가능한 스마트 화분 </br>
> 2024.01.08 ~ 2024.02.16 (6주) </br>
> [🔗 푸른 Notion 바로가기](https://pengisblue.notion.site/E101-132c697bfe734b22b0640fc0aaec8c80?pvs=4)

### TOC
1. [TEAM](#팀소개)
2. [기술 스택](#기술-스택)
3. [Commit Convention](#commit-convention)
4. [Overview](#overview)
    - [홈화면](#홈화면)
    - [화분 정보](#화분-정보)
    - [아이 정보](#아이-정보)
    - [대화](#대화)
    - [컬렉션](#컬렉션)

## 팀소개

|김해인<br>(팀장)|한성주<br>(팀원)|김연빈<br>(팀원)|이동호<br>(팀원)|최진우<br>(팀원)|박종국<br>(팀원)
|:--:|:--:|:--:|:--:|:--:|:--:|
|Frontend|Embedded|Embedded|Frontend|Backend|Backend|

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
