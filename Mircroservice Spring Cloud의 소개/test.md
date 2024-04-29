<h3>Cloud Navtive Architecture</h3>

- 확장 가능한 아키텍처
    - 시스템의 수평적 확장에 유연
    - 확장된 서버로 시스템 부하분산, 가용성 보장
- 탄력적 아키텍처
    - 서비스 생성 - 통합 - 배포, 비즈니스 환경 변화에 대응하는 시간 단축
    - 분할된 서비스 구조
    - 무상태 통신 프로토콜
    - 서비스의 추가 및 삭제 자동으로 감지
    - 변경된 서비스 요청에 따라 사용자 처리
- 장애 격리
    - 특정 서비스에 오류가 발생해도 다른 서비스에 영향을 주지 않음
 


<h3>Cloud Native Application</h3>
- CI/CD
  - CI(Continuuous Integration)
  - CD(Continuous Delivery, Deployment)
  - Pipe line
- DevOps
  - Development + QA + Operations
- Microservices
- Container 가상화
  - Traditional Deployment : 한 물리서버에서 여러 어플리케이션의 리소스를 할당하기 어려움
  - Virtualized Deployement : VM 간 애플리케이션을 격리하고 각각 리소스를 할당  (VMWare 등)
  - Container Deployment : 격리 속성을 완화하여 OS를 공유해 더 가볍게 어플리케이션 실행 가능 (도커)


<h3>Monolithic vs Microservice</h3>
- Monolithic : 일부 기능만 수정해도 전체 빌드 및 배포
- Microservice : 각 서비스
  
