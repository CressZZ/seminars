# 참고 자료
https://baram-my.sharepoint.com/personal/jongin_designme_ai/Documents/Forms/All.aspx?cid=b2d1b275-ff5e-4962-8545-3bf3b4ee5b58&RootFolder=%2fpersonal%2fjongin_designme_ai%2fDocuments%2f%EA%B8%B0%EC%88%A0%20%ED%99%9C%EB%8F%99%2f%5b2019%2e3%2e30%5dAzure%20DevOps%20Launch%5b%EA%B3%B5%EC%9C%A0%5d&FolderCTID=0x0120007E7CA367CFE5384A9ED3B8662B5A7549

# 0. 환영사

# 1. Devops 혹시 나만 빼고 다하고 있는 건가?
- 발표자 : 김명신 
- https://dev.azure.com 

## Nearly 50% of the current S&P 500 will be replaced by 2026
- 2000년에서 2018년 까지 500위 순위의 회사가 바뀌었다. 
- 아마 8년 후(2026)에는 절반이 더 바뀔것이다. 
- 새롭게 부각되는 기업의 특징은 기술/`소프트웨어 개발의 역량`이 있다는 것이다. 

## Fast Curve Ball
- 빠르고 변화하는 것
### 움직이는 과녁 (뭘 공부해야 살아 남을 수 있는가?) 
- 뭘 공부 해야 하는 것인가가 항상 변화한다. 
### 빨리 빨리
- Accelerate - 세계적인 트렌득 된다. 

## 소프트웨어 출시의 패러독스 
- `혁신` : 빨리 소프트웨어를 출시해야 한다.  
- `신뢰` : 안정성 있는 소프트 웨어를 출시 해야 한다. 
### 소프트웨어의 출시가 느리다?
- 배포 주기가 길다.
    - 일반적으로 소프트웨어 만들고, 테스트 거치고 약 6주가 걸린다. 
- 개선하려면 오래 걸린다. 
- 변경시 실패율이 높다. 
- 복구 시간이 길다. 
    - 만약에 버그가 있었다. 그것을 복구하려면 시간이 오래 걸린다. 
### 왜 느린가? 
- 요구사항의 변화 
- 개발, 운영의 전문성, 역량 결여 
- 협업, 소통의 결여 : 운영, 사업, 기획등의 팀  
- 자동화된 과정, 절차, 체계, 시스템의 결여 

### 무엇을 개선할 것인가?
- 문화 
라- `과정/절차`
- 도구 

## DevOps
- Develop & Operating System

### 적용한 살례를 보니 
- 빨라진다. 
- 협업이 더 긴밀해 진다. 

### DevOps란 무엇인가?
- DevOps is the union of people, process, and products 
- 문화, 과정, 절차, 도구 

### Technical Approach
- Plan&Track
- Moditoring
- Deploy
- Source Control

## DepOps를 적용한다는 것은 
### 1) DevOps적 문화를 적용한다.
- Trust, Share, then Collaborate
- 개발자와 운영자가 공유할 수 있는 핵심이 있다. 

### 2) DevOps적 절차

### 3) DevOps적 도구

### DevOps의 도입 절차  
- Source Control 도입 
- 개발환경 통합 (OS 등) 
- 표준화된 기술 세트 
- ... 

## Azure DevOps에 대해 
- Azure Boards : jira/Github 같은거(?)
- Azure Pipelines
    - CI/CD 
- Azure Repos
    - Git : 관리 
- Azure Test Plans
- Azure Artifactes

## 가격 Azure DevOps Servies 
- 5명 이하의 조직이라면 무료. 그 이상이라면 35,000웜 정도 


# 2. Azure DevOPs, CI/CD를 위한 5개의 핵심 기능 살펴보기
- Azure DevOps의 CI, CD를 감당하실 수 있겠습니까? 어서 회사로 들이십시오
- DEMO위주의 발표

## DevOps를 시작하려면
### 지속적인 통합 (CI)
- 소프트웨어 개발 퀄리티와 속도를 향상 시킨다. 
- Azure Pipeline이나 Jenkins를 사용하여 매번 코드를 커밋할 때마다 클라우드에서 앱을 빌드한다면, 앱은 자동으로 빌드되고 테스트되기에, 버그는 더 빨리 빨견된다.
### 지속적인 딜리버리 (CD)

### CI/CD를 통한 지속적인 배포


### CI (Continuous Integration)
- 자동화된 테스트, 빌드
- 산출물은 빌드 아티팩트가 생성된다. 
- 버튼 안눌렀을때 자동

### CD (Continuous Delivery)
- 배포하는 프로세스
- 기존 시스템에 새로운 버전과 수정사항을 릴리즈
- 자동화된 릴리즈 파이프 라인 

### CI/CD 다시 이해하기 
- Build 파이프 라인 CI : 
    - 븰드 + 단위 테스트
- Release 파이프 라인 CD : 
    - 배포환경 프로비저닝 + 승인 + 배포 + UI테스트, QA테스트, 부하 테스트, 

## DevOps와 Azure
 - DevOps는 최종 사용자에게 가치를 지속적으로 전달하기 위해 필요한 프로세스, 도구, 사람의 결합니다. 

## Aure DevOps 종류
- Azure Boards - Jira
- Azure Repos - Github
- Azure Piplines - CI/CD
- Azure Test Plans - 테스트 도구
- Azure Artifacts - 버전?

## Azure 프레임워크 상에서의 DevOps
- 플래닝 & 추적, Code, 빌드/테스트, 배포, 운영, 모니터


## Demo
- 짱 재미 있었음


# ASW, dJango, python, Azure를 활요한 것 
- 발표자 : Azure microsoft MVP

## dJango 
- 파이썬 백엔드 프레인 워크

## AWS
- 사용할 것 : S3, Elastic Beanstalk

## 시나리오
- github에 코드 푸쉬
- CI 트리거
- CD 트리거
- 릴리즈 (스테이징) -> S3
- 릴리즈 (프로덕션) -> Beans Talk
- 확인

## 소스코드 (깃험) 연결 하는 방법
- Azure CI 단계에서 연결 

## Demo
- 진행함

# 4. 디자인미에서 Azure 사용하기
- 발표자 : 디자인미 대표

## 코드베이스 공유를 위하여 .NET 을 사용하고 있음
- 코드 베이스를 다양한 플랫폼 (웹, 맥, 윈도우, 아이폰, 안드로이드)에서 공유 할수 있다. 

## 하지만 크로스 플랫폼에 대한 배포는 어떻게 하는가?
### 문제점
- Nuget 패키지를 업데이트 했는데 어느 프로젝트에서 호환이 안된다면?
- 특정 로직이 특정 플랫폼에서 의도치 않게 돌아간다면?
- 리팩터링 했는데 일부 프로젝트에 적용이 안된다면?
- 각 플랫폼에 대한 모니터링은?

## 그래서 선택한 Azure DevOps
- 코드를 올리면 수많은 플랫폼에 빌드, 테스트 배포
- Azure Web App, Functions, Window, iOS, Android 등 지원하고자 하는 모든 플랫폼 빌드, 배포 가능
- 서버와 클라이언트까지 배포되어 새로운 로직을 모든 곳에서 테스트 

## Visual Studio App Center
- 빌드된 iOs, Android, Windows 앱들을 App Center 로 자동으로 보내 각 플랫폼에 배포 

## 빌드 혹은 테스트 실패로 걸러지는 많은 오류
- 빌드 실패
- 테스트 실패
- 사용 테스트 실패

## DEMO

## 운영에서의 문제
### 빌드 실패 
- 코드 베이스로 병합되지 않은 새로운 pull request가 빌드 안됨. 
- 제 프로젝트에서는 빌드가 잘되는데, Azure DevOps에서는 빌드가 실패했어요!
### 테스트 실패
- 팀원들은 서로의 모든 코드를 파악하지 못함. 
- 하지만 팀의 코드 베이스는 팀원들 코드들이 연결되어 있다. 
- 또한 특정 기능 개발을 위한 코드 작업을 하다 다른 로직에 이슈 및 균열을 일으키는데 이를 파악하지 못함
- 코드 작업으로 특정 기능은 개선되었지만, 다른 기능들이 버그 및 오작동하는 결과를 낳는 다면 코드 작업은 의미가 있었을까?

## 문제 해결을 위한 방안
### 브랜치 정책
### 풀리퀘 정책 (리뷰어, 검토자)
### 코드리뷰
### Azure Board와 Pipeline은 단순히 탭으로나뉜가 아니라 서로 연동되어 있음





















