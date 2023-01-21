# springBoot-jpa-hello-shop

## 강의명
실전! 스프링 부트와 JPA 활용1 - 웹 애플리케이션 개발(김영한)

## 서론 
스프링부트는
복잡하고 여러운 스프링기술을 쉽게 사용할 수 있도록 해준다. + jpa는 java orm 표준 기술    
두 기술을 함께 사용하면 높은 개발생산성을 유지하면서 빠르게 웹애플리케이션을 개발 가능.  
두 조합으로 프로젝트트 진행하는 것이 세계적인 추세이다.  

## 강의목표
스프링부트 + jpa로 실무에서 웹 애플리케이션을 개발 할수 있도록함.  
1. 실무에 가까운 복잡한 예제 준비  
2. 결제, 정산, 주문 서비스 등을 개발하면서 얻은 실무 노하우 전수  

## 전체구성
1편 - 웹 애플리케이션 개발  
2편 - api 개발과 성능 최적화   

### 1편 웹 애플리케이션 개발 

- 프로젝트 환경설정  
스프링부트, jpa, hibernate, gradle, tomcat, thymeleaf  

- 요구사항 분석  
1. 회원기능 - 회원가입, 회원목록  
2. 상품기능 - 상품등록, 상품목록  
3. 주문기능 - 상품주문, 주문내역  

- 도메인 모델 설계   

![크기변환 크기변환 001](https://user-images.githubusercontent.com/48856906/213454636-141f822a-2d35-4ecc-acc2-4ed2b78ee918.png)

- 엔티티 설계  

![스크린샷 2023-01-17 오후 12 33 24](https://user-images.githubusercontent.com/48856906/212805568-42c51bcd-7723-4e83-bc3f-5e75fdd30bc3.png)

- 테이블 설계  

![스크린샷 2023-01-17 오후 12 33 41](https://user-images.githubusercontent.com/48856906/212805574-c7d92ab3-16e8-4a2f-8064-058792bc2685.png)

- 애플리케이션 아키텍처 구성  

![크기변환 002](https://user-images.githubusercontent.com/48856906/213454649-8bec543b-fbd1-4406-9ecb-9a740eb5424e.png)

- 핵심 비즈니스 로직 개발  
1. 회원, 상품, 주문 도메인 개발  
2. 핵심 비즈니스 로직 개발  
3. 테스트 케이스 검증  
4. 도메인 주도 설계 이해  

- 웹계층 개발  

![스크린샷 2023-01-17 오후 12 35 13](https://user-images.githubusercontent.com/48856906/212805606-1f6e0218-c381-40dd-ba31-d1cb0914b7ff.png)  
![스크린샷 2023-01-17 오후 12 35 20](https://user-images.githubusercontent.com/48856906/212805612-b50894d6-da58-49ac-b704-7e439fb4e69f.png)


### 2편 - api 개발과 성능 최적화

- Rest API 개발   
1. 등록, 수정, 조회 REST API 개발  
2. API 개발 실무 노하우 전수   

- 성능 최적화  
1. jpa극한의 조회 성능 최적화 노하우 전수  
2. 복잡한 예제를 6단계로 성능 튜닝  
3. 실무 JPA 성능 문제의 90% 해결  
