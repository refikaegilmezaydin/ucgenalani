
package Deneme;
import java.util.Scanner;

public class alan {
    public static void main(String[] args) {
        double a,b,c,alan,cevre;

    Scanner lan = new Scanner(System.in);


    System.out.println("üçgenin 1. kenar uzunluğunu girin:"); a = lan.nextDouble();
    System.out.println("üçgenin 2. kenar uzunluğunu girin:"); b = lan.nextDouble();
    System.out.println("üçgenin 3. kenar uzunluğunu girin:"); c = lan.nextDouble();
    cevre=a+b+c;
    System.out.println("üçgenin çevre uzunluğunu:"+cevre);
    alan = Math.sqrt(cevre* (cevre-a)*(cevre-b)*(cevre-c));
    System.out.println("üçgenin alanı:"+alan);
    }

}


https://patika.dev/
