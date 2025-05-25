# percentage error
import java.util.Scanner;
class calculator2
		
		{
			public static void main(String[] args) {
				
				{
					
					System.out.println("Enter the list of subjects");
					Scanner sc = new Scanner(System.in);
					System.out.println("Marks in Hindi");
					float b = sc.nextInt();
					System.out.println("Marks in English");
					float c = sc.nextInt();
					System.out.println("Marks in Maths");
					float d = sc.nextInt();
					System.out.println("Marks in Science");
					float e = sc.nextInt();
					System.out.println("Marks in GK");
					float f =  sc.nextInt();
					 float percentage = (b+c+d+e+f)/5;
					System.out.println(percentage);

				}
			}
		}
