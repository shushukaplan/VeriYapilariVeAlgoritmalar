# Proje 3
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları
Root 7 

* 5 solunda 
[5, 7, 1, 8, 3, 6, 0, 9, 4, 2]

* 1<7 solunda - 1<5 solunda 
[1, 5, 7, 8, 3, 6, 0, 9, 4, 2]

* 3<7 solunda - 3<5 solunda - 3<1 sağında
[1, 3, 5, 7, 8, 6, 0, 9, 4, 2]

* 6<7 solunda - 6<5 sağında 
[1, 3, 5, 6, 7, 8, 0, 9, 4, 2]

* 0<7 solunda - 0<5 solunda - 0<1 solunda 
[0, 1, 3, 5, 6, 7, 8, 9, 4, 2]

* 4<7 solunda - 4<5 solunda - 4<3 sağında - 4<1 sağında 
[0, 1, 3, 4, 5, 6, 7, 8, 9, 2]

* 2<7 solunda - 2<5 solunda - 2<3 solunda - 2<1 sağında 
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
-----

           7
        5    8
   1      6     9
0      3
   2      4

