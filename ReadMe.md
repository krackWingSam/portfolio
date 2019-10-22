# 포트폴리오
## 목차
## 1. [참여 프로젝트](##-1.-참여-프로젝트)

### ㄱ. [방송 및 공연 환경에서의 각 전문분야의 유기적인 활동을 지원하기 위한 프로그램 군의 개발](####-ㄱ.-방송-및-공연-환경에서의-각-전문분야의-유기적인-활동을-지원하기-위한-프로그램-군의-개발)
### ㄴ. [영상, 음성 분석기술을 이용한 고객 관리 솔루션 시스템](####-ㄴ.-[영상,-음성-분석기술을-이용한-고객-관리-솔루션-시스템])
### ㄷ. [ASMR Director]()
### ㄹ. [Chord Player]()
### ㅁ. [Stdio Recording]()
### ㅂ. [Karaoke Studio]()
### ㅅ. [Whyme]()
### ㅇ. [myOndo]()
### ㅈ. [IMU를 활용한 측위 알고리즘 / Firmware 개발]()

## 2. [수상 실적]()
---

## 1. 참여 프로젝트
#### ㄱ. 방송 및 공연 환경에서의 각 전문분야의 유기적인 활동을 지원하기 위한 프로그램 군의 개발
* 프로젝트 개요 : 
    + 방송 및 공연 환경에서의 각 전문분야의 유기적인 활동을 지원하기 위한 프로그램 군(5개)의 개발(OSX/iOS 환경)
    + SE(Sound Engine)
        - 소리의 입/출력 관리
        - 최대 16채널 관리
    + VE(Video Engine)
        - 영상의 입력 및 처리
        - GVE 로 입력된 영상을 송출
    + GVE(Graphic Visualization Engine)
        - 각 VE로부터 송출된 영상의 입/출력 관리
        - 최대 8 채널 관리
    + IS(Integraed System)
        - 각각의 SE, VE, GVE 관제
        - 실 공연에 사용하기위한 실행 Queue 관리
    + RCI(Remote Control Interface)
        - iOS 환경에서 IS 와 무선으로 연동되는 컨트롤 인터페이스
    
* 기여 :
    + OpenFrameworks를 이용한 4개 어플리케이션 개발(SE, VE, GVE, IS), iOS 어플리케이션 개발
    + SE 내부 로직을 제외한 모든 부문 개발
    + Kinect 연동
    + 각 어플리케이션간 커뮤니케이션을 위한 Socket 통신부 개발

* 해당 프로그램군을 활용하여 총 3회의 공연 수행
<img src="/need/image/path.jpg" width="450px" height="300px" title="need to add images" alt=""></img><br/>
***

#### ㄴ. 영상, 음성 분석기술을 이용한 고객 관리 솔루션 시스템