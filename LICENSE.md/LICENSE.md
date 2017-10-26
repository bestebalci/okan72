package okan7;
import java.util.Scanner;
public class okan72 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int n1 , n2;
		
		System.out.println("\t\tcarpim tablosu");
		System.out.println("\t1 \t2 \t3 \t4 \t5 \t6 \t7 \t8 \t9");
		System.out.println("--------------------------------------------------------------------------");
		
		for (n1 =1; n1<10; n1++) {
			for (n2 =1; n2<10; n2++) {
				System.out.print("\t" + n1*n2);
			}
			System.out.println();
		}
		
		

	}

}
