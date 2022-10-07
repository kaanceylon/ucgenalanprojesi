# ucgenalanprojesi
Üç kenar uzunluğunu kullanıcıdan aldığınız üçgenin alanını hesaplayan programı yazınız.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
    int a, b, c;
    int u;
    double alan;


    Scanner giris = new Scanner(System.in);
    System.out.print("A kenarını giriniz : ");
    a = giris.nextInt();

    System.out.print("B kenarını giriniz :");
    b = giris.nextInt();

      System.out.print("C kenarını giriniz : ");
      c = giris.nextInt();

      u = (a+b+c) / 2;

      alan = Math.sqrt (u * (u - a) * (u - b) * (u - c));

      System.out.println( "Üçgenin çevresi : " + u);
      System.out.println( "Üçgenin alanı : " + alan);
