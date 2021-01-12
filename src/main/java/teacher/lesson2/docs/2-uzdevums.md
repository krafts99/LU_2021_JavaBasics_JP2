# Uzdevuma apraksts

# Tēma 1

## Uzdevums 1 - Atvērt iepriekš dotu Java HelloWord klasi un izpildīt ar IntelliJ izstrādes vidi.



## Uzdevums 1 - uzmest kauliņu.

- Noteikumi: tiks mesti 2 kauliņi (roll the dice) and tiks noģenerēeti 2 random cipari intervālā 1-6.
  No šiem 2 cipariem paņem summu un tā nosaka kas būs tālāk. ja summa ir 2,3,12 tad ir zaudēts. ja summa ir 7,11 tad ir vinnests. ja summa ir 4,5,6,8,9,10 tad  programma automātiski met kauliņu pa jaunu. Process notiek kamēr tiek vinnēts vai zaudēts
  pēc katra vinnesta vai zaudējuma parādīt cik spēles tika vinnētas vai cik zaudētas.

- Pagaidām vienkārši metam 2 kauliņus un izdruklājam pirmo , otro un summas ciparu.

### Soļi

- izveidojam jaunu klasi RollDice, ievietojam main metodi.

- main metodē ievietojam kodu

```jshelllanguage
// Math.random metodes lietošana. tā atgriež random vērtību 0 - 1. Rezultāts ir dubultais peldošais punkts.
// int rand = (int)(Math.random() * range) + min; 
// Lūdzu ievietojiet kodu main metodē!
int dice11 = (int)(Math.random() * 6) + 1;
int dice22 = (int)(Math.random() * 6) + 1;
System.out.println("pirmais kauliņš"+rand1+ "otrais kauliņš"+dice2 +" summa "+ (dice1 + dicee2);

```
- izpildām nospiežot zaļo stūrīti pie klases vai main metodes.