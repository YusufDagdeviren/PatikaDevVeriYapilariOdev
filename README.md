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

