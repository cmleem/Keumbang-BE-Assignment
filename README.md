## 실행 환경

- Spring Boot
- MariaDB
- Redis
- gRPC

<br>

## 폴더 설명

- keumbang-auth: 인증 서버
- keumbang-resource: 자원 서버
- 서버 간 통신은 gRPC를 사용합니다.

<br>

## Quick Start

1. 현재 레포지토리를 clone 혹은 download 합니다.
   
2. 레포지토리의 root directory 에서 다음과 같은 명령어를 입력합니다.
   ```console
   git submodule init
   git submodule update
   ```

3. `.env.example`파일을 참고하여 `.env` 파일을 작성합니다. 

4. 각 디렉토리에서 Spring Boot 프로젝트를 빌드합니다.(아래는 예시)
   - Unix 계열
   ```console
   /keumbang-auth$ ./gradlew build
   ```
   
   - Windows
   ```console
   \keumbang-auth> .\gradlew.bat build
   ```

5. java -jar 명령어로 각 디렉토리에서 빌드된 파일을 실행합니다.
   이 때, 명령은 반드시 각 디렉토리의 최상단에서 실행합니다.

<br>

