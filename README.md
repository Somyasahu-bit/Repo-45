# Repo-45
Write a program to check Divisibility of 5
//Check Divisibility of 5
import java.util.Scanner;
class Divisible{
    public static void main(String[] args) {
    int n;
    System.out.println("Enter any number");
    Scanner r = new Scanner(System.in);
    n = r.nextInt();
    
    if (n%5==0)
    {
       System.out.println("Divisible by 5");
    }
    else 
    {
       System.out.println("Not Divisible by 5");
    }
    
}
}
