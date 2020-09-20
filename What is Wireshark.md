# What is Wireshark?

**Wireshark**

- 네트워크상의 패킷을 포착하고 분석해서 보여주는 툴

![image-20200921001404558](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20200921001404558.png)

- 제일 상단부터 Packet List Window, Packet Details Window, Packet Bytes Window 라고 칭함
- **Packet List Window**
  - 캡처한 패킷들을 시간 순서대로 나열해서 보여줌
  - 항목의 의미
    - Number : 캡처된 순서
    - Time : 패킷이 캡처된 시간
    - Source & Destination : 패킷의 출발지와 목적지 주소
    - Protocol : 패킷이 포함하는 주요 프로토콜
    - Length : Byte 단위의 길이
    - Info : 해당 패킷이 담고 있는 주요 정보
- **Packet Details Window**
  - 패킷에 대한 자세한 정보들을 보여줌
- **Packet Bytes Window**
  - 선택된 부분에 해당하는 Hexadecimal data를 보여줌