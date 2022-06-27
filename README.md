# 🌈 Kafka-akhq & Kafka-ELK stack 구축해보기
## 🟥jconsole

Jconsole이란 실행중인 자바 프로세스를 모니터링 할 수 있는 툴이다. Kafka를 실행하기 위해선 Java를 설치해아 한다.
JDK에 포함되어 있습니다 파일의 위치는 jdk가 설치된 폴더내에 bin 폴더에 들어있다.

JMX는 Java Management Extensions의 약자로 JAVA 응용프로그램의 모니터링과 관리기능을 제공. 

Kafka를 모니터링하기 위해 kafka server에서 JMX 포트를 열어준 뒤, Jconsole(어느 컴퓨터든 상관없다)을 통해서 kafka server의 각종 metric, CPU, Memory 등등을 모니터링 할 수 있다.
1.setup_kafka에 해당 자료를 포스팅 해두었고, 2,3에서 Producer와 Consumer 설정 포스팅에서도 metric을 모니터링 할 수 있다. 

![initial](https://user-images.githubusercontent.com/70564639/175929538-a5e3f9c3-5e86-42fd-9959-8a80f9207d00.png)

🟧 akhq
![initial](https://user-images.githubusercontent.com/70564639/175927905-d9a4b1ab-1768-4b66-89ef-cfd60503ecd2.png)
🟨
![initial](https://user-images.githubusercontent.com/70564639/175927918-eaf2def4-335c-4309-b468-bf6f78d067d7.png)

🟩

