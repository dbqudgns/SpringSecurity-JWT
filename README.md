# SpringSecurity-JWT
Spring Security - JWT 실습

### CORS(Cross-Origin Resource Sharing) 

- 교차 출처 리소스 공유
- 교차 출처 == 다른 출처 : 다른 출처에서 자원을 공유하는 정책

- 즉, CORS 설정이란 "도메인이 다른 서버끼리의 리소스 공유를 허용한다." 라는 뜻이다.

- 프론트엔드와 벡앤드가 협업하면서 각자 따로 서버를 띄우게 되었을 경우
- 서로 다른 React 서버(3000)와 Springboot 서버(8080)가 리소스를 주고 받으려 한다면 포트가 달라 브라우저가 서로 다른 출처로 판단해 CORS 위반 에러가 발생한다 !!
- 따라서, 백엔드 서버단에서 CORS 설정을 수행해야 한다. 
