# spring-cloud-config-propeties
스프링 클라우드 컨피그 프로퍼티 레파지토리.. ~~오타났네..~~
- 프로퍼티별 공통 부분을 가질수 있도록 구조화
  - common 부분은 모든 프로젝트에서 값을 읽도록 설정
  - profile을 세세히 구분한다면 나누기 가능
- properties 중복 시 우선 순위 
  1. {application}/{application}-{profile}.properties
  2. common/application-{profile}.properties
  3. {application}/{application}.properties
  4. common/application.properties