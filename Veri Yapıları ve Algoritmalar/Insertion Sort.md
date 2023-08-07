Proje 1 - Insertion Sort

1. Soru

[22,27,16,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre tüm aşamalarını yazınız.

ÇÖZÜM


*-[22,27,16,2,18,6] -> 22<27 -> eylem yok               
*-[22,27,16,2,18,6] -> 16<27 & 16<22 -> 16 basa
*-[16,22,27,2,18,6] -> 2<ilk 3 sayı -> 2 basa
*-[2,16,22,27,18,6] -> 18 3. sıraya
*-[2,16,18,22,27,6] -> 6 en başa
*-[2,6,16,18,22,27] -> ---


2. Soru

Big-O gösterimini yazınız

ÇÖZÜM

= O(n²)


3. Soru

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.


ÇÖZÜM

18 Sayısı dizinin ortasında bulunmasından dolayı Average case kapsamına girer.

