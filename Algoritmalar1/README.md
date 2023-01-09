# Algoritmalar Ödev-2


[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


----------------------------------------------------------------------------------------------------

Cevap

Merge Sort

[16,21,11,8,12,22] Merge Sort algoritmasına göre sıralarken, küçükten büyüğe sıralama yapmak yerine parçalara bölerek küçük gruplar haline getirip, birleştirirken sıralama yapmaya yönelik çalışıyor.

          16,21,11,8,12,22
             /         \
        16,21,11     8,12,22
          /    \      /     \
       16 21   11    8 12   22
        / \     \    / \     \
      16  21    11  8  12    22
        \/       |   \/       |
       16,21    11  8,12     22
          \    /       \   /
          11,16,21     8,12,22
              \          /
            8,11,12,16,21,22
Yeni dizi [8,11,12,16,21,22] şeklinde olur.

Sorgulama sayısı her seferinde (n-1), O(n); x=logn kez işlem yapıyor.

Yani; Big O Notation= O(nlogn)
