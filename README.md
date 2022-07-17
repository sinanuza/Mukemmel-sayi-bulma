# Mukemmel-sayi-bulma
www.patika.dev Mukemmel Sayi Bulma








import java.util.Scanner;

public class Mukemmel_sayi {
    public static void main(String[] args) {
        int a,b=0;
        System.out.println("Lutfen sayi giriniz:");
        Scanner input= new Scanner(System.in);
        a=input.nextInt();
        for (int i=1;i<a;i++){
            if (a%i==0){
                b=b+i;
            }
        }if (a==b){
            System.out.println(a+" bir mukemmel siyidir.");
        }else {
            System.out.println(a+" bir mukemmel sayi degildir.");
        }
    }
}
