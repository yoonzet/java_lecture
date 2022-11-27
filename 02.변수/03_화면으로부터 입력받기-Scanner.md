**Scanner란?** - 화면으로 부터 데이터를 입력 받는 기능을 제공하는 클래스

**사용방법**

1. import문 추가

```java
import java.util.*;
```

2. Scanner클래스의 객체생성

```java
Scanner scanner = new Scanner(System.in);
```

1. Scanner 객체사용

```java
int num = scanner.nextInt(); //화면에서 입력받은 정수를 num에 저장
System.out.println(num);

//또는 아래와 같이 표현도 가능(연습을 위해 번거롭지만 이런 방법도 있음을 알아두기..ㅎㅎ)

	String input = scanner.nextLine(); //nextLine()은 한 행을 뜻함, 화면에 입력받은 데이터를 input에 저장
	int num = Integer.parseInt(input); //문자열(input)을 정수로 바꿈
	System.out.println(num);

```

전체 코드

```java
import java.util.*; // 1. import문 추가

public class Scanf {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		// 2. Scanner클래스의 객체생성
		Scanner scanner = new Scanner(System.in);

		// 3. Scanner 객체 사용
//		int num = scanner.nextInt();
//		int num2 = scanner.nextInt();
//		System.out.println(num);
//		System.out.println(num2);
		
	String input = scanner.nextLine();
	int num = Integer.parseInt(input);
	System.out.println(num);
	}

}
```
