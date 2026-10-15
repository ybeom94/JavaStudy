### Java 기초 학습 기록
| 일차 | 학습 주제 | 핵심 키워드 |
|:---:|---|---|
| **Day 1** | Java 소개와 실행 구조 | JDK, JRE, JVM, `javac`, `main()`, 출력, 주석 |
| **Day 2** | 변수와 자료형 | 변수 선언, 리터럴, 기본형 8종, 참조형, 형변환, `Scanner` |
| **Day 3** | 연산자와 활용 | 산술, 증감, 비교, 논리, 대입, 삼항, 비트, 비트 이동 |
| **Day 4** | 제어문 | `if`, `else if`, `switch`, `for`, `while`, `do-while` |


# Day1
### Java 동작 원리
#### Java의 특징
- 이식성: 동일한 바이트코드를 운영체제에 맞는 JVM에서 실행할 수 있습니다.
- 객체 지향: 클래스와 객체를 중심으로 프로그램을 구성합니다.
- 자동 메모리 관리: 가비지 컬렉션을 지원합니다.
- 풍부한 라이브러리: 표준 API 및 외부 라이브러리를 활용할 수 있습니다.

#### JDK, JRE, JVM 구분
| 구성 요소 | 의미 | 역할 |
|---|---|---|
| **JDK** | Java Development Kit | 개발 도구(`javac` 등)와 실행 환경 제공 |
| **JRE** | Java Runtime Environment | Java 실행에 필요한 구성 요소 |
| **JVM** | Java Virtual Machine | 바이트코드를 읽고 실행하는 가상 머신 |