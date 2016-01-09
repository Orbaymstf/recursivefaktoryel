// recursivefaktoryel
//mustafa orbay
//08.01.2016

package recursive;

import java.util.Scanner;

public class faktoryel {

    public static int fak(int n) {
        if (n==1) {
            return 1;
        }else 
            return n*fak(n-1);
    }
    public static void main(String[] args) {
        Scanner klv=new Scanner(System.in);
        System.out.println("faktöryeli alınacak sayıyı giriniz :");
        int sayı=klv.nextInt();
        System.out.println("5!= "+fak(sayı));
    }
}
