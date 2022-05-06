### Vücut Kitle Endeks Hesaplama:

 *Formulü : kg / (boymt*boymt)*

```java
import java.util.Scanner;
public class vkiHesaplama {
    public static void main(String[] args) {

        double kg, mt, vki;

        Scanner inp = new Scanner(System.in);

        System.out.print("Lütfen boyunuzu metre cinsinde giriniz :");
        mt = inp.nextDouble();

        System.out.print("Lütfen kilonuzu kg cinsinden giriniz :");
        kg = inp.nextDouble();

        vki = kg / (mt*mt);
        System.out.print("Vücut Kitle İndeksiniz :" + vki);

    }

    
}

```

