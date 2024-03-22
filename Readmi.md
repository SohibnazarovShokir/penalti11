```java
package uz.Shokir;

import java.util.Random;
import java.util.Scanner;

public class Penalti {
    public Penalti() {
    }

    public static void main(String[] args) {
        Random random = new Random();
        String[] darvozabon = new String[]{"Buffon", "K.Navas", "Casselis", "Oblak", "Noer", "De xea", "", "Labanib", "Nesterif"};
        int a = darvozabon.length;
        int b = random.nextInt(a);
        String[] uyinchi = new String[]{"Cristiano.Ronaldo ", "Klian Mbappe", "Leonel Messi", "Eldor Shomurodov", "Dragba", "Ronaldinyo", "", "Roberto Lewandoweski", "K.De Bruyne", "E.Haaland"};
        int s = uyinchi.length;
        int d = random.nextInt(s);
        Scanner scanner = new Scanner(System.in);
        System.out.println("______________");
        System.out.println("|            |");
        System.out.println("|     \ud83e\uddcd\u200d     |");
        System.out.println("Varatabon  --  " + darvozabon[b]);
        System.out.println("Fudbolchi -- " + uyinchi[d]);
        System.out.println("1. chapga \ud83e\uddcd\u200d♂️⚽\ud83d\udd1a");
        System.out.println("2. unga \ud83e\uddcd\u200d♂️⚽\ud83d\udd1c");
        System.out.println("3. to'g'riga \ud83e\uddcd\u200d♂️⚽\ud83d\udd1d");

        while(true) {
            while(true) {
                int varatar = random.nextInt(1, 4);
                int tepish = scanner.nextInt(4);
                if (varatar == tepish) {
                    System.out.println("Afsuski gol emas  \ud83d\ude12\ud83d\ude12\ud83d\ude12   " + darvozabon[b]);
                } else {
                    System.out.println("Gooool \ud83d\udc4d\ud83d\udc4d\ud83d\udc4d " + uyinchi[d]);
                    System.out.println(varatar);
                }
            }
        }
    }
}

```