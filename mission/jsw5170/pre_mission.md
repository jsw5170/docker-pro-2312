# 사전미션


### 1.컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
컨테이너란 소프트웨어가 현재의 컴퓨팅 환경에서 다른 환경으로 이동하더라도 안정적으로 실행되도록 하기 위해 나온 개념으로 어플리케이션을 구동하는 환경을 격리한 공간이다.

### 2.도커란 무엇입니까? (100자 이내로 요약)
도커란 오픈소스 기반 컨테이너 관리 기술로 응용프로그램들을 컨테이너 안에 배치시키는 일을 자동화하는 프로젝트이며 실행되는 앱과 구동하는 시스템이 분리된 형태로 스택 구현하다.

### 3.도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
도커 파일은 도커 이미지를 빌드하는 방법을 정의하는 스크립트이다. 도커에서 환경 정보를 저장하는 파일을 도커 파일이라고 하며 도커 파일에는 컨테이너 구둥에 필요한 정보가 작성되어 있다.   
도커 이미지는 컨테이너 실행에 필요한 모든 파일과 설정값을 지닌 것으로 더 이상의 의존성 파일을 컴파일하거나 추가로 설치 할 필요 없는 상태의 파일을 의미한다.   
도커 컨테이너는 이미지를 실행한 상태로 응용프로그램의 종속성과 함께 응용프로글매 자체를 패키징 또는 캡슐화하여 격리된 공간에서 프로세스를 동작시키는 기술이다.
도커 컨테이너는 실행 중인 이미지 인스턴스로 간주한다.   
도커 파일을 빌드해서 이미지를 생성하며 이미지를 동적인 형태로 변경한 것이 컨테이너이다.   
Dockerfile --(Build)--> Image --(Create)--> Container
