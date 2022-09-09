# sinifigecmeDurumu

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner inp = new Scanner(System.in);
        int sbt = 55;
        int ders = 0;
        double toplam=0;
        int Matematik, Fizik, Turkce, Kimya, Muzik  ;
        System.out.println("Lütfen Matematik Notunuzu Giriniz");
        Matematik = inp.nextInt();
        if (0 <= Matematik && Matematik <= 100) {
            ++ders;
            toplam += Matematik;
            System.out.println("toplam"+toplam);

        }

        System.out.println("Lütfen Fizik Notunuzu Giriniz");
        Fizik = inp.nextInt();

        if (0 <= Fizik && Fizik <= 100) {
            ++ders;
            toplam += Fizik;
            System.out.println("toplam"+toplam);

        }
        System.out.println("Lütfen Türkçe Notunuzu Giriniz");
        Turkce = inp.nextInt();
        if (0 <= Turkce && Turkce <= 100) {
            ++ders;
            toplam += Turkce ;
            System.out.println("toplam"+toplam);

        }
        System.out.println("Lütfen Kimya Notunuzu Giriniz");
        Kimya = inp.nextInt();
        if (0 <= Kimya && Kimya <= 100) {
            ++ders;
            toplam += Kimya ;
            System.out.println("toplam"+toplam);

        }
        System.out.println("Lütfen Müzik Notunuzu Giriniz");
        Muzik = inp.nextInt();
        if (0 <= Muzik && Muzik <= 100) {
            ++ders;
            toplam += Muzik ;
            System.out.println("toplam"+toplam);

        }

        double ortalama = toplam / ders;
            if (ortalama >= sbt) {
                System.out.println("Sınıfı " + ortalama + " ortalama ile geçtiniz...Tebrikler");
            } else {
                System.out.println("Sınıfta Kaldınız.");
            }
        }
    }
