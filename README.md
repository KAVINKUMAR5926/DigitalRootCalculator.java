# DigitalRootCalculator.java
import java.util.Scanner;
public class Main
{
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int rem = n%9;
        if(n%9==0){
            System.out.print(9);
        }
        else{
            System.out.print(rem);
        }
    }
}
