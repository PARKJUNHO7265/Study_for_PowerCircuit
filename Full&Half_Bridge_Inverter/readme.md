<h2>회로도</h2>

• 풀 브리지</br>
![image](https://github.com/PARKJUNHO7265/Study_of_SMPS/assets/87568714/ff7d07d6-1f54-475c-b97f-50dc8f22050e)

• 하프 브리지</br>
![image](https://github.com/PARKJUNHO7265/Study_of_SMPS/assets/87568714/041bb46c-5304-460c-8da5-370e0e2f957b)
</br></br></br>

<h2>특성</h2>

• 공통</br>
1. 출력전압 vo는 입력전압 VDC와 트랜지스터의 pwm에 의하여 정해진다.</br>
2. 부하전류 io는 인버터 출력전압과 부하의 특성에 따라 정해진다. </br>
3. 인버터의 입력전류 iDC는 부하전류 io와 트랜지스터의 pwm에 의하여 정해진다.</br>

• 차이</br>
1. 풀 브리지는 하프 브리지의
</br></br></br>

<h2>Orcad Pspice 회로도</h2>

• 풀 브리지</br>
![image](https://github.com/PARKJUNHO7265/Study_for_PowerCircuit/assets/87568714/4f36d45b-9687-4bb5-8d81-fe1be54db855)

• 하프 브리지</br>


•사용된 소자</br>
Q2N222 트랜지스터</br>
1N4004 다이오드</br>

• 파라미터</br>
입력전압 VDC : 5V</br>
트랜지스터 베이스 전원 (V3, V6) : 전압 5V, 주기 20ms, 딜레이 0ms</br>
트랜지스터 베이스 전원 (V4, V5) : 전압 5V, 주기 20ms, 딜레이 10ms</br>
</br></br>

<h2>시뮬레이션 결과</h2>

![image](https://github.com/PARKJUNHO7265/Study_for_PowerCircuit/assets/87568714/273abaab-d486-423b-ade0-929ab345f73e)

