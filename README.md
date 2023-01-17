# binarysearchtree


## Selection Sort Projesi
* İlk eleman en küçük elemanla yer değiştirecek:
* [**22**,27,16,2,18,**6**] 
* * ikinci eleman en küçük elemanla yer değiştirecek:
* [2,**27**,16,22,18,**6**]
* üçüncü elemandan sonra kendisinden daha küçük eleman yok, dördüncü eleman listedeki en küçük elemanla yer değiştirecek:
* [2,6,16,**22**,**18**,27]
* Dizi sıralaması tamamlandı:
* [2,6,16,18,22,27]
* Big O Notation: O(n^2)
* Dizi sıralandıktan sonra **18** elemanı dizinin ortasında olduğu için Average Case kapsamındadır.

## Merge Sort Projesi
*              [16,21,11,8,12,22]
*           [16,21,11]        [8,12,22]
*        [16,21]  [11]     [8,12]  [22]
*       [16]  [21]  [11]  [8]  [12]  [22] 
*        [16,21]      [8,11]    [12,22]
*           [8,11,16,21]       [12,22]
*             [8,11,12,16,21,22]
* Big O Notation: O(nlogn)

## Binary Search Tree Projesi
* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisi için root 5 olup her düğüm için küçük değerler sol tarafta büyük değerler sağ tarafta olacak şekilde yerleştirildi.
