# hesap-makinasi
basit hesap makinası
package day01;

import java.util.Scanner;

public class day8 {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("1. Sayı= ");
        int a = scan.nextInt();
        System.out.print("2.Sayı= ");
        int b = scan.nextInt();

        System.out.print("İşlem Seçiniz= ");
        System.out.println("1-Toplam");
        System.out.println("2-Çıkarma");
        System.out.println("3-Çarpma");
        System.out.println("4-Bölme");
        System.out.print("işleminiz= ");
        int select = scan.nextInt();
        double sonuc = 0.0;


        if (select == 1) {
            sonuc = a + b;
        } else if (select == 2) {
            sonuc = a - b;
        } else if (select == 3) {
            sonuc = a * b;
        } else if (select == 4) {
            sonuc = a /(double) b;
        } else {
            System.out.println("Lütfen Geçerli Bir İşlem Giriniz !! ");
        }
        System.out.println("Sonuç = " + sonuc);
    }
}
