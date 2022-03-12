### 💡Summary of Studies for Springboot

- JUnit을 활용한 테스트 코드를 통해 개발단계 초기 문제 발견 파악
- 객체와 RDB를 중간에서 서로 매핑해주는 JPA 사용
- JPA를 한 단계 더 추상화 시켜 개발 용이성을 상당히 올려주는 인터페이스인 Spring Data JPA 사용
- 인메모리 관계형 데이터베이스인 h2 활용하여, 최소한의 리소스로 실행 가능한 경량 DB로서 테스트
- 서버 템플릿 엔진으로, 수많은 언어를 지원하는 가장 심플한 템플릿 엔진인 머스테치 사용
- 부트스트랩, 제이쿼리 등 프론트엔드 라이브러리 활용을 위한 외부 CDN 사용
- Authentication과 Authorization 기능을 가진 프레임워크인 Spring security와 OAuth 2.0으로 로그인 기능 구현
- 구글 로그인 API & 네이버 로그인 API 활용

### 💡Summary of Studies for AWS

- Infrastructure as a Service(IaaS) 클라우드 사용
- AWS에서 제공하는 성능, 용량 등을 유동적으로 사용할 수 있는 서버인 EC2 인스턴스 생성
- Amazon Linux 2 AMI, t2 micro 프리티어 버전 사용
- AWS에서 지원하는 클라우드 기반 관계형 데이터베이스인 RDS 활용을 통해 서버 환경 구축
- DBMS로는 MariaDB 사용
- git clone을 통해 받은 프로젝트를 EC2 서버에 배포

### 🧨 Stop & Cause

- “스프링부트와 aws로 혼자 구현하는 웹서비스” 책을 참고하여 공부를 진행하였고, 스프링부트까지 완성하여 24시간 무중단 웹 사이트 배포를 목표로 하였음.
- 9장부터 11장은 엔진 버젼이 달라서 프로젝트 진행의 어려움을 겪게 되어 중단하였지만, 블로그에는 책에 있는 내용을 정리할 예정.
