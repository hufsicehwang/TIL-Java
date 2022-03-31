## 🦊TIL-2🦊

# 스택 메모리
![image](https://user-images.githubusercontent.com/67450413/161033676-ce2d7313-b11f-4b13-a6f1-999593b1fd58.png)
- 스택 : 함수가 호출될 때 지역 변수들이 사용하는 메모리
- 함수의 수행이 끝나면 자동으로 반환 되는 메모리
- 지역 변수들이 클래스(블록) 단위로 저장 된다.

# 힙 메모리
![image](https://user-images.githubusercontent.com/67450413/161033866-edd55289-1cdc-470c-b99a-3842e533b321.png)
- 생성된 인스턴스는 동적 메모리(heap memory) 에 할당됨
- C나 C++ 언어에서는 사용한 동적 메모리를 프로그래머가 해제 시켜야 함 ( free() 난 delete 이용)
- 자바에서 Gabage Collector 가 주기 적으로 사용하지 않늠 메모리를 수거
- 하나의 클래스로 부터 여러개의 인스턴스가 생성되고 각각 다른 메모리 주소를 가지게 됨
