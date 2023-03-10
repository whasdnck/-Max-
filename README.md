# -Max-

### max 함수를 설명해줄게, max 함수는 수학으로 따지면 더하기라고 보면되고 내가준비한 코딩은 정수 3가지를 넣고 그 3가지 중에 제일 큰값을 출력하는 문을 만들려고해
### 일단 Scanner 를 import라는 명령어에 집중시켜서 출력할수있게 만들어야되, 그리고 그걸 다 써넣으면 출력을 이제 할수있어.
### a b c 에다가 max 라는 함수를 집어넣으면 System.out.println("셋 중 가장 큰 값은 " + max +  "입니다."); 출력문이 완성이되.

## MAX 코드
package sungil21102algo;

import java.util.Scanner;

class Max {

	public static void main(String[] args) {
		
		
		Scanner stdIn = new Scanner(System.in);
		
		System.out.println("한 개의 정수를 입력하세요.");
		int a = stdIn.nextInt();
		System.out.println("또 다른 정수를 입력하세요.");
		int b = stdIn.nextInt();
		System.out.println("마지막 정수를 입력하세요.");
		int c = stdIn.nextInt();
		
		int max = a;
		if(b > max) max = b;
		if(c > max) max = c;
		
		System.out.println("셋 중 가장 큰 값은 " + max +  "입니다.");
	}
}
