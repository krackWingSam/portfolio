# 포트폴리오
## 목차
## 1. [참여 프로젝트](##-1.-참여-프로젝트)

### ㄱ. [방송 및 공연 환경에서의 각 전문분야의 유기적인 활동을 지원하기 위한 프로그램 군의 개발](#ㄱ.방송-및-공연-환경에서의-각-전문분야의-유기적인-활동을-지원하기-위한-프로그램-군의-개발)
### ㄴ. [영상, 음성 분석기술을 이용한 고객 관리 솔루션 시스템](####-ㄴ.[영상,-음성-분석기술을-이용한-고객-관리-솔루션-시스템])
### ㄷ. [ASMR Director](#-ㄷ.ASMR-Director)
### ㄹ. [Chord Player](#-ㄹ.Chord-Player)
### ㅁ. [Stdio Recording](#-ㅁ.Stdio-Recording)
### ㅂ. [Karaoke Studio](#-ㅂ.Karaoke-Studio)
### ㅅ. [Whyme](#-ㅅ.Whyme)
### ㅇ. [myOndo](#-ㅇ.myOndo)
### ㅈ. [IMU를 활용한 측위 알고리즘 / Firmware 개발](#ㅈ.IMU를-활용한-측위-알고리즘-/-Firmware-개발)

## 2. [개인 프로젝트]()
## 3. [수상 실적]()
---

## 1. 참여 프로젝트
#### ㄱ.방송 및 공연 환경에서의 각 전문분야의 유기적인 활동을 지원하기 위한 프로그램 군의 개발
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

    <img src="./old/ewat/p1.jpg" width="130px" height="130px" title="공연1 : 그녀의 시간 포스터" alt="그녀의 시간 포스터"></img>
    <img src="./old/ewat/p2.jpg" width="184px" height="130px" title="공연2 : 그녀의 시간2 포스터" alt="그녀의 시간2 포스터"></img>
    <img src="./old/ewat/p3.jpg" width="104px" height="147px" title="공연3 : 미혹" alt="미혹"></img><br/><br/>
    <img src="./old/ewat/a1.png" width="150px" height="100px" title="Application : VE" alt="App 1"></img>
    <img src="./old/ewat/a3.png" width="150px" height="100px" title="Application : VE" alt="App 3"></img>
    <img src="./old/ewat/a2.png" width="150px" height="100px" title="Application : IS" alt="App 2"></img><br/>
    <img src="./old/ewat/a5.jpg" width="150px" height="100px" title="Application : IS" alt="App 5"></img>
    <img src="./old/ewat/a4.jpg" width="150px" height="100px" title="Application : GVE" alt="App 4"></img><br/><br/>
    <img src="./old/ewat/r1.jpg" width="150px" height="100px" title="in performance" alt="Performance"></img>
***

#### ㄴ.영상, 음성 분석기술을 이용한 고객 관리 솔루션 시스템

* 프로젝트 개요 : 
    + Keynect를 이용하여 사용자의 얼굴 표정을 추측
    + 사용자의 표정, 음성으로부터 화남의 정도를 분석
    + OSX 환경에서 구동

<img src="./old/self/a1.jpg" width="433px" height="327px" title="Application Screen" alt="Application"></img><br/>
***

#### ㄷ.ASMR Director

* 프로젝트 개요 : 
    + 사용자가 원하는 white noise를 추가하여 자신만의 ASMR을 만들 수 있는 Application
    + mp3, wav, aiff 등의 음원포맷 지원
    + 최대 16개 채널 동시 재생 가능

    <img src="./old/Kadncha_Fermata/a1.jpg" width="180px" height="320px" title="Application Screen" alt="Application"></img>
    <img src="./old/Kadncha_Fermata/a2.jpg" width="180px" height="320px" title="Application Screen" alt="Application"></img>
    <img src="./old/Kadncha_Fermata/a3.jpg" width="180px" height="320px" title="Application Screen" alt="Application"></img>
***

#### ㄹ.Chord Player

* 프로젝트 개요 : 
    + Chord 기반의 가상 악기
    + Grand Piano, EP 등 3가지 악기 지원
    + 내부 악보 포맷 지원
    + 악보 작성용 툴 개발(OSX)
    + 개발 중단

    <img src="./old/Kadncha_Fermata/a4.png" width="320px" height="180px" title="Application Screen" alt="Application"></img>
***


#### ㅁ. Stdio Recording

* 프로젝트 개요 : 
    + 사용자가 추가한 MR을 반주로 하여 동영상 UCC 제작을 도와주는 Application
    + mp3, wav, aiff 등의 음원포맷 지원
    + 3종류의 Reverb 효과 지원
    + 사용자의 선택에 따라 동영상 녹화의 On/Off 설정 가능

    <img src="./old/Kadncha_Fermata/a5.png" width="180px" height="320px" title="Application Screen" alt="Application"></img>
    <img src="./old/Kadncha_Fermata/a6.png" width="180px" height="320px" title="Application Screen" alt="Application"></img>
***

#### ㅂ.Karaoke Studio

* 프로젝트 개요 : 
    + Youtube 동영상을 이용하여 UCC 제작을 도와주는 Application
    + Youtube 동영상중 오디오 채널을 이용하여 MR 생성 및 동영상 촬영시 적용
    + 3종류의 Reverb 효과 지원
    + 사용자의 선택에 따라 동영상 녹화의 On/Off 설정 가능
    + 개발 중단

    <img src="./old/Kadncha_Fermata/a7.png" width="320px" height="180px" title="Application Screen" alt="Application"></img>
    <img src="./old/Kadncha_Fermata/a8.png" width="320px" height="180px" title="Application Screen" alt="Application"></img><br/>
    <img src="./old/Kadncha_Fermata/a9.png" width="180px" height="320px" title="Application Screen" alt="Application"></img>
***

#### ㅅ.Whyme

* 프로젝트 개요 : 
    + 구인구직 플랫폼
    + 이력서 / 채용공고 분석을 통해 구인자-구직자 간 매칭
    + 실시간 채팅 제공

* 기여 :
    + 서비스, UI/UX 기획 참여
    + iOS 어플리케이션 구현
    + 문서 유사도 비교 알고리즘 구현
    + 분석서버 분산처리를 위한 구조 설계 : Redis를 이용한 Message Queue, NodeJS 를 이용한 분석서버 API 개발

    <img src="./askstory/a3.png" width="180px" height="320px" title="Application Screen" alt=""></img>
    <img src="./askstory/a2.png" width="180px" height="320px" title="Application Screen" alt=""></img>
    <img src="./askstory/a1.png" width="180px" height="320px" title="Application Screen" alt=""></img>
***

#### ㅇ.myOndo

* 프로젝트 개요 : 
    + 에어컨 제어를 위한 IoT 서비스
    + 자체 분석된 IR Code Table
    + 영문, 중문, 일문, 한글 지원
    + 내부 인공지능 엔진을 이용한 온도조절 기능 제공

* 기여 :
    + iOS Application 개발

    <img src="./askstory/a5.png" width="180px" height="320px" title="Application Screen" alt=""></img>
    <img src="./askstory/a4.jpg" width="180px" height="320px" title="Application Screen" alt=""></img>
***

#### ㅈ.IMU를 활용한 측위 알고리즘 / Firmware 개발

* 프로젝트 개요 : 
    + 위치추적장치 개발중 Offline 상태에서의 측위/행동 관찰을 위한 알고리즘 개발
    + 차후 생활패턴 작성을 위한 10종의 행동패턴 분류
    + X,Y,Z 축을 기준으로 착용자의 이동거리 계산

* 기여 :
    + ESP32 보드에 MPU9250을 이용하여 측위 알고리즘 구현
    + 시뮬레이션을 위한 OSX Application 개발
    + Matlab을 이용하여 저장된 데이터로 알고리즘 구현
    + Serial/wifi 통신을 이용하여 알고리즘 테스트/모니터링

    <img src="법무부/01.png" width="320px" height="200px" title="Application Screen" alt=""></img><br/>
    <img src="법무부/02.png" width="200" height="140px" title="Application Screen" alt=""></img>
    <img src="법무부/06.png" width="260px" height="140px" title="Application Screen" alt=""></img><br/>
    <img src="법무부/03.png" width="144px" height="144px" title="Application Screen" alt=""></img>
    <img src="법무부/04.png" width="200px" height="140px" title="Application Screen" alt=""></img><br/>
    <img src="법무부/05.png" width="200px" height="144px" title="Application Screen" alt=""></img>

    Video<br/>
    [<img src="법무부/07.png" width="200px" height="140px" title="Application Screen" alt=""></img>](법무부/video.mov)<br/>