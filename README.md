# 컴퓨터구조 (Computer Architecture) 2018 가을학기

>컴퓨터 시스템을 이루는 프로세서, 메모리, 버스, 주변 장치 등의 각 요소를 중심으로, 기본 구조와 동작 원리를 배우고, 이를 통해 하드웨어 및 소프트웨어의 개발에 필요한 깊이 있는 지식을 익힌다. 이 과정에서는 기초적인 요소 기술의 소개는 물론, 상용 기술의 사례 연구를 통해 수강자들이 최근의 기술 동향>을 파악하게 하고 향후에 이를 활용할 수 있는 기반 지식을 제공한다.
> 이 과정에서는 또한 MIPS 프로세서 기반의 하드웨어를 중심으로 프로세서 구조, 어셈블리 프로그래밍 등을 실습함으로 이론을 확인, 심화하는 과정을 제공한다. 본 교과목은 <임베디드 시스템 개론> 및 <임베디드 하드웨어>의 권장 선수과목이다.

## 강의 스탭
### 담당교수: 이정근
   - 연구실:(성호관 1306호실) / Email: Jeonggun.Lee (AT) gmail.com
   - 전화번호: 033-248-2312 (연구실)
### 담당조교: 정다운
   - (데이터베이스 연구실, Email:  )
   
## 교재
   - 주교재: "[디지털논리와 컴퓨터설계](http://www.yes24.com/24/goods/3311366)," 데이비드 해리스,사라 해리스 공저/조영완 등역, 사이텍미디어
   - 부교재: "컴퓨터 구조 및 설계 : 하드웨어/소프트웨어 인터페이스 ARM 버전," 데이비드 패터슨,존 헤네시 공저/박명순,김병기,하순회,장훈 공역, 비제이퍼블릭(BJ퍼블릭)   
   
## 평가방법
   - 중간 35%, 기말 35%, 실습 20%, 숙제 & 퀴즈 10%
   - 결석 4회 이상 "F", 사유가 있어도 결석임!
   - 결석 1회를 만회하기 위해서는 "추가로 숙제를 제출"해야함

## 강의노트
   - Chapter 6 :: MIPS 어셈블리 언어와 명령어 포맷
      - 6.1 Introduction
      - 6.2 Assembly Language
      - 6.3 Machine Language
      - 6.4 Programming
   - Chapter 7 :: Microarchitecture (PPT) : MIPS 프로세서의 구조, Pipelining
      - 7.1 Introduction
         - 7.1.1 Architectural State and Instruction Set
         - 7.1.2 Design Process
         - 7.1.3 MIPS Microarchitectures
      - 7.2 Performance Analysis
      - 7.3 Single-Cycle Processor
         - 7.3.1 Single-Cycle Datapath
         - 7.3.2 Single-Cycle Control
         - 7.3.3 More Instructions
         - 7.3.4 Performance Analysis
   - Chapter 8 :: Memory Systems (PPT) : 메모리 계층, 캐쉬메모리 구조
      - 8.1 Introduction
      - 8.2 Memory System Performance Analysis
      - 8.3 Caches
         - 8.3.1 What Data is Held in the Cache
         - 8.3.2 How is Data Found?
         - 8.3.3 What Data is Replaced?
         - 8.3.4 Advanced Cache Design
         - 8.3.5 The Evolution of MIPS Caches


## 실습
   - QtSpim 을 이용한 MIPS 어셈블러 프로그래밍 ([Youtube](https://www.youtube.com/results?search_query=Qtsim+PCSIM+MIPS))
   - [요기-한국어!!!](https://www.joinc.co.kr/w/Site/Assembly/Documents/Spim) : SPIM에 대한 자세한 한글 설명을 볼수 있습니다.
   - [조기](http://chortle.ccsu.edu/AssemblyTutorial/index.html) : 위 사이트의 영문 원본 문서를 볼수 있습니다.
   - Spim 공부를 위한 [좋은 곳](http://www.cs.ccsu.edu/~markov/ccsu_courses/254syllabus.html)!
   
   > SPIM은 오픈소스 SW로 구현된 MIPS 프로세서 시뮬레이터입니다. [MIPS 시뮬레이터](http://spimsimulator.sourceforge.net/)
   > 관심있는 학생들은 SPIM 시뮬레이터의 소스코드를 분석하고 수행시켜봄으로써 보다 자세히 명령어의 수행 구조 및 프로세서 구조에 대해서 이해할수 있습니다.
   > 컴퓨터구조 교과목은 오픈소스 SW에 대한 이해도 함께 증진시키는 것을 목적으로 합니다.
   
   ![Alt text](https://github.com/jeonggunlee/Computer_Arch_2018_Fall/blob/master/img/openss.png "오픈소스교과목")

## 참조 사이트
   - [MIPS 프로세서 위키백과사전](https://ko.wikipedia.org/wiki/MIPS_%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98) : 밉스 프로세서에 대한 자세한 설명을 한글로 볼수 있습니다.

   
   
   
