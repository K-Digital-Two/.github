

## 💛 BIGDATA PJT BY JKM

### ShipTraffic Live - 선박도착시간 예측 서비스

<p align="center">
  <img src="https://user-images.githubusercontent.com/109561152/218896659-e4cd5acd-e873-482e-acd4-c21cac6774b5.png" />
</p>

<br/>

---

### 한 줄 소개

-AIS 신호를 활용하여 국내 선박들의 위치 정보를 실시간으로 파악 및 목적지 도착 예정 시각을 예측하여 알려주는 서비스

##

### 기획 배경

- 컨테이너 터미널에서는 선박 크기, 도착시각 등을 고려하여 정박할 선석 배정 및 하역 준비 진행
- 여러 가지 환경 변수에 따라 선박의 실제 도착시각이 최초 예측한 값과 차이 발생
- 예측값과 실제 도착시각의 차이가 클 수록 업무 효율이 하락하고 불필요한 비용 발생
- 선박의 실시간 위치 기준 예측한 값을 활용하면 문제 해결 가능
- 동일한 서비스를 제공하는 다른 업체들도 있으나 해외 사이트가 대다수이며 유료로 서비스를 제공하는 사이트들이 많음

##

### 목표

- 팀 프로젝트를 수행하며, SW 개발 뿐만 아니라 팀원들과 함께 문제를 해결하기 위한 협업 역량을 배양

##


### 서비스 특징

- 컨테이너 터미널에 접안하는 선박의 정확한 도착 예정 시간을 예측하여 제공함으로써 선석의 운영 및 터미널 운영의 사전 준비 및 리소스 운영 계획을 안정적으로 수행할 수 있도록 한다.
- 선박체항을 방지하여 선박의 탄소배출 감소 및 선주,화주 모두 운항비용 절감 효과 기대 

##

### 프로젝트

-  2023.01.11 ~ 2023.02.09 (일/시간)
- [Github - FrontEnd](https://github.com/K-Digital-Two/JKM1-FE)
- [Github - BackEnd](https://github.com/K-Digital-Two/JKM1-BE)
- [Github - DataAnalysis](https://github.com/K-Digital-Two/JKM1-DA)
- [Notion](https://www.notion.so/jm61229/dba2917f8a004c1e8fa25974ecc31ca8)

<br/>

---

### **_📌_** 차례

##

1. [팀원소개](#🔥-1-중꺾마-팀원)
2. [주요 기술 스택](#**_⚙_**-2.-주요-기술-스택)
3. [아키텍쳐](#**_🔨_**-3.-아키텍쳐)
4. [ER Diagram](#**_🔗_**-4.-ER-Diagram)
5. [서비스 소개](#🎞-서비스-소개)
6. [Git Branch](#***🌿***-Git-Branch)
7. [Git 규칙](#✔-Git-규칙)
8. [시작하기](#✔-시작하기)

<br/>

---

### 🔥 1. 중꺾마 팀원

##

- **이정민** \- _backend -_ [danmiee](https://github.com/danmiee)
  - [dan-mi@kakao.com](mailto:dan-mi@kakao.com)
- **금민경** \- _frontend/data -_ [min0312](https://github.com/min0312)
  - [mkm6192@gmail.com](mailto:)
- **최정인** \- _data -_ [Choi-09](https://github.com/Choi-09)
  - [vanessaj.choi@gmail.com](mailto:vanessaj.choi@gmail.com)
- **변혁** \- _backend -_ [uiiunm](https://github.com/uiiunm)
  - [uiiunm@gmail.com](mailto:uiiunm@gmail.com)
- **이창현** \- _frontend -_ [ckdtns5262](https://github.com/ckdtns5262)
  - [ckdgus5262@gmail.com](mailto:ckdgus5262@gmail.com)
 
<br/>
 
---

### **_⚙_** 2. 주요 기술 스택

##

- Collaboration Tools
 <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub" /> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion" /> <img src="https://img.shields.io/badge/Miro-yellow?style=flat-square&logo=Miro&logoColor=000000" /> <img src="https://img.shields.io/badge/ Google Sheets-34A853?style=flat-square&logo=Google Sheets&logoColor=ffffff" /> 

- FrontEnd
<img src="https://img.shields.io/badge/ Figma-F24E1E?style=flat-square&logo=Figma&logoColor=ffffff" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=ffffff"/>

- BackEnd
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Spring Cloud-6DB33F?style=flat-square&logo=Spring&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Spring Webflux-6DB33F?style=flat-square&logo=SpringBoot&logoColor=ffffff" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat-square&logo=Amazon S3&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat-square&logo=Amazon RDS&logoColor=ffffff" />

- DataAnalysis
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat&logo=Tensorflow&logoColor=white"/> 

<br/>

---
 
### **_🔨_** 3. 시스템 구성도

##

<p align="center">
  <img src="https://user-images.githubusercontent.com/109561152/218897445-fdad1c72-92e5-48b7-9089-16c10360c174.png" width="60%" height="60%"/>
</p>

<p align="center">
- FrontEnd 구성도
  <img src="https://user-images.githubusercontent.com/109561152/218897522-34d93f87-1c47-4808-a5a4-1b3e68a40e9e.png" width="60%" height="60%"/>
</p>
<p align="center">
- BackEnd 구성도
  <img src="https://user-images.githubusercontent.com/109561152/218897581-3963a079-dc61-4dc1-b8a2-13e11c2eb1fe.png" width="60%" height="60%"/>
</p>

<br/>

---

### **_🔗_** 4. ER Diagram

##

<p align="center"> <img src ="https://user-images.githubusercontent.com/109561152/218897247-52a5e523-8cf4-4d52-9a41-03ffa04ecd1b.png" width="60%" height="60%"> </p>
<br/>
---

###  🎞 5. 서비스 소개 

## 

#### 1. 주요 버전

##### FrontEnd 주요 버전
```cmd
1. react : 18.2.0
2. next : 12.3.1
3. axios : 1.2.2
4. redux : 8.0.5 
5. tailwind css : 3.2.4
6. Visual Studio : 1.71.0
```

#### BackEnd 주요 버전
```cmd
1. JVM : 1.8.0_192
2. WAS : Tomcat 9.0.65
3. springBootVer : '2.7.4'
4. JAVA: 11
. 기타 상세 버전 정보
    - SpringBoot : build 도구 gradle 7.5
```

#### DataAnalysis 주요 버전
```cmd
1. Python : 3.8.15
2. Tensorflow : 2.9.0
3. MySQL : 8.0.31
4. 
```

<br/>

##

#### 2. 서비스 시연 영상

<img src="https://user-images.githubusercontent.com/109561152/218896206-cb1c17a7-e3d4-4367-bcf9-42c0cec6ff80.gif"/>


<br/>

---

### **_🌿_** 6. Git Branch

##

> ✨ (main) → (develop/ frontend) → (feature/<BE / FE>/<feature>)

- `main` : release branch

- `develop` : backend branch

- `frontend` : frontend branch

- `feature/<BE/FE>/<feature>` : 개별 개발 branch

<br/>
	
---

### ✔ 7. Git 규칙

##
	
#### 1. Commit 규칙

> ✨ 형태 : git commit -m '#[깃이슈번호] [git 컨벤션]: [작업내용]'
>
> 예시 ) `git commit -m '#[깃이슈번호] feat 페이지네이션 기능 추가'`

- git commit -m '#[깃이슈번호] style: 버튼 스타일링'

- git commit -m '#[깃이슈번호] fix: 팝업 버그 수정'

- git commit -m '#[깃이슈번호] docs: 리드미 수정'

<br/>
	
##
	
#### 2. Git 컨벤션**

- feat : 새로운 기능
- fix : 버그 수정
- docs : 문서 (문서 추가, 수정, 삭제)
- style : 포맷팅, 세미콜론 추가, etc) 코드 변화 없을 때
- refactor : 코드 리팩토링
- test : 테스트 추가, 테스트 리팩토링
- chore: 빌드 업무 수정, 패키지 매니지 수정

<br/>
	
##
	
####  3. 네이밍 규칙**

- 변수 함수: camelCalse
- 클래스/컴포넌트/인터페이스: PascalCase
- 메소드 적용 예시 <br/>
		- C : createXXX ex) creatOrders <br/>
		- R : retrieveXXX ex) retrieveOrders<br/>
		- U : updateXXX ex) updateOrder<br/>
		- D : deleteXXX ex) deleteOrder<br/>

<br/>
			
---		
	
### ✔ 8. 시작하기

##

```shell
# /backend/
$ gradlew clean build
$ build/libs/[서비스명].jar -jar app.jar

# /frontend/
$ npm install
$ npm start
```
