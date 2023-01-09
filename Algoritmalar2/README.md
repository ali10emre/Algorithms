# Algoritmalar2 Ödev

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


-------------------------------------------------------------------------------------------------------------


Cevap


Binary Search Tree

[7,5,1,8,3,6,0,9,4,2] Binary Search Tree'ye göre sıralarken, sıralı diziymiş gibi varsayıp indexte orta noktayı kök(root) alıyor. Bu durumda 10 elemanlı olduğu için 3 veya 6'yı root olarak alabiliriz. Sağ tarafa kendinden büyükler, sol tarafa kendinden küçükler yazılıyor.

6'yı Root Node olarak alalım.

             6         0.indexteki 7>6 sağa yazılır. 1.indexteki 5<6 sola yazılır.
            /\
           5  7        2.indexteki 1<6 ve 1<5 sola yazılır. 3.indexteki 8>6 ve 8>7 sağa yazılır.
          /    \
         1      8      4.indexteki 3<6 ve 3>1 sağa yazılır. 6.indexteki 0<6, 0<5, 0<1 sola yazılır.
        /  \     \
       0    3     9    7.indexteki 9>6, 9>7, 9>8 sağa yazılır.
            /\
           2  4        8.indexteki 4<6, 4<5, 4>1, 4>3 sağa yazılır. 
           
                       9.indexteki 2<6, 2<5, 2>1, 2<3 sola yazılır.
