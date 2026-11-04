# SKALA DevOps 학습 자료

[himang10/skala-devops](https://github.com/himang10/skala-devops)를 포크한 강의·실습 자료입니다. 이 저장소에 포함된 예제 코드와 배포 구성을 독자적으로 설계한 개인 프로젝트로 소개하지 않습니다.

## 포트폴리오에서의 위치

AI·데이터 분석 프로젝트를 서비스로 연결하기 위한 배포 기초 학습 자료입니다. 개인 구현 결과는 [배터리 수명 분석](https://github.com/ncelinelee/mini_project_data), [Paweather](https://github.com/ncelinelee/Paweather), [Spring 주문 API](https://github.com/ncelinelee/myfirst-api-server)에서 확인할 수 있습니다.

## 자료 구성

| 디렉터리 | 주제 |
| --- | --- |
| `00.sample-container/` | 컨테이너 기초 |
| `01.spring-backend-v1.0/` | Spring Boot·JPA·헬스체크 예제 |
| `02.build-platform/` | 빌드 환경 |
| `03.helm/`, `03.helm-umbrella/` | Helm 배포 구성 |
| `04.jenkins/` | Jenkins 예제 |
| `05.argocd/` | Argo CD 예제 |

강의 환경의 레지스트리·네임스페이스·설정이 포함되어 있습니다. 해당 클러스터 접근 권한이 없는 환경에서 그대로 배포되는 프로젝트는 아닙니다. 개인 클러스터에서 재현한 운영 성과나 장애 대응 기록은 현재 이 저장소에서 주장하지 않습니다.
