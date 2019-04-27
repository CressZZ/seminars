# 0. 개요
- 일시 : 2019년 04월 27일
- 장소 : 한국마이크로소프트 
- Global Azure Bootcamp 2019

# 1. Apache Airflow
- 아파치 에어플로우를 활용한 워크플로우 메니져먼트 활용 및 파이프라인 구성, 프로젝트 적용 및 삽질기
- 발표자 : 배준현 / 클라우드 메이트 Azure 사업부, 우분투한국사용자 그룹, 코딩이랑 무관합니다만 운영진

## 스케쥴러 
- Cron?
    - /usr/local/sbin/backup.sh 
- Cron의 문제점들
    - 언제완료 되었는지 모른다. 
    - 선행작업 완료가 필요한 경우에는 대충 선행이 언제 끝날거라고 예상하고 작업해야 한다. 

## 스케쥴러 vs 워크플로우메니저

## Apache Airflow
- 아파치 제단에서 진행중인 프로젝트 
- 아직 `incubating`단계이며(아직 정식버전이 아닌듯), 꾸준히 발전시키고 있다.
- GUI의 대쉬보드를 제공한다. 
- 병렬 형태등의 순서를 정할 수 있다. 
- 어떤 Task에서 시간을 많이 잡아 먹는지에 대해 대쉬보드에서 제공한다. 

## 파이썬 환경에서 Apache Airflow
- `pip install apche-airflow`의 형식처럼 간단히 설치 할 수 있다. 

## task를 DB에 몰어 넣고 Task를 돌린다.
- SQlite를 사용하고 있다. (싱글쓰레드)
- extenstion을 설치하여 멀티쓰레로 변경할 수 있다.


# 2. Window 환경에서의 kubernetes 
- 발표자 : 남정현 / 한국 Azure 사용자, DevOps 개발자

## Windows Workload
- DEVSISTERS에서는 게임 서버 개발과 테스트 자동화를 위하여 Kubernetes를 성공적으로 도입하였다. 
- 하지만 Kubernetes의 windows OS 지원은 1.5버전이 되어서야 지원하기 시작했다. 
- 2019년 2월에 환경을 완료 하였다. 

## 컨테이너화를 하는 이유
- 일관성 
- 효율성

## 오케스트레이션의 필요성
- 켄터에너화를 하는 것으로는 끝나지 않는다. 
- 여러 컨테이너 호스트에 표율적으로 컨테이너를 배포하고, 상황에 따라 제어하는 기술이 필요하다. 
- 이것을 Kubernetes가 시장을 장악했다. 

## Kubernates
- 앱을 빠르고 예측 가능하게 배포
- 즉시 앱을 스케일 업/다운
- 중단 없이 새로운 기능 배포
- 하드웨어 사용을 필수 리소스로만 제한 
- 이식가능 : 퍼블릭, 프라이빈, 하이브리드, 멀티 클라우드
- 확장 가능 : 모듈식, 플러그 가능, 훅 연결 가능, 구성가능
- 자가 치유 : 자동배정, 자동재시작, 자동복제, 자동스케일링

## Linux Kubernetes와의 차이점
- HCS, HNS를 지원하는 컨테이너 런타임이 필요
    - ContainerD 출시 전까지는 Windows Server용 Docker Enterprise Edition을 기반으로 함
- Kube-Proxy가 컨테이너가 아닌 별도 바이너리로 Kubelet과 같은 위치에서 실행되어야 함
    - Kuber-Proxy를 별도의 NT 서비스로 실행해야 하고, KLbelet시작 후 별도 실행이 필요함 

## Windows Kubernetes를 설치하는 방법
- 쉬운 방법 : Azure + AKS Engine
- 다른 방법 : ㄱRancher 2.x의 Windows지원 활용

## Kubernetes의 동작원리를 체험하고 직접 살펴보려면
- `Kubernetes the hard Way`

## 특징
- HCS(Host Compute Service)와 HNS(Host Network Service)가 핵심

## AKS Engine(Azure Kubernetes Service)
- MS가 제공하는 Azure Kubernetes Service를 실제로 만들기 위해 사용하는 핵심 도구
- Azure CLI를 이용하여 AKS fmf aksemsms rjtrhk ehddlfgks rlsmddmf wprh

