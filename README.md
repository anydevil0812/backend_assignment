<h2>인턴 과제 - 백엔드 인프라 구성</h2>

![1](https://github.com/anydevil0812/backend-assignment/assets/109947297/3e465702-715b-4fb7-8bdf-eeff2c432d96)
- 진행 기간 : 2023.8.23 ~ 2023.9.8
### 결과 화면
<img width="1280" alt="2" src="https://github.com/anydevil0812/backend_assignment/assets/109947297/991095f0-2a72-4bc4-b7a8-8cec32327573">

### 참고 사항
- Flutter Project(agent_sample, web_manager_sample)의 경우에는 용량이 큰 build와 .dart_tool를 제외하였기에 각 폴더의 README.md 파일을 참고하여 Docker Compose로 컨테이너 생성 전에 build 및 dependency 세팅 필수!
- Spring Boot Project의 경우 용량이 큰 build를 제외하였기에 gradlew.bat build로 app.jar 파일 생성 필수! (Redis 및 DB 설정이 Docker Compose에서 지정한 컨테이너명으로 되어 있기 때문에 해당 명령으로 jar 파일 생성됨에도 실행 테스트로 인하여 build failed가 나옴)
