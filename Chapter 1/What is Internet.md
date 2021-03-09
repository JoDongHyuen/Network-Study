1.1 인터넷이란 무엇인가?
=======================
## 인터넷을 설명하기 위한 2가지 방법</br>
```
1. 인터넷 구성요소를 기술("nuts and bolts" view)

2. 어플리케이션에 서비스를 제공하는 인프라로 보는 관점
(Infrastructure that provide services to applications)
```

</br>1.1.2 구성요소로 본 인터넷 (nuts and bolts)
--------------------------
1. end system(종단시스템) = host (ex. 핸드폰, 냉장고, 다양한 IoT 등) 서로 연결해보자!
```
* 정n각형에 모든 대각선을 잇는거처럼 선이 너무 많이 필요한데? (대략 N^2)
* But 정n각형 중심에 점을 하나 찍고 그 점에서 모든 대각선을 이어보면? (N개의 선으로 해결 가능)
```
### 2. 위와 같이 중심에 점과 같은 역할을 하는 Packet Switch
### 3. 그리고 end system 과 Packet Swithch를 잇는 Link
### 4. collection of end system, Packet Switch and Link 를 이르는 말인 Network 