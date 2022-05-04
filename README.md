# Patika-Veri-yapilari-ve-Algoritmalar-projeleri

## MERGE SORT
[16,21,11,8,12,22] 

[16,21,11] - [8,12,22]

[16] - [21,11] [8] - [12,22]

[16] - [11]-[21] [8] - [12]-[22]

[16] - [11,21] [8] - [12,22]

[16,11,21] - [8,12,22]

[8,11,12,16,21,22]

---

## INSERTION SORT
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevaplar: n -> [22,27,16,2,18,6] , n-1 -> [2,27,16,22,18,6] , n-2 -> [2,6,16,22,18,27] , n-3 -> [2,6,16,22,18,27] , n-4 -> [2,6,16,18,22,27] , n-5 -> [2,6,16,18,22,27]

2 - n=6, 1'den n'e kadar olan sayıların toplamı => n*(n+1)/2 => Big O Notation, O(n^2)=O(36)

3 - Worst Case(Sonda Olması) => O(n^2), Average Case => O(n^2), Best Case => O(n) Liste zaten sıralı ise hiçbir şeyin yeri değiştirilmezdi. Her eleman için bir kere işlem yapılırdı.

4 - 18 sayısı küçükten büyüğe sıralamada ortada yer aldığı için average casede değerlendirilebilir.

5 - [2,3,5,8,7,9,4,15,6], [2,3,5,8,7,9,4,15,6] , [2,3,4,8,7,9,5,15,6], [2,3,4,5,7,9,8,15,6]

## BINARY SEARCH TREE
[7,5,1,8,3,6,0,9,4,2]

root 7 dir.

5 rootun solunda bulunur, 8 rootun saginda bulunur
1 5'in solunda bulunur 3, 1'in saginda bulunur, 6 5'in saginda bulunur 0 1'in solunda bulunur 
9 8'in saginda bulunur 4 3'un saginda bulunur 2 3'un solunda bulunur.
