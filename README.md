import java.util.Scanner;


public class Jala {

	public static void main(String[] args) {
		int arr[] = new int[100];
		Scanner input = new Scanner(System.in);
		System.out.println("Enter size of array:");
		int n = input.nextInt();
		System.out.println("Enter "+ n +" elements of array");
		for(int i=0;i<n;i++)
		{
			arr[i] = input.nextInt();
		}
		System.out.println("elements of array are:");
		for(int i=0;i<n;i++)
		{
			System.out.println(arr[i]);
		}
	}
}
