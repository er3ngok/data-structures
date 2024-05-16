# Selection Sort Projesi

### Soru 1) 

#### [22,27,16,2,18,6] -> Insertion Sort

### a) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

````
Adım 1. [22,27,16,2,18,6] -> Aynı kalır 22 < 27.
Adım 2. [22,27,16,2,18,6] -> 27 > 16 -> [22,16,27,2,18,6]
Adım 3. [22,16,27,2,18,6] -> 22 > 16 -> [16,22,27,2,18,6]
Adım 4. [16,22,27,2,18,6] -> 27 > 2 -> [16,22,2,27,18,6]
Adım 5. [16,22,2,27,18,6] -> 22 > 2 -> [16,2,22,27,18,6]
Adım 6. [16,2,22,27,18,6] -> 16 > 2 -> [2,16,22,27,18,6]
Adım 7. [2,16,22,27,18,6] -> 27 > 18 -> [2,16,22,18,27,6]
Adım 8. [2,16,22,18,27,6] -> 22 > 18 -> [2,16,18,22,27,6]
Adım 9. [2,16,18,22,27,6] -> 27 > 6 -> [2,16,18,22,6,27]
Adım 10. [2,16,18,22,6,27] -> 22 > 6 -> [2,16,18,6,22,27]
Adım 11. [2,16,18,6,22,27] -> 18 > 6 -> [2,16,6,18,22,27]
Adım 12. [2,16,6,18,22,27] -> 16 > 6 -> [2,6,16,18,22,27]
````

#### b) Big-O gösterimini yazınız.

````
Cevap: O(n^2)
````

#### c) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması 
Worst case: Aradığımız sayının sonda olması 
Best case: Aradığımız sayının dizinin en başında olması.

````
Cevap: Average Case
````

### Soru 2) 

#### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

````
Adım 1. [7,3,5,8,2,9,4,15,6] -> Dizinin en küçük elemanı olan 2, 7 ile yer değiştirir -> [2,3,5,8,7,9,4,15,6]
Adım 2. [2,3,5,8,7,9,4,15,6] -> 4 ile 5 yer değiştirir -> [2,3,4,8,7,9,5,15,6]
Adım 3. [2,3,4,8,7,9,5,15,6] -> 8 ile 5 yer değiştirir -> [2,3,4,5,7,9,8,15,6]
Adım 4. [2,3,4,5,7,9,8,15,6] -> 6 ile 7 yer değiştirir -> [2,3,4,5,6,9,8,15,7]
Adım 5. [2,3,4,5,6,9,8,15,7] -> 9 ile 7 yer değiştirir -> [2,3,4,5,6,7,8,15,9]
Adım 6. [2,3,4,5,6,7,8,15,9] -> 15 ile 9 yer değiştirir -> [2,3,4,5,6,7,8,9,15]
````
