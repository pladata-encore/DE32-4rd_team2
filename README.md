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

<br/>
### 활용 기술 스택
---
![Ubuntu](https://img.shields.io/badge/ubuntu-orange?style=for-the-badge&logo=ubuntu)
![linux](https://img.shields.io/badge/linux-black?style=for-the-badge&logo=linux)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-9B59B6?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
</br>
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017E9A?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)

<br/>
### 🗓️ 전체 프로젝트 일정
> **프로젝트 일정 : 2024년 10월 24일 ~ 2024년 10월 27일(총 4일)**

<br/>
## 목차
1. [프로젝트 개요](#프로젝트-개요)
2. [요구사항 정의서](#요구사항-정의서)
3. [개발 일정](#개발-일정)
4. [주요 기능](#주요-기능)
5. [시스템 아키텍처](#시스템-아키텍처)
6. [환경 구성](#환경-구성)
7. [테스트 결과](#테스트-결과)
8. [회고(KPT)](#회고(KPT))
9. [최종 검토 및 개선](#최종-검토-및-개선)

<br/>
### 프로젝트 개요
---
#### 프로젝트 시나리오
**[설정 상황]**
> 업무용 메신저에서 회사 기술 및 기밀 정보들이 유출되는 상황들이 생겨나고 있다.

**[요구 사항]**
> 메신저의 주고받는 내용을 감시하고 추적하여 문제를 예방하고자 한다.

**[솔루션]**
> 메세지 발신자의 IP를 추가한 로그를 데이터베이스에 남겨 분석하고 감시하는 프로그램을 개발한다.

<br/>
### 요구사항 정의서
---
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


<br/>
### 개발 일정
---
상우형 보내주세요


<br/>
### 주요 기능
---
1. **메시지 기록 및 로깅**
   - 사용자가 주고받는 메시지를 자동으로 기록하여 데이터베이스에 저장합니다.
   - 메시지에는 발신자의 IP 주소와 타임스탬프가 포함됩니다.

2. **실시간 모니터링**
   - 메시지가 전송될 때마다 실시간으로 로그를 기록하여 즉각적인 분석이 가능합니다.

3. **데이터 분석 및 통계**
   - 수집된 데이터를 기반으로 기밀 정보 유출 가능성을 분석하고, 통계 자료를 생성하여 시각화합니다.

4. **관리자 인터페이스**
   - 관리자가 메시지 기록과 분석 결과를 손쉽게 확인할 수 있는 웹 기반 대시보드를 제공합니다.


<br/>
### 시스템 아키텍처
---
상우형 보내주세요


<br/>
### 환경 구성
---
1. **AWS 서버 접속**
```
$ ssh -i <your_key> ubuntu@<aws_server_ip>
```

2. **Kafka 실행**
```
$ cd /home/ubuntu/code/springkafka
$ docker compose up -d
```

3. **App 및 DB Run**
```
$ cd /home/ubuntu/code/JavaWithKafka
$ docker compose -d --force-recreate --build
```

4. **Airflow 및 Pyspark 실행**



<br/>
### 테스트 결과
---
구현 완료되면 테스트 결과 이미지 및 시현 영상 업로드 예정


<br/>
# 회고(KPT)
### 팀 회고
#### 같이 최종 회고 하나 적어도 괜찮을 듯해여
<br/>

## 김동욱
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>이전에 했던 내용을 활용하였기 때문에 해당 내용에 대한 이해도가 상승함과 동시에 자바 활용하는 방법을 익힐 수 있었다.</p>
  <p>파이널을 같이 할 팀원이기 때문에 협업하는 방법에 대해 논의하고 적극적으로 소통하려고 노력한 점이 좋았다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>이전 프로젝트를 자바로 대체하는 것이 목표인지 그것을 참고한 새로운 프로젝트인지 구분하는 것이 확실하게 되지 않았던 것 같다.</p>
  <p>아무래도 시간이 부족했기 때문에 다른 팀원들의 수행한 역할 및 업무를 완벽하게 이해하고 넘어가기에는 무리가 있었고, 각자 맡은 업무에만 집중하게 되었던 점이 아쉬웠다.</p>
 </figure>
</div>
</details>


<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>역할 분담과 담당 업무에 대한 공유가 더욱 더 잘 이뤄져야 한다.(이 부분에서는 완벽이란 없으니 언제나 더욱 노력해야 함)</p>
  <p>프로젝트를 만족스럽게 완성하는 것도 중요하지만, 더욱 중요한 것은 주어진 시간 내에 프로젝트를 완성하는 것이기 때문에 기간 내에 해낼 수 있는 프로젝트를 계획하는 것에 집중해야 한다.</p>
 </figure>
</div>
</details>

## 김도현
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>중간중간 소통을 해서 서로 진행했던 것, 배운 점을 공유해서 좋았다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBELM</summary>
<div>
<figure align="center">
  <p>짧은 시간에 많은 것을 하려다 보니 시간이 촉박했다.</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>서로 진행하는 것을 공유하는 과정에서 역할분담이 덜된 느낌, 각자 코딩하며 스스로 학습한 것은 좋았으나 전체 프로젝트 진행도로 봤을 때는 위의 점 때문에 많이 지체된 느낌이 있었다.</p>
 </figure>
</div>
</details>

## 이상우
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>팀원들에 대해서 알 수 있는 기회였다.</p>
  <p>기술에 대해서 공부를 할 수 있는 시간이었다.</p>
  <p>다들 협업과 업무의 목말라있는게 보인다. 열정이 넘치고, 일찍온다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>팀원들의 열정을 프로젝트에 모두 담을 수 없었다.</p>
  <p>새로운 기술을 적용하기엔 부족한 지식이었고, 부족한 시간이었던 것 같다.</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>가용 가능한 자원을 객관적으로 생각해서 프로젝트 주제를 정하고 계획을 짜야겠다.</p>
 </figure>
</div>
</details>

## 이상훈
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>소통을 많이해서 공유가 잘돼서 좋았고, 그 덕분에 이해가 좋았고, 나의 업무에 좀 더 집중 할 수 있었다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>짧은 시간에 많은 것을 하려다 보니 시간이 촉박하고 코드 이해가 부족했다.</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>기간 내에 이루어질 수 있는 요구사항을 좀 더 구체화 했으면 좋겠다. 약간은 일방적인 소통의 느낌이 있었던거 같다. 업무 분담도 다음엔 더 잘됐으면 좋겠다라는 바램</p>
 </figure>
</div>
</details>

## 조하영
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
<summary>TRY</summary>
<div>
<figure align="center">
  <p>1. 우선순위(팀의 Task에 대한)를 확정한 후에 실행에 옮길 것</p>
  <p>2. Trouble Shooting 기록 제대로 남기기</p>
  <p>3. Problem의 4번과 연관, 방향성을 제대로 확인한 후 내가 할 수 있는 자원하여 팀에 제대로 도움이 되어보도록 하겠습니다.</p>
  <p>4. 시간 나면 이전 채팅 내역 뜨게 고쳐보고 싶다.</p>
 </figure>
</div>
</details>


### 최종 검토 및 개선





















