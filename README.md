# ๐ Kafka-akhq & Kafka-ELK stack ๊ตฌ์ถํด๋ณด๊ธฐ
## ๐ฅjconsole

Jconsole์ด๋ ์คํ์ค์ธ ์๋ฐ ํ๋ก์ธ์ค๋ฅผ ๋ชจ๋ํฐ๋ง ํ  ์ ์๋ ํด์ด๋ค. Kafka๋ฅผ ์คํํ๊ธฐ ์ํด์  Java๋ฅผ ์ค์นํด์ ํ๋ค.
JDK์ ํฌํจ๋์ด ์์ต๋๋ค ํ์ผ์ ์์น๋ jdk๊ฐ ์ค์น๋ ํด๋๋ด์ bin ํด๋์ ๋ค์ด์๋ค.

JMX๋ Java Management Extensions์ ์ฝ์๋ก JAVA ์์ฉํ๋ก๊ทธ๋จ์ ๋ชจ๋ํฐ๋ง๊ณผ ๊ด๋ฆฌ๊ธฐ๋ฅ์ ์ ๊ณต. 

Kafka๋ฅผ ๋ชจ๋ํฐ๋งํ๊ธฐ ์ํด kafka server์์ JMX ํฌํธ๋ฅผ ์ด์ด์ค ๋ค, Jconsole(์ด๋ ์ปดํจํฐ๋  ์๊ด์๋ค)์ ํตํด์ kafka server์ ๊ฐ์ข metric, CPU, Memory ๋ฑ๋ฑ์ ๋ชจ๋ํฐ๋ง ํ  ์ ์๋ค.
1.setup_kafka์ ํด๋น ์๋ฃ๋ฅผ ํฌ์คํ ํด๋์๊ณ , 2,3์์ Producer์ Consumer ์ค์  ํฌ์คํ์์๋ metric์ ๋ชจ๋ํฐ๋ง ํ  ์ ์๋ค. 

![initial](https://user-images.githubusercontent.com/70564639/175929538-a5e3f9c3-5e86-42fd-9959-8a80f9207d00.png)

๐ง akhq
![initial](https://user-images.githubusercontent.com/70564639/175927905-d9a4b1ab-1768-4b66-89ef-cfd60503ecd2.png)
๐จ
![initial](https://user-images.githubusercontent.com/70564639/175927918-eaf2def4-335c-4309-b468-bf6f78d067d7.png)

๐ฉ

