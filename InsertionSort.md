# PROJE 1
## Insertion Sort
* [22,27,16,2,18,6] -> Insertion Sort Adımları
27<22  [22, 27, 16, 2, 18, 6]

16<27  [22, 16, 27, 2, 18, 6]
16<22  [16, 22, 27, 2, 18, 6]

2<27  [16, 22, 2, 27, 18, 6]
2<22  [16, 2, 22, 27, 18, 6]
2<16  [2, 16, 22, 27, 18, 6]

18<27  [2, 16, 22, 18, 27, 6]
18<22  [2, 16, 18, 22, 27, 6]
18<16  [2, 16, 18, 22, 27, 6]
18<2   [2, 16, 18, 22, 27, 6]

6<27  [2, 16, 18, 22, 6, 27]
6<22  [2, 16, 18, 6, 22, 27]
6<18  [2, 16, 6, 18, 22, 27]
6<16  [2, 6, 16, 18, 22, 27]
6<2   [2, 6, 16, 18, 22, 27]
-----------
* Big-O Notation
O (n^2)
--------
* Time Complexity
Avarage Case: n^2
Worst Case: n^2
Best Case: n
--------

* Dizi sıralandıktan sonra 18 sayısı Avarange Case kapsamına girer.

* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı;

7<3  [7, 3, 5, 8, 2, 9, 4, 15, 6]
3<7  [3, 7, 5, 8, 2, 9, 4, 15, 6]
5<7  [3, 5, 7, 8, 2, 9, 4, 15, 6]
5<3  [3, 5, 7, 8, 2, 9, 4, 15, 6]
------------