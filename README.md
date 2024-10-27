![venom](https://capsule-render.vercel.app/api?type=venom&height=200&text=플레이데이터%20DE%2032기%204rd%202조&fontSize=40&color=100:ff7f00,100:87ceeb&stroke=ffffff)

---

### Team

| 이름     | 역할            |
|:--------:|:---------------:|
| [김동욱](https://github.com/DONGUK777)   ||
| [김도현](https://github.com/rlaehgus97)   ||
| [이상우](https://github.com/GITSangWoo)   ||
| [이상훈](https://github.com/hun0219)   ||
| [조하영](https://github.com/EstherCho-7)   ||

### 활용 기술 스택
![Ubuntu](https://img.shields.io/badge/ubuntu-orange?style=for-the-badge&logo=ubuntu)
![linux](https://img.shields.io/badge/linux-black?style=for-the-badge&logo=linux)
![Apache Kafka](https://img.shields.io/badge/Apache-Kafka-000000?style=flat&logo=apache-kafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache-Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache-Airflow-017E9A?style=flat&logo=apache-airflow&logoColor=white)
추가 예정

### 🗓️ 전체 프로젝트 일정
<details> 
<summary>프로젝트 일정 : 2024년 10월 24일 ~ 2024년 10월 27일(총 4일)</summary>
  <div align="center">
    <img src="https://github.com/beyond-sw-camp/be04-1st-CLOUDY-UniVerse/assets/122339395/2308712b-988b-49a9-bfb9-a2245533f958" alt="">
    <p align="center">WBS</p>
  </div>

</details>

## 목차
1. [프로젝트 개요](#프로젝트-개요)
2. [요구사항 정의서](#요구사항-정의서)
3. [개발 일정](#개발-일정)
4. [주요 기능](#주요-기능)
5. [시스템 아키텍처](#시스템-아키텍처)
6. [환경 구성](#환경-구성)
7. [테스트 결과](#테스트 결과)
8. [회고(KPT)](#회고(KPT))
9. [최종 검토 및 개선](#최종-검토-및-개선)


### 프로젝트 개요
#### 프로젝트 시나리오
**[설정 상황]**
> 업무용 메신저에서 회사 기술 및 기밀 정보들이 유출되는 상황들이 생겨나고 있다.

**[요구 사항]**
> 메신저의 주고받는 내용을 감시하고 추적하여 문제를 예방하고자 한다.

**[솔루션]**
> 메세지 발신자의 IP를 추가한 로그를 데이터베이스에 남겨 분석하고 감시하는 프로그램을 개발한다.


### 요구사항 정의서

#### 프로필

| **요구사항 ID** | **구분**        | **요구사항 설명**            | **중요도** | **난이도** | **구현 상태** |
|:---------------:|:---------------:|:----------------------------:|:----------:|:----------:|:-------------:|
| PR-01          | Username 설정   | 사용자의 이름을 설정합니다.   | 필수       | 하         | O             |


#### 업무 대화 기능

| **요구사항 ID** | **구분**         | **요구사항 설명**                   | **중요도** | **난이도** | **구현 상태** |
|:---------------:|:----------------:|:------------------------------------:|:----------:|:----------:|:-------------:|
| CT-01          | 메세지 보내기    | 사용자가 채팅방에 메세지를 보냅니다.   | 필수       | 중         | O             |
| CT-02          | 메세지 받기      | 상대방이 보낸 메세지를 받습니다.       | 필수       | 하         | O             |
| CT-03          | 메세지 시간 표시 | 메세지를 보낸 시간을 표시합니다.       | 필수       | 중         | O             |

### 감사 기능

| **요구사항 ID** | **구분**                | **요구사항 설명**                                                | **중요도** | **난이도** | **구현 상태** |
|:---------------:|:-----------------------:|:----------------------------------------------------------------:|:----------:|:----------:|:-------------:|
| AU-01          | 채팅 내역 로그 파일 저장 | 채팅 내역을 로그 파일에 저장합니다.                              | 필수       | 중         | O             |
| AU-02          | 채팅 정보 DB 저장        | 채팅 내역 및 발신자 IP를 Spark, Airflow를 통해 DB에 저장합니다.  | 필수       | 상         | O             |
| AU-03          | 특정 단어 통계           | 회사에 대한 기술 및 기밀 정보에 관한 단어 사용을  통계합니다.    | 필수       | 중         | O             |



### 개발 일정
상우형 보내주세요



### 주요 기능




### 시스템 아키텍처
상우형 보내주세요



### 환경 구성




### 테스트 결과
구현 완료되면 테스트 결과 이미지 및 시현 영상 업로드 예정



### 회고(KPT)
#### 팀 회고
~~~같이 최종 회고 하나 적어도 괜찮을 듯해여

### 김동욱

### 김도현

### 이상우

### 이상훈

### 조하영
<details>
<summary>KEEP</summary>
<div>
<figure align="center"> 
  <p>1. 요구사항에 대한 논의를 지속적으로 한 것</p>
  <p>2. 의견을 가감 없이 내뱉을 수 있는 환경</p>
  <p>3. 익숙하지 않은 것을 계속 시도해보면서 공부한 것</p>
 </figure>
</div>
</details>
<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>1. 우선순위를 깊게 고려하지 않고 한 가지만 집요하게 물고 늘어진 것</p>
  <p>2. Trouble Shooting 한 것을 제대로 기록하지 않고 해당 실수를 지속적으로 반복하는 것</p>
  <p>3. 뭔가 많이 한 것은 같은데 팀에 도움이 되었는가…? 딱히 그건 아니라고 생각</p>
  <p>4. 현재 나오는 결과에 만족하다 보니 그것이 제대로 된 방향이었는지를 고려하지 않았음</p>
  <p>5. 채팅방 들어갔을 때 나를 제외한 사람들의 이전 대화 내역이 안 뜸</p>
 </figure>
</div>
</details>
<details>
<div>
<figure align="center">
<details>
<summary>TRY</summary>
  <p>1. 우선순위(팀의 Task에 대한)를 확정한 후에 실행에 옮길 것</p>
  <p>2. Trouble Shooting 기록 제대로 남기기</p>
  <p>3. Problem의 4번과 연관, 방향성을 제대로 확인한 후 내가 할 수 있는 자원하여 팀에 제대로 도움이 되어보도록 하겠습니다.</p>
  <p>4. 시간 나면 이전 채팅 내역 뜨게 고쳐보고 싶다.</p>
 </figure>
</div>
</details>


### 최종 검토 및 개선





















