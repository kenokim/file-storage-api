# file-storage-api
## 기능 명세 v1
- 파일을 API 로 받아서 S3 에 업로드하는 서비스이다.
- S3 에는 파일의 sha256 을 경로로 저장한다.
- 파일 사이즈는 0~200MB 까지 지원 가능해야 한다.
- 파일의 메타데이터는 RDS 에 저장한다.
## 아키텍처
<img src="https://github.com/user-attachments/assets/f4bd58d5-4e69-4ca5-9ffb-1781da56b85c" alt="아키텍처" width="600"/>
