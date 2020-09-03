# Development Log

> ### 2020/08/31 MON   
> - BlockChain Skeleton Code - git clone Complete.   
> - README.md Updated.   
> - Virtual Box 설치 완료   
> - Vagrant 설치 완료   
> - Virtual Box, Vagrant 연동 완료   
> - 2 Node (eth0, eth1) 생성 완료   
> - Virtual Box, Vagrant 구동 확인 완료   

> ### 2020/09/01 TUE   
> - eth0, eth1 노드 설정 완료   
> - Geth 설치 완료.   
> - 환경변수 설정 -> 오류로 인해 중단   
> - Geth 설정 완료.   
> - 마이닝 완료   
> - 마이닝 후 잔액 확인 -> 오류   
> - 노드 연결 -> 오류   

> ### 2020/09/02 WED   
> - skeleton code FrontEnd 실행 완료   
> - skeleton code BackEnd JRE 버전 동기화 완료   
> - BackEnd에 Getter, Setter 추가 완료.   

> ### 2020/09/03 THUR   
> - skeleton code FrontEnd config 수정 완료   
> - Geth 환경변수 설정 완료
> - 마이닝 후 잔액 증가 안되는 오류 해결
> - 노드 연결 완료
> - 트랜잭션 설정 진행중...


## 목차
- [개요](#개요)
- [기능](#기능)
- [유사 서비스](#유사-서비스) 
- [향후 전망](#향후-전망)
- [기술 스택](#기술-스택)
- [기술 설명](#기술-설명)
	- [ERD](#erd)
	- [디렉토리 구조도](#디렉토리-구조도)
	- [기타](#기타)
- [테스트 방법](#테스트-방법)

## 개요
> 가상 머신을 활용하여 개인적으로 실습할 수 있는 이더리움 네트워크 환경을 구축함.  
> 이더리움 프로토콜의 공식 구현체인 Go-Ethereum을 설치하고 이더리움 환경에서 수행할 수 있는 다양한 커맨드를 확인하며 블록체인의 구조를 익힘   
> 스마트 컨트랙트를 작성하는 방법을 학습함으로써 블록체인의 구성과 동작 원리, 활용 방법을 익힘   
> 제공된 스켈레톤 프로젝트를 통해 블록체인 환경을 웹과 어떻게 연동할 지 알 수 있음   

## 기능
> 프로젝트의 기능들을 설명해주세요  
> 스크린샷이나 gif등으로 한눈에 볼 수 있게 하면 더 좋습니다

## 유사 서비스
> #### [헥슬란트의 블록체인 서비스 '옥텟'](https://octet.hexlant.com/)   
> ![옥텟 이미지](https://plog-image.s3.ap-northeast-2.amazonaws.com/%EC%98%A5%ED%85%9F.PNG)    
> ![](https://plog-image.s3.ap-northeast-2.amazonaws.com/%EC%98%A5%ED%85%9F2.PNG)   
> ![](https://plog-image.s3.ap-northeast-2.amazonaws.com/%EC%98%A5%ED%85%9F3.PNG)   
> ![](https://plog-image.s3.ap-northeast-2.amazonaws.com/%EC%98%A5%ED%85%9F4.PNG)   
> 헥슬란트의 블록체인 서비스 '옥텟'은 

## 향후 전망 
> 스마트 컨트랙트가 아직 불안정한 부분이 있습니다.   
> 노드끼리 연결이 되었으나 송금을 할때 pending에서 멈추는 경우가 가끔 생겨서 다음 프로젝트에는 좀더 꼼꼼히 공부한 후 해결할 예정입니다.   

## 기술 스택
> Oracle VM VirtualBox, Vagrant로 가상머신을 통해 Ubuntu 환경을 구성하였습니다.   
> Go-Ethereum, Solidity 등으로 블록체인 이더리움을 구현하였습니다.   
> BackEnd는 Spring STS로 구현하였습니다.   
> DB는 Mysql로 연결하였습니다.   
> FrontEnd는 Vue를 사용하였습니다.   


## 기술 설명

### ERD
> DB 및 백엔드를 구현할 때 ERD를 그려보고 리드미에 남겨주세요

### 디렉토리 구조도
> 폴더 구조가 어떻게 되는지 폴더, 파일별 역할들을 간략하게 적어주세요  
> 너무 자세히 적을 필요는 없습니다

### 기타
> 이외에도 프로젝트를 이해하기 위해 필요한 것들을 적어주세요 (팀별 개발표준, API Documentation 등등...)

## 테스트 방법
> 프로젝트를 배포한 url과 테스트하기 위한 계정 ID/PW를 적어주세요