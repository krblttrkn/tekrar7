# Ödev - Manav Kasa Programı
## Manav Kasa Programı
Java ile kullanıcıdan manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran programı yazın.

*Meyveler ve KG Fiyatları*
* Armut : 2,14 TL
* Elma : 3,67 TL
* Domates : 1,11 TL
* Muz : 0,95 TL
* Patlıcan : 5,0 TL

*Örnek Çıktı*
* Armut Kaç Kilo? : 0
* Elma Kaç Kilo? : 1
* Domates Kaç Kilo? : 1
* Muz Kaç Kilo? : 2
* Patlıcan Kaç Kilo? : 3
* Toplam Tutar : 21,68

```
import java.util.Scanner;

public class Manav {
    public static void main(String[] args){
        double a=2.14,e=3.67,d=1.11,m=0.95,p=5,toplam;
        double kg1,kg2,kg3,kg4,kg5;
        Scanner inp = new Scanner(System.in);
        System.out.print("Armut Kaç Kilo? :");
        kg1 =inp.nextDouble();
        System.out.print("Elma Kaç Kilo? :");
        kg2 =inp.nextDouble();
        System.out.print("Domates Kaç Kilo? :");
        kg3=inp.nextDouble();
        System.out.print("Muz Kaç Kilo? :");
        kg4 = inp.nextDouble();
        System.out.print("Patlıcan Kaç Kilo? :");
        kg5=inp.nextDouble();
        toplam = (a*kg1)+(e*kg2)+(d*kg3)+(m*kg4)+(p*kg5);
        System.out.print("Toplam Tutar :"+toplam);
    }
}
```
# Patika Profilim
<a href="https://academy.patika.dev/profile">**Patika Profilim**</a>