# PatikaDev VeriYapıları Bitirme Ödevi
***
Patika Dev'in Veri yapıları için bitirme ödevidir.

# Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

* 1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* 2-Big-O gösterimini yazınız.
* 3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
* 5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1-)Insertion Sort Aşamaları
-------------------------
```
1.Aşama -->[2,27,16,22,18,6]
2.Aşama -->[2,6,16,22,18,27]
3.Aşama -->[2,6,16,18,22,27]
```
## 2-)Big-O gösterimi
-----------------
```
Worst Case = O(n^2)
Avarage Case = O(n^2)
Best Case = O(n)
```
## 3-)Time Complexity
-------------
```
Best Case : [2,6,16,18,22,27]
Worst Case : [27,22,18,16,6,2]
```
## 4-)18 sayısının case durumu
-----------------
```
Dizi sıralandıktan sonra [2,6,16,18,22,27] durumda olduğu için 18 sayısıda dizinin ortasında olduğu 
için avarage case sayılabilir.
```
## 5-)[7,3,5,8,2,9,4,15,6] dizisinin ilk 4 adımı
----------------------
```
1.Aşama -->[2,3,5,8,7,9,4,15,6]
2.Aşama -->[2,3,4,8,7,9,5,15,6]
3.Aşama -->[2,3,4,5,7,9,8,15,6]
4.Aşama -->[2,3,4,5,6,9,8,15,7]
```
# Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort
* 1-)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* 2-)Big-O gösterimini yazınız.
## 1-) [16,21,11,8,12,22] Dizisinin Sıralanmasi
----------------
```
                R                    L
1.Aşama -->[16,21,11]             [8,12,22]
2.Aşama -->[16,21],[11]           [8,12],[22]
3.Aşama -->[16],[21],[11]         [8],[12],[22]
4.Aşama -->[16,21],[11]           [8,12],[22]
5.Aşama --> [11,16,21]            [8,12,22]
6.Aşama -->        [8,11,12,16,21,22]
```
## 2-) Big-O Gösterimi
--------------------
```
Worst Case = O(nlogn)
Avarage Case = O(nlogn)
Best Case = O(nlogn)
```
# Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
## Binary Search Tree Aşamaları
***
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinde soldan okumaya başlarız yani ilk kökümüz 7 olsun kökten büyük olanları kökün sağına küçük olanları ise soluna yazarak ilerleyelim
```
```
            7
           /       
```
```
            7
           /
          5 
```
```
            7
           /
          5
         /
        1   
```
```
            7
           / \
          5   8
         /
        1   
```
```
            7
           / \
          5   8
         /
        1
        \
         3        
```
```
            7
           / \
          5   8
         / \
        1   6 
        \
         3        
```
```
            7
           / \
          5   8
         / \
        1   6 
       / \
      0   3        
```
```
            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3        
```
```
            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3
           \
            4        
```
```
            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3
         / \
        2   4        
```
[www.patika.dev](https://www.patika.dev)