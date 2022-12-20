import java.util.Scanner;
import java.lang.Math;

public class Hipotenüs {

    public static void main(String[] args){

        int kenar1,kenar2;
        double hipo,KenarTopla;
        double cevre;
        Scanner input = new Scanner(System.in);

        System.out.println("Üçgenin Bir Kenarını Giriniz");
        kenar1 = input.nextInt();
        System.out.println("Üçgenin Bir Kenarını Giriniz");
        kenar2 = input.nextInt();

        KenarTopla = (kenar1*kenar1) + (kenar2*kenar2);

        hipo = Math.sqrt(KenarTopla);

        System.out.println(" Hipotenüs = " + hipo);

        cevre = (hipo+kenar1+kenar2) / 2;

        System.out.println("Üçgenin Çevresi :"+ cevre*2);

    }
}
