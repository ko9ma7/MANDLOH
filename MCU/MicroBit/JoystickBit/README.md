# MANDLOH  
만들오의 자료공방 입니다.  
내용은 [블로그]에 담고 있습니다.  
* * *
## 송신 정보
- XX : 조이스틱 X축 값 (00~18)
- YY : 조이스틱 Y축 값 (00~18)
- R : 조이스틱 중심과의 거리 (0~9)
- TTT : 조이스틱 중심에서의 각도값 (000~360)
- A, B, C, D, E, F : 각 버튼들의 상태 (누른경우 1, 뗀경우 0)
- O : 조이스틱의 위치를 8방향으로 구분한 문자열 (Q, W, E, A, S, D, Z, X, C)
  * S는 중립위치
  * Q(11시), W(12시), E(1시) ~~ C(5시)

- 송신 예제
  * 조이스틱 12시 방향 : 09189090000000W  
  * 조이스틱 12시 방향 + 버튼 A 누름 : 09189090100000W
  * 조이스틱 5시 방향 : 18189315000000C
  * 조이스틱 5시 방향 + 버튼 A, B 누름 : 18189315110000C

[블로그]:  https://mandloh.tistory.com/35