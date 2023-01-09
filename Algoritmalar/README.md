# Algoritmalar Ödev


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


-----------------------------------------------------------------------------------------------------------------------------
Cevap 


[22,27,16,2,18,6] dizisini Insertion Sort algoritması ile çalıştırırsak; dizinin 2.elemanı yani 27 başlangıç elemanı seçilir. 27 ile 22 kıyaslanıp küçükse soluna büyükse sağına yazılır. Buradaki durumda büyük o yüzden sağda kalır.

Dizinin 3.elemanı olan 16, önce 27 ile sonra 22 ile kıyaslanır. Küçük olduğu için sola yazılır. Yeni dizi [16,22,27,2,18,6] olur.

Dizi bu şekilde kıyaslamalar yapılarak son elamana kadar gelinir.

Dizinin son elamanı olan 6 da kıyaslanıp yazılır. Böylelikle [2,6,16,18,22,27] sıralı dizisi elde edilir.

18 sayısı dizinin en son basamağından bir önce yerleştirildiği için Worst Case'e yakındır ama Average Case senaryosu kapsamına girer.

Big O Notation = İşlem sayısı n, n-1, n-2...1 şeklinde olacağından, işlem sayısı toplamı n.(n+1)/2; dominant faktörü n²'dir. O(n²)

--------------------------------------------------------------------------------------------------------------------------------------

Selection Sort

[7,3,5,8,2,9,4,15,6] dizisini Selection Sort algoritması ile çalıştırdığımızda ilk 4 adımı:

En küçüğü bulup baştaki elemanla yer değiştirerek çalıştığı için;

2 ile 7 yer değişecek. [2,3,5,8,7,9,4,15,6] 2-3 sıralı denk geldi, 4 ile 5 yer değişecek. [2,3,4,8,7,9,5,15,6] 5 ile 8 yer değişecek. [2,3,4,5,7,9,8,15,6] 6 ile 7 yer değişecek ve yeni dizi bu şekilde olacaktır. [2,3,4,5,6,9,8,15,7]





