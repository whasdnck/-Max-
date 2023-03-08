# -Max-

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
