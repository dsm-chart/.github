# Chart란?

---

> 방과후 프로젝트반 **DaF** 팀에서 진행하고 있어요.
> 
> ***학생들에게 필요한 기능(ex. 시간표, 급식표)를 포함하여, 개발자에게도 유용한 기능(github 커밋 그래프)을 제공하기 위해 노력해요!***


# DaF팀이란?

---

> ***Daehee And Friend의 약자에요!***  *따뜻히 품어주세요.....
> 
> **Chart 개발팀 이름이 DaF랍니다!***








# 개발 언어 및 활용 기술

---


## FE

---

### 개발환경

- React.js라는 js 라이브러리 사용합니다.
- react hooks를 통해 동적인 웹페이지를 만듭니다.
- recoil을 통해 상태관리합니다.
- jsx를 통해 문서를 작성합니다.
- Styled-component를 이용하여 jsx로 작성한 문서에 스타일을 입힙니다.
- axios를 통해 api를 호출하는데 async와 await를 이용해 비동기로 호출합니다.
- swiper.js를 통해 급식표 슬라이드 ui 제작



## BE

---

### 개발 환경

- **SpringBoot** 로 어플리케이션 서버를 구축합니다.
- 빌드 도구로는 *Gradle*을 사용합니다.
- 어플리케이션의 **안전성과, 간결함, 자바와의 높은 상호 운영성**을 위해 **Kotlin**으로 개발합니다.
- **Spring Data JPA(Hibernate)** 로 *객체 지향 데이터 로직*을 작성합니다.

### Infrastructure

- **AWS EC2**를 사용합니다.
- **AWS RDS**를 데이터베이스로 사용합니다.
- **Firebase Cloud Message** 를 사용하여 푸시알림을 구현합니다.

### CI/CD

- **TrivisCI** 로 *빌드와 테스트를 검사합니다.*
- **CodeDeploy** 로 *빌드 자동화를 구축합니다.*
- **Sonar Cloud**를 통해 github에 Push된 code를 정적분석하여, 보안 취약점 및 버그 등을 사전에 탐색합니다.

### Security

- **Spring Security** 를 사용합니다.
- **JWT**를 이용하여, *서버에 별도 저장소*를 유지하지 않음에도 권한을 인증할 수 있는 로직을 구성합니다.




## Backend Architecture
![architecture](https://github.com/dsm-chart/Chart-Backend-V1/blob/main/chart-architecture.png)



Notion: https://dsm-chart.notion.site/Chart-bac26b6525e54ce9a4086fcb8d0a1200
