# 제어공학1 과제2 5주차 1차시 정리_2020732004 송주엽
## state variable model
### THE concept of state variable
![image](https://github.com/user-attachments/assets/a1edd3e9-4a3f-4867-9233-73f755227454)  
서로 다른 두개의 state를 정의(state가 항등식이 되면 안된다.)    
1차 미분방정식들로 표현
## 예시1
![image](https://github.com/user-attachments/assets/a7622724-be9d-41c2-9eb7-5ee6fdde056b)  
## 예시2
![image](https://github.com/user-attachments/assets/918af7f0-a5eb-49d6-9712-854c65ea03b3)

## state space equation

![image](https://github.com/user-attachments/assets/e3fc9803-b4dc-40fd-aa33-54cb2eec2914)  

다차 미분 방정식을 1차 미분방정식으로 표현하기 위해 state여러개를 정의해준다.   
![image](https://github.com/user-attachments/assets/5daa4cd2-e6d3-4cb6-b71b-3a0260d29a76)  

정의된 state를 state vector로 표현해준다.  
![image](https://github.com/user-attachments/assets/a8122eff-ac59-4360-afef-1f9f6c9c4ef8)   
라플라스 변환을 해주어 phi를 구하고 역변환을 통해 state transition matrix를 구할 수 있다.   
## 예시1  
![image](https://github.com/user-attachments/assets/54a6ea1f-2062-4884-998f-d494a0a6edc1)  

![image](https://github.com/user-attachments/assets/27e3f542-b233-4a9a-a1cf-bfab086d91a2)  
구해진 state space equation을 통해 matlab을 이용해 작성한 코드와 결과값은 다음과 같다.  

**Summary**  
state 란 내부의 시스템이다   
state를 정의하여 다차 미분방정식을 여러개의 1차 행렬 방정식으로 재 정의 해준다.   
1차 미분방정식은 컴퓨터가 쉽게 해결할 수 있기 때문에 효율적이다.   
참고로 state를 정의하는 법은 6차시 강의에서 다룬다.   
