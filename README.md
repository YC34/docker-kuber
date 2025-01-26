# 2025-01-25 Docker kubernetes study

## 1. Docker

### 1.1. Docker 명령어
- example
    - docker build : 베이스 이미지에 기능을 추가하여 새로운 이미지를 만들떄 사용.
    - docker pull : 레지스트리에서 이미지를 로컬에 다운로드할 떄 사용 한다.
    - docker run : 이미지를 실행할 떄 사용 한다.
    - docker ps : 실행중인 컨테이너를 조회할 떄 사용 한다.
    - docker stop : 실행중인 컨테이너를 중지할 떄 사용 한다.
    - docker rm : 컨테이너를 삭제할 떄 사용 한다.
    - docker rmi : 이미지를 삭제할 떄 사용 한다.
    - docker images : 이미지를 조회할 떄 사용 한다.
    - docker push : 이미지를 레지스트리에 업로드할 떄 사용 한다.    
- 레지스트리 란?
    - 이미지를 저장하고 관리하는 저장소 이다.
    - 레지스트리에 이미지를 업로드하면 다른 사용자가 이미지를 다운로드하여 사용할 수 있다.
    - 레지스트리는 주로 클라우드 플랫폼에서 제공하는 서비스를 사용한다.
    - 대표적인 레지스트리로는 Docker Hub, AWS ECR, Google Container Registry 등이 있다.
    - 레지스트리는 private 레지스트리와 public 레지스트리로 나뉜다.
    - private 레지스트리는 기업 내부에서 사용하는 레지스트리이다.
    - public 레지스트리는 외부에서 사용하는 레지스트리이다.
