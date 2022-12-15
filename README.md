# JAVA-IO-PROGRAM



import java.io.*;
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        int no;
        
        System.out.println("ENTER NUMBER");
        Scanner s=new Scanner(System.in);
        no=s.nextInt();
        System.out.println("ENTERED NO IS: " + no);
    }
}
