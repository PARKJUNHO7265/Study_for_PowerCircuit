<h3>회로도</h3>

![image](https://github.com/PARKJUNHO7265/Study_for_PowerCircuit/assets/87568714/4045fcf6-c970-460a-9797-83ba9853a4d1)

<h3>특성</h3>

• 인버터의 출력전압 vo는 입력전압 VDC와 트랜지스터의 pwm에 의하여 정해진다.</br>
• 부하전류 io는 인버터 출력전압과 부하의 특성에 따라 정해진다. </br>
• 인버터의 입력전류 iDC는 부하전류 io와 트랜지스터의 pwm에 의하여 정해진다.</br>

<h3>Orcad Pspice 회로도</h3>

![image](https://github.com/PARKJUNHO7265/Study_for_PowerCircuit/assets/87568714/4f36d45b-9687-4bb5-8d81-fe1be54db855)

•사용된 소자</br>
Q2N222 트랜지스터</br>
1N4004 다이오드</br>

• 파라미터</br>
입력전압 VDC : 5V</br>
트랜지스터 베이스 전원 (V3, V6) : 전압 5V, 주기 20ms, 딜레이 0ms</br>
트랜지스터 베이스 전원 (V4, V5) : 전압 5V, 주기 20ms, 딜레이 10ms</br>

<h3>시뮬레이션 결과</h3>

![image](https://github.com/PARKJUNHO7265/Study_for_PowerCircuit/assets/87568714/273abaab-d486-423b-ade0-929ab345f73e)

