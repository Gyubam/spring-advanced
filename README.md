# spring-advanced


### 템플릿 콜백 패턴

![image](https://user-images.githubusercontent.com/71515740/197515837-65c2fee3-70f2-453b-965e-30033c62711f.png) </br>
- 핵심기능과 부가기능의 분리
- 템플릿 안에서 변하는 부분은 call() 메서드를 호출해서 처리
- 변하는 부분은 자식 클래스에 두고 상속과 오버라이딩을 사용해서 처리


</br></br>


### 전략 패턴

![image](https://user-images.githubusercontent.com/71515740/197516283-43bfec4b-85a7-4299-87a8-8aeb1c37a8c9.png) </br>
- 변하지 않는 부분을 Context에 작성
- 변하는 부분을 Strategy 인터페이스에 작성 및 구현해서 사용
- Context는 변하지 않는 템플릿 역할, Strategy는 변하는 알고리즘 역할
