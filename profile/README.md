<div id="top"></div>

[//]: # (팀로고, 팀명)
## <a href="https://4vidia.shop" style="text-decoration:none; color:inherit;"><img src="img/logo.png" width="70" style="vertical-align: middle"> <span style="vertical-align: middle">4VIDIA 🔗</span></a>


> **4VIDIA** (NVIDIA처럼 떡상하자!)   
> 고성능 검색 엔진과 LLM을 결합하여 지능형 도서 탐색 경험을 제공하는 **MSA 기반 온라인 커머스 플랫폼**입니다. 단순한 상품 판매를 넘어, 데이터 기반의 정교한 큐레이션을 통해 사용자 경험(UX)을 극대화하는 것을 목표로 합니다.


[//]: # (팀소개, 담당파트)
## 🧑‍💻 Team
<div align="center">

|                                         고나영                                         |                                      김영재                                      |                                        김성우                                         |                                         나우림                                         |
|:-----------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|:----------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------:|
| <img width="150" src="https://avatars.githubusercontent.com/u/133228490?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/88365662?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/52788173?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/169413654?v=4"/> |
|                                      🛒 장바구니, 🅿️ 포인트                                        |                                 📚 도서, 🔍 검색                                  |                                       🍀 쿠폰                                        |                                        👤 회원                                        |

|                                      류지강                                       |                                      배종옥                                       |                                        박상민                                         |                                         정예림                                         |
|:------------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------:|
| <img width="150" src="https://avatars.githubusercontent.com/u/104420236?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/170800055?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/27434877?v=4"/> | <img width="150" src="https://avatars.githubusercontent.com/u/133829981?v=4"/> |
|                                    👤 회원                                     |                                ⚙️ 인프라, 🔒 인증/인가                                |                                    📚 도서, 🔄 배치                                    |                                       💰 주문, 결제                                         |

</div>

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>



[//]: # (레포지토리 주소)
## 🔗 Repositories

<div align="center">

|        Service        | Description                       | Repository 🔗                                                                                                                                                                         |
|:---------------------:|:----------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     🧭 **Eureka**     | 마이크로서비스 간 **서비스 등록 및 탐색**         | [![Repo](https://img.shields.io/badge/GitHub_Repository-Discovery-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-discovery)                  |
|    🌐 **Gateway**     | 요청 라우팅, 필터링, 인증 연계 처리             | [![Repo](https://img.shields.io/badge/GitHub_Repository-Gateway-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-gateway)                      |
|     🖥️ **Front**     | 사용자 UI 및 화면 렌더링 (Thymeleaf 기반)    | [![Repo](https://img.shields.io/badge/GitHub_Repository-Front-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-front)                          |
|    📚 **Backend**     | 도서, 장바구니, 주문, 회원 등 **핵심 비즈니스 로직** | [![Repo](https://img.shields.io/badge/GitHub_Repository-Book_Store_Service-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-bookstore-service) |
|      🔒 **Auth**      | JWT 기반 인증·인가 및 사용자 인증 처리          | [![Repo](https://img.shields.io/badge/GitHub_Repository-Auth-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-auth)                            |
| 🍀 **Coupon Service** | 쿠폰 발급·적용·만료 관리                    | [![Repo](https://img.shields.io/badge/GitHub_Repository-Coupon_Service-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-coupon-service)        |
| 🔄 **Batch Service**  | 정산, 만료 처리 등 **스케줄링 배치 작업**        | [![Repo](https://img.shields.io/badge/GitHub_Repository-Batch_Service-181717?style=flat-square&logo=github)](https://github.com/nhnacademy-be12-4vidia/4vidia-batch-service)          |

</div>

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>




[//]: # (아키텍처)
## 🌐 Micro-Service Architecture
![아키텍처](img/architecture.png)

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>




[//]: # (ERD)
## ERD (Entity-Relationship Diagram)
[📎 4VIDIA ERD 구조도](https://www.erdcloud.com/d/RBnydpYKLrRgfjN6t)
![아키텍처](img/erd.png)

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>



## 🚀 서비스 주요 기능 (Features)

* **도서 관리 및 검색:** Elasticsearch를 활용한 고성능 도서 검색 및 상세 정보 제공
* **회원 및 인증/인가:** JWT 기반의 안전한 회원가입, 로그인, 정보 관리
* **장바구니 및 주문:** 상품 담기, 주문 생성 및 결제 연동
* **쿠폰 및 이벤트:** Redis를 활용한 실시간 쿠폰 발급 및 재고 관리

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>






## 💡 Key Differentiation (프로젝트 차별점)

### 1️⃣ 하이브리드 검색 및 지능형 큐레이션
단순 키워드 매칭의 한계를 극복하기 위해 **Elasticsearch(Lexical)** 와 **LLM(Semantic)** 을 결합한 하이브리드 검색 시스템을 구축했습니다.
* **리랭커(Re-ranker) 서버 운용:** 1차 선별된 도서 데이터와 검색어 간의 연관성을 재계산하여, 사용자의 의도에 가장 부합하는 최상위 결과를 도출합니다.
* **LLM 추천 사유 생성:** 검색 결과와 도서 정보를 분석하여 "사용자가 왜 이 책을 읽어야 하는지"에 대한 맞춤형 큐레이션을 제공합니다.

### 2️⃣ 비용 효율적인 AI 아키텍처
LLM 도입 시 발생하는 API 호출 비용과 응답 지연 문제를 기술적으로 해결했습니다.
* **시맨틱 캐싱(Semantic Caching):** 벡터 유사도 기반 캐싱 전략을 도입하여, 동일하지 않은 검색어라도 의미가 유사하면 캐시를 활용함으로써 LLM 토큰 비용을 절감했습니다.
* **비동기 백그라운드 캐싱:** 일반 검색 시 AI 결과를 선제적으로 생성하는 비동기 처리를 통해 사용자 체감 응답 속도를 극대화했습니다.

### 3️⃣ 고가용성 마이크로서비스(MSA)
시스템의 확장성과 유연성을 위해 **Spring Cloud** 기반의 마이크로서비스 아키텍처를 채택했습니다.
* **독립적 도메인 설계:** 도서, 주문, 쿠폰, 인증 등 핵심 도메인을 분리하여 특정 서비스 장애가 시스템 전체로 전파되는 것을 방지했습니다.
* **대규모 트래픽 대응:** **Redis** 기반의 분산 락과 재고 관리, **Spring Batch**를 이용한 대용량 데이터 처리를 통해 시스템 안정성을 확보했습니다.

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>





## 🧩 핵심 트러블 슈팅 (Technical Problem Solving)

**'AI 검색 최적화'** 과정을 중심으로 정리한 문제 해결 사례입니다.

| 구분 | 내용                                                                                                                                                                                                                                                   |
|:---:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Issue** | **LLM(Gemini) API 토큰 고갈 및 비용 최적화 필요** <br> - 크롤링 봇의 무분별한 검색 요청으로 인한 토큰 할당량 조기 소진 <br> - "스프링 기초" vs "SpringBoot 입문" 등 동의어 검색 시 캐시 미스 발생                                                                                                              |
| **Analysis** | **기존 문자열 캐싱의 한계** <br> - 단순 Key-Value(String) 캐싱은 자연어의 의미적 유사성을 판단하지 못해 불필요한 LLM 호출 중복 발생                                                                                                                                                            |
| **Action** | **시맨틱 캐싱(Semantic Caching) & 비동기 파이프라인 구축** <br> 1. **벡터 유사도 판별**: 사용자 검색어를 임베딩하여 Redis 내 캐시와 코사인 유사도(Threshold 0.75) 비교 <br> 2. **리랭커(Re-ranker)**: 모델을 통한 결과 연관성 재정렬로 정확도 보정 <br> 3. **비동기 캐싱**: 일반 검색 시 백그라운드에서 AI 결과를 선제적 생성하여 'Zero-wait' 응답 구현 |
| **Outcome** | **비용 절감 및 검색 성능 극대화** <br> - LLM API 호출 횟수 절감 및 응답 속도 대폭 개선 <br> - 데이터 축적에 따른 캐시 히트율 선순환 구조 확립                                                                                                                                                       |

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>






[//]: # (사용 기술)
## 🛠️ Tech Stack

### 💻 Develop

<div>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=Thymeleaf&logoColor=white">
</div>

### 🧪 Testing & Quality

<div>
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white">
  <img src="https://img.shields.io/badge/AssertJ-2E8B57?style=for-the-badge">
  <img src="https://img.shields.io/badge/Mockito-2E8B57?style=for-the-badge">
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white">
</div>

### 🚀 Infra & CI/CD

<div>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Git%20Flow-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>





## 💻 Main function

프로젝트의 주요 기능 화면 이미지

> 1) 메인화면 & 로그인

| 메인 화면                                             | 로그인                                              | 회원가입                                                 |
|---------------------------------------------------|--------------------------------------------------|------------------------------------------------------|
| <img src="img/main.png" alt="메인 화면" height="200"> | <img src="img/login.png" alt="로그인" height="200"> | <img src="img/register.png" alt="회원가입" height="200"> |

<br>

> 2) 검색기능 & 도서화면

| 일반 키워드 검색 결과                                                      | 재검색 결과                                                     | AI검색 결과                                                 | 도서 상세                                                    | 리뷰 요약                                               |
|-------------------------------------------------------------------|------------------------------------------------------------|---------------------------------------------------------|----------------------------------------------------------|-----------------------------------------------------|
| <img src="img/search-common.png" alt="일반 키워드 검색 결과" height="200"> | <img src="img/search-retry.png" alt="재검색 결과" height="200"> | <img src="img/search-ai.png" alt="AI검색 결과" height="200"> | <img src="img/book-detail.png" alt="도서 상세" height="200"> | <img src="img/review.png" alt="리뷰 요약" height="200"> |

<br>

> 3) 마이페이지

| 회원정보                                                | 주소관리                                                   | 좋아요 목록                                                  | 주문 목록                                                   |
|-----------------------------------------------------|--------------------------------------------------------|---------------------------------------------------------|---------------------------------------------------------|
| <img src="img/info.png" alt="회원정보 화면" height="200"> | <img src="img/address.png" alt="주소관리 화면" height="200"> | <img src="img/like-list.png" alt="좋아요 목록" height="200"> | <img src="img/order-list.png" alt="주문 목록" height="200"> |

| 반품조회                                               | 포인트 내역 조회                                              | 쿠폰 조회                                               |
|----------------------------------------------------|--------------------------------------------------------|-----------------------------------------------------|
| <img src="img/refund.png" alt="반품조회" height="200"> | <img src="img/point.png" alt="포인트 내역 조회" height="200"> | <img src="img/coupon.png" alt="쿠폰 조회" height="200"> |

<br>

> 4) 주문 화면

| 장바구니                                             | 주문                                              | 주문 상세                                                     |
|--------------------------------------------------|-------------------------------------------------|-----------------------------------------------------------|
| <img src="img/cart.png" alt="장바구니" height="200"> | <img src="img/order.png" alt="주문" height="200"> | <img src="img/order-detail.png" alt="주문 상세" height="200"> |

<br>

<!-- Top Button -->
<div align="right">
<p style="background: gray; width: 28px; height: 28px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;"><a href="#top" style="color: white; text-decoration: none;">▲</a></p>
</div>