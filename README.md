# 📖 Interview-Question
 
- 주니어 백엔드 개발자 면접 시에 물어볼 수 있는 질문에 대해서 같이 공부하고, 공유하고자 합니다. 

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FNext-Squad%2FInterview-Question&count_bg=%2379C83D&title_bg=%23150404&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
## 🎙 진행방식

### 1. 핵심 주제 면접 스터디 

-  2022.08.02 ~
    - 10주간 진행 (변동 가능)
    - 10주 이후에 모의면접 형식으로 전환될 수 있습니다. 
    - 10주 내에서도 자유롭게 모의면접 형식의 모임도 있을 수 있습니다.
   
- 세션 진행 일시 : 매주 화요일 저녁 9시

- 진행 방식
  - 공지되는 핵심 주제(소주제)에 대해서 공부하고 각자 질문을 만들고, 답변도 준비합니다.
  - 아래에 공유된 질문리스트에서 핵심 주제에 포함되는 면접 질문은 기본적으로 답변을 준비합니다.
    - 핵심 주제 공유시에 기본 질문리스트도 함께 공유드리겠습니다.
  - 각자 준비한 질문들을 토대로 면접관과 면접자가 되어서 질의응답을 진행합니다.
    - 인원에 따라서 소그룹화할 수 있습니다.
    - 세션 이후 각자 준비한 질문과 답변을 #주차 Issue에 comment로 공유합니다.
    

#### 진행 스케줄

| 주차  | 일시          | 주제                                                 |
| ----- | ------------- | --------------------------------------------------- |
| 1주차 | 22.08.03 (수) | [TCP와 UDP](https://github.com/Next-Squad/Interview-Question/issues/3)     |
| 2주차 | 22.08.09 (화) | [HTTP와 HTTPS](https://github.com/Next-Squad/Interview-Question/issues/18)     |
| 3주차 | 22.08.16 (화) | [로그인](https://github.com/Next-Squad/Interview-Question/issues/24)     |
| 4주차 | 22.08.23 (화) | [운영체제1](https://github.com/Next-Squad/Interview-Question/issues/30)     |
| 5주차 | 22.08.30 (화) | [DB1](https://github.com/Next-Squad/Interview-Question/issues/39) |
| 6주차 | 22.09.06 (화) | [Java1](https://github.com/Next-Squad/Interview-Question/issues/43) |
| 7주차 | 22.09.13 (화) | [Spring1](https://github.com/Next-Squad/Interview-Question/issues/47) |
| 8주차 | 22.09.20 (화) | [Spring2 + JPA](https://github.com/Next-Squad/Interview-Question/issues/51) |
| 9주차 | 22.09.27 (화) | [자료구조 + 알고리즘(정렬)](https://github.com/Next-Squad/Interview-Question/issues/54) |

### 2. 면접 질문 공유 wiki 함께 만들기

- 좋은 reference들을 토대로 wiki를 공동 제작합니다. 
- 총 5개의 분야에 대한 질문 리스트들에 대해서 답변을 작성합니다.
    - `Java + 자료구조`, `Spring + JPA`, `운영체제`, `네트워크`, `DataBase`
    - 자유롭게 질문을 골라서 Issue를 등록, Comment로 답변을 달고, 질문리스트에 Issue를 링크합니다. 
    - 이 후에 해당 질문에 대해서 작성자 이 외에도 추가로 Comment를 달고, 꼬리 질문 및 키워드에 대해서 작성하면 좋습니다. 
      - 실제 면접 질문에 답변한다고 생각하고, 자신의 말로 정리해보는 형식의 Comment를 권장합니다.
       
- 이외에 좋은 주제 혹은 질문이 빠졌다고 생각되면 질문을 추가하셔도 좋습니다. 


 ## 📋 면접 질문 리스트 

<details>
<summary>💻 운영체제</summary>
<div markdown="1">
 
1. 바이트코드와 기계어의 차이에 대해 설명해주세요.
2. 컴퓨터는 10진수를 2진수로 바꿔서 계산합니다. 10진수를 2진수로 바꾸는 방법과, 그 반대 방법에 대해 설명해주세요.
3. [context switching이란?](https://github.com/Next-Squad/Interview-Question/issues/10)
    - PCB에 저장되는 정보는?
4. [비선점방식과 선점방식을 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/55)
5. Thread 간의 데이터 공유와 Process 간의 데이터 공유의 공통점과 차이점을 설명해주세요.
    - 스레드에 스택을 독립적으로 할당하는 이유?
    - PC레지스터를 스레드마다 독립적으로 할당하는 이유?
6. [멀티스레드 프로그래밍에 대해 설명해보세요.](https://github.com/Next-Squad/Interview-Question/issues/56)
    - 멀티 스레드의 장점, 단점
    - 멀티 프로세스 대신 멀티 스레드를 사용하는 이유
7. Thread-safe 하다는 의미와 설계하는 법을 설명해보세요.
8. 프로세스 동기화에 대해 설명해보세요.
9. 교착상태와 기아상태의 해결방법에 대해 설명해보세요.
10. [세마포어와 뮤텍스의 차이에 대해 설명해보세요.](https://github.com/Next-Squad/Interview-Question/issues/36)
11. 가상 메모리에 대해 설명해보세요.
12. 페이지 교체 알고리즘에 대해서 설명해보세요.
    - 페이징이 필요한 이유는?
    - demand paging이란?
13. 캐시의 지역성에 대해 설명해보세요.
    - 페이지 적중률을 높이는 방법은? 
14. 시스템콜이란 무엇이며 시스템 콜을 사용하는 예시를 들어주세요.
15. 인터럽트가 필요한 이유 및 언제 발생되는지 설명해주세요.
    - 인터럽트 동작과정을 설명해보세요.
16. 커널 모드와 유저 모드를 구분해 놓은 이유는?
    - 커널이란?
17. 커널 수준 스레드와 사용자 수준 스레드의 각각 장단점은?
18. 운영체제가 여러 프로그램을 동시에 실행하는 원리에 대해 설명해주세요.
19. 동기와 비동기의 차이(블로킹, 넌블로킹)에 대해서 설명해주세요.
20. 캐시와 레지스터의 차이점은 무엇인가요?
</div>
</details>

<details>
<summary>🌐 네트워크 + WEB</summary>
<div markdown="2">
 
#### IP, xOSI 7, TCP/IP Layer

 1. [IPV4 vs IPV6 을 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/5)
 2. IPv4의 주소 부족현상을 해결하기 위해 현재 어떤 방법을 사용하고 있나요?
 3. OSI 7 - TCP/IP Layer와 각 계층에 대한 설명과 계층화하는 이유에 대해 설명해주세요
 4. [패킷이란 무엇인지 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/6)
 
#### TCP와 UDP

 5. [TCP와 UDP의 특징과 차이점을 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/12)
 6. [3-Handshaking과 4-Handshaking의 과정을 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/15)
 7. [3-way handshaking 과정에서 클라이언트가 서버가 보낸 ACK+SYN을 받지 못하면?](https://github.com/Next-Squad/Interview-Question/issues/31)
 8. [4-way handshaking 과정에서 Active closer가 마지막에 ACK를 굳이 보내는 이유?](https://github.com/Next-Squad/Interview-Question/issues/14)
 9. [만약 Passive closer에서 FIN 세그먼트를 전송하기 전에 전송한 패킷이 Routing 지연이나 패킷 유실로 인한 재전송 등으로 인해 FIN 패킷보다 늦게 도착하는 상황이 발생하면 어떻게 될까?](https://github.com/Next-Squad/Interview-Question/issues/22)
 10. TCP의 연결 설정 과정(3단계)과 연결 종료 과정(4단계)이 단계가 차이나는 이유?
 11. [초기 Sequence Number인 ISN을 0부터 시작하지 않고 난수를 생성해서 설정하는 이유?](https://github.com/Next-Squad/Interview-Question/issues/20)
 12. UDP에서 신뢰도를 보장하는 방법을 설명해주세요.
 
#### HTTP와 HTTPS

13. HTTP1.1와 HTTP2.0 차이점은 무엇인가요?
14. [HTTP의 특징을 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/26)
15. [비대칭키 또는 공개키 암호화 방식은 무엇인가요?](https://github.com/Next-Squad/Interview-Question/issues/52)
16. [HTTP METHOD 종류에 대해서 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/28)
17. [HTTP에서 상태유지(stateful)를 하는 방법을 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/29)
18. SSL (또는 TLS) 가 어떻게 동작하는지 말씀해주세요.(연결방식)
19. 차세대 프로토콜로 논의중인 HTTP/3 은 UDP 기반의 QUIC 이라는 기술로 구현되어 있습니다. UDP 는 TCP 대비 안정성이 떨어지는 프로토콜이라고 하는데, 그럼에도 왜 UDP 를 채택한 걸까요?
20. HTTP(s) 프로토콜에서 바이너리 데이터를 전송하는 방식에 대해 설명해주세요.
 
#### DNS와 DHCP

 21. 도메인과 DNS가 무엇인지 설명해주세요
 22. Domain Name System 동작과정을 설명해주세요.
 23. DNS 스케줄링 알고리즘에 대해 설명해주세요. 특히 round robin 방식과 문제점을 설명해주세요
 24. [DHCP 서버의 역할을 간단히 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/63)

#### 로드밸런서

 25. 로드 밸런싱을 설명해주세요.
 26. L4 로드 밸런싱과 L7 로드 밸런싱에 대해  설명하고, 차이를 말해보세요
 27. 게이트웨이란?
 28. 서버에 트래픽이 주어졌을 때 어떻게 응답속도를 개선할 수 있는가?
 29. 로드밸런싱과 클러스터링 개념과 차이
 30. 프록시 서버에 대한 설명
 31. 리버스 프록시 서버를 왜 쓰는지 및 장단점
 
#### WEB

 32. url과 uri에 대해 각각 설명해주세요
 33. 브라우저에 "www.google.com" 입력하면 어떤일이 일어날까요?
 34. RESTful API란 무엇인가요?
 35. Ajax의 장점과 단점은 무엇인가요?
 36. CORS, preflight는 무엇인가요?
 37. 소켓이란 무엇인가요, 소켓 프로그래밍에 대해 설명해주세요?
 38. DOM과 가상DOM
 39. [OAuth란 무엇인가요?](https://github.com/Next-Squad/Interview-Question/issues/40)
 40. SPA
 41. HTTP 는 Stateless (상태가 없는) 통신 프로토콜이라고 합니다. 따라서, 상태가 없다면 가령 HTTP 를 쓰는 서비스는 매번 로그인을 해 줘야 하거나 사용자 정보를 저장하는 일이 불가능합니다. 그런데 실제론 그렇지 않죠. 어떻게 이런 불편함을 해소했을까요?
 42. Socket 으로 웹 페이지를 크롤링하는 HTTP 클라이언트를 직접 구현해야 한다면, 어떻게 하시겠습니까?
 43. http통신을 api를 안쓰고 하려면?
 
#### 쿠키와 세션
 
 44. 세션 / 토큰 / 쿠키 / JWT 인증방식에 대한 장단점과 해결 방안에 대해 설명해주세요
 45. [JWT와 장단점 대해 설명해주세요](https://github.com/Next-Squad/Interview-Question/issues/61)
</div>
</details>

<details>
<summary>💾 데이터베이스</summary>
<div markdown="3">
 
#### RDBS 란?

  1. [Super Key, Candiate Key, Primary Key, Alternate Key, Foreign Key](https://github.com/Next-Squad/Interview-Question/issues/60)

#### 정규화란 무엇인가?

  2. [정규화의 종류](https://github.com/Next-Squad/Interview-Question/issues/58)

#### 인덱스(Index)란 무엇인가?

  3. Index 의 자료구조
  4. [Index 사용 시 장점과 단점](https://github.com/Next-Squad/Interview-Question/issues/42)
  5. [Clustered Index와 Non-Clustered Index의 차이](https://github.com/Next-Squad/Interview-Question/issues/7)
     - Primary Index vs Secondary Index
  6. 인덱스는 어떤 기준으로 정해야하는가?
  7. Cardinality 란?
  8. Selectivity 란?
  9. 커버링 인덱스란? 
  10. Composite Index
  11. 모든 칼럼에 Index를 사용 시 발생하는 문제는?
  12. Index 를 사용하기 적합한 테이블은?

#### 트랜잭션(Transaction)이란 무엇인가?

  13. [ACID 란?](https://github.com/Next-Squad/Interview-Question/issues/21)
  14. [트랜잭션 격리 수준](https://github.com/Next-Squad/Interview-Question/issues/17)
  15. 트랜잭션의 상태
  16. 교착상태란?

#### 옵티마이저(Optimizer)란 무엇인가?

#### Statement, PreparedStatement 차이

#### CAP 이론(일관성, 가용성, 네트워크 분할 허용성)

#### [SQL과 NoSQL의 차이점](https://github.com/Next-Squad/Interview-Question/issues/4)

  17. 저장 방식에 따른 NoSQL 분류 (Key-Value Model, Document Model, Column Model)
  18. NOSQL 이 확장에 열려있는 이유는?

#### Redis 란 무엇인가?

#### ORM 이란 무엇인가?

  19. ORM 의 장점
</div>
</details>

<details>
<summary>☕ 자바 + 자료구조</summary>
<div markdown="4">
 
### 자바

1. java 언어의 장단점
2. [JVM 구조 & JAVA 동작 원리](https://github.com/Next-Squad/Interview-Question/issues/8)
3. OOP의 4가지 특징
4. [OOP의 5대 원칙 (SOLID)](https://github.com/Next-Squad/Interview-Question/issues/45)
5. 객체지향(Object-Oriented)이란
6. 객체지향 프로그래밍과 절차지향 프로그래밍의 차이
7. 클래스, 객체, 인스턴스의 차이
8. 객체(Object)란 무엇인가
9. 변수의 3가지 타입에 대해 설명해주세요.
10. Wrapper Class에 대해 설명하시오.
11. 자바의 접근 제어자
12. Autoboxing, Autounboxing에 대해 설명하시오.
13. non-static 멤버와 static 멤버의 차이에 대해 설명하시오.
14. main 메소드가 public static인 이유는?
15. Final 키워드의 용도에 대해 설명하시오.
16. Generic에 대해 설명하시오.
17. [==과 equals()의 차이에 대해 설명하세요. (동일성 vs 동등성)](https://github.com/Next-Squad/Interview-Question/issues/46)
18. Call by Reference와 Call by Value의 차이에 대해 설명하시오. + 자바에서 사용하는 방식은?
19. 추상 클래스와 인터페이스의 차이에 대해 설명하시오.
20. java reflection에 대해 설명하시오.
21. String, StringBuilder, StringBuffer의 차이점을 설명해주세요.
22. Java 8에 추가된 기능은 무엇이 있나요? (프로젝트를 진행하면서 버전을 11로 사용한 이유는?)
23. Lambda란 무엇이고 어떠한 장점이 있는가?
24. Stream API 특징이나 장점은 무엇이 있나요?
25. [Garbage Collector(GC)란? + 동작 방식 + 동작 알고리즘](https://github.com/Next-Squad/Interview-Question/issues/9)
26. GC에 의해 변수가 초기화되는 시점을 설정해주세요.
27. [JAVA에서 바이트코드에 대해 설명해보세요.](https://github.com/Next-Squad/Interview-Question/issues/38)
28. 예외처리 방법을 설명해주세요.
29. 자바에서 쓰레드를 구현하기 위한 2가지 방법을 간단하게 설명하시오.
30. Java Collections Framework
31. ArrayList와 LinkedList의 차이는 무엇인가요
32. [HashTable vs HashMap vs ConcurrentHashMap](https://github.com/Next-Squad/Interview-Question/issues/59)
33. CheckedException과 UnCheckedException의 차이
34. Error, Exception 에 대해 설명
35. Synchronized(동기화)를 하기 위한 방법은 무엇이 있나요
36. try-with-resource란?
37. Functional Interface란 무엇인가요?
38. Method Reference는 무엇인가요?
39. Optional 클래스는 무엇인가요?
40. 업캐스팅과 다운캐스팅이란?
41. this 키워드는 언제 사용되나요?
42. 오버로딩 오버라이딩
43. Java SE와 Java EE 애플리케이션 차이
44. java 직렬화(Serialization)와 역직렬화(Deserialization)란 무엇인가
45. Annotation
46. Mutable 객체와 Immutable 객체 차이점
47. [equals()와 hashCode()를 함께 오버라이딩 해야하는 이유가 무엇일까요?](https://github.com/Next-Squad/Interview-Question/issues/27)


### 자료구조
1. List Set 차이
2. 배열과 리스트
3. 스택
4. 큐
5. 해싱
6. 그래프
7. 해시와 해시테이블
8. 힙
9. 트리
- Tree, Binary Tree, BST, AVL Tree, MST, Red-Black Tree, 트리 순회
10. 자료구조를 이용해서 스택 구현하기
11. 2개의 스택으로 큐 구현하기
</div>
</details>

<details>
<summary>🌱 Spring + JPA</summary>
<div markdown="5">
 
### Spring
1. [Spring DI/IoC는 어떻게 동작하나요?](https://github.com/Next-Squad/Interview-Question/issues/2)
2. Spring Bean이란 무엇인가요?
3. 스프링 Bean의 생성 과정을 설명해주세요.
4. 스프링 Bean의 Scope에 대해서 설명해주세요.
5. IoC 컨테이너의 역할은 무엇이 있을까요?
6. [DI 종류는 어떤것이 있고, 이들의 차이는 무엇인가요?](https://github.com/Next-Squad/Interview-Question/issues/19)
7. Autowiring 과정에 대해서 설명해주세요.
8. [Spring Web MVC의 Dispatcher Servlet의 동작 원리에 대해서 간단히 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/48)
9. [프론트 컨트롤러 패턴이란 무엇인가요?](https://github.com/Next-Squad/Interview-Question/issues/49)
10. Servlet Filter와 Spring Interceptor의 차이는 무엇인가요?
11. Spring에서 CORS 에러를 해결하기 위한 방법을 설명해주세요.
12. Bean/Component 어노테이션에 대해서 설명해주시고, 둘의 차이점에 대해 설명해주세요.
13. [@Configuration 어노테이션에 대해서 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/50)
14. [Proxy에 대해서 설명해주세요.](https://github.com/Next-Squad/Interview-Question/issues/25)
    - CGLIB, JDK Proxy
15. Spring AOP를 활용해보셨다면, 어떻게 활용해보셨나요? 장점이 무엇일까요?
16. [POJO란 무엇인가요? Spring Framework에서 POJO는 무엇이 될 수 있을까요?](https://github.com/Next-Squad/Interview-Question/issues/53)
17. Spring Web MVC에서 요청 마다 Thread가 생성되어 Controller를 통해 요청을 수행할텐데, 어떻게 1개의 Controller만 생성될 수 있을까요?
18. Filter는 Servlet의 스펙이고, Interceptor는 Spring MVC의 스펙입니다. Spring Application에서 Filter와 Interceptor를 통해 예외를 처리할 경우 어떻게 해야 할까요?
19. Spring Application을 구동할 때 메서드를 실행시키는 방법에 대해 설명해주세요.
20. 의존성과 설정값을 생성자 인자로 주입해야 하는 이유에 대해 설명해주세요.
21. [PSA란 무엇인가요?](https://github.com/Next-Squad/Interview-Question/issues/16)
22. @Transacional이 붙은 서비스 내에서 @Async가 붙은 메소드를 호출하면 어떻게 될까요?

### JPA
1. JPA 영속성 컨텍스트의 이점(5가지)을 설명해주세요.
2. 영속성 컨텍스트 생명주기에 대해서 설명해주세요.
3. 1차 캐시, 2차 캐시에 대해서 설명해주세요.
4. dirty checking에 대해서 설명해주세요.
5. LazyInitializationException은 왜 발생할까요?
6. 스프링 프레임워크에서의 엔티티 매니저와 영속성 컨텍스트
7. JPA Propagation 전파단계를 설명해주세요.
8. JPA를 쓴다면 그 이유에 대해서 설명해주세요.
9. N + 1 문제는 무엇이고 이것이 발생하는 이유와 이를 해결하는 방법을 설명해주세요.
10. OSIV에 대해서 설명해주세요.
</div>
</details>

<details>
<summary> 자료구조 + 알고리즘(정렬) </summary>
<div markdown="4">

### 정렬 알고리즘
1. 퀵 정렬이 빠른 이유, 정렬에서 유리한 이유를 설명해주세요.
2. 퀵 소트와 머지 소트를 비교해주세요.`
3. 안정 정렬과 불안정 정렬의 차이와 예시를 설명해주세요.
4. 정렬하려는 자료가 현재 메모리보다 클 때, 어떻게 해서 정렬할 수 있을지 설명해주세요. (정렬하려는 자료가 1G인데 메모리가 100M이라면?)
5. 퀵 정렬에서 최악의 시간 복잡도가 나오는 케이스를 설명해주세요.
6. 버블 정렬(또는 다른 정렬)을 구현하는 과정을 설명해주세요.
7. 병합 정렬을 제자리 정렬로 구현하는 방법이 있을까요?
8. O(nlogn)인 정렬 알고리즘을 아는대로 설명해주세요.
9. 모두 정렬되어있는 배열에 하나의 원소를 추가할 때 사용하면 좋은 정렬 방법은 무엇이고 그 이유는 무엇인가요?

### 자료구조
1. 웹 브라우저의 앞으로 가기, 뒤로 가기, 링크 눌러서 새 창 띄우기를 구현하려면 어떻게 해야할까요?
2. 특정 유저의 점수를 입력하면 랭킹을 구하는 시스템을 구현하려고 할 때 어떤 자료구조를 쓰면 좋을까요?
3. 해시 테이블의 해시 충돌 해결방법에 대해서 설명해주세요.
4. 트리 순회 방식에 대해서 설명해주세요.
5. 특정 문자열을 검색할 때 사용하면 좋은 자료구조가 있나요?
6. 자가 균형 이진 탐색 트리에 대해 설명해주세요.
</div>
</details>

<details>
<summary>etc</summary>
<div markdown="4">

1. [docker란?](https://github.com/Next-Squad/Interview-Question/issues/57)
</div>
</details>

## ⛓ References

- [Dion - Backend-Interview-Question](https://github.com/ksundong/backend-interview-question)


- [SSAFY-CS-STUDY - Tech_interview](https://github.com/SSAFY-CS-STUDY)

- [JaeYeopHan - Interview_Question_for_Beginner](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)

- [안산학생 티스토리 블로그 백엔드 질문 60개](https://haejun0317.tistory.com/238) 


- [WeareSoft - 
tech-interview](https://github.com/WeareSoft/tech-interview)


- [jobhope - TechnicalNote](https://github.com/jobhope/TechnicalNote)

- [NESOY - Back-End 개발자 인터뷰 질문](https://github.com/NESOY/Back-end-Developer-Interview-Questions)


- [jeonyeohun - 기술면접을 준비하는 저장소](https://github.com/jeonyeohun/Getting-Ready-For-Interview)

- [Sir.LOIN 소프트웨어 엔지니어 인터뷰 질문 목록](https://github.com/sirloin-dev/meatplatform/blob/master/job-description/interview-questions.adoc)

