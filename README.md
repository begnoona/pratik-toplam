import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
    
    /*Java döngüler ile tek bir sayı girilene kadar
    kullanıcıdan girişleri kabul eden ve
    girilen değerlerden çift ve 4'ün
    katları olan sayıları toplayıp
    ekrana basan programı yazıyoruz.
     */


        Scanner inp=new Scanner(System.in);
        int sayi;
        int toplam=0;
        do{
        
            System.out.print("lütfen sayı giriniz : ");
            sayi=inp.nextInt();
            if(sayi%2==0 && sayi%4==0){
                toplam+=sayi;
            }
            
        }while(sayi%2==0);
        System.out.print(toplam);


    }
}
