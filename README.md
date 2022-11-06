# Insertion-Sort-Projesi
Insertion Sort Projesi (Patika)
Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

ÇÖZÜM:

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Adım 1: İlk olarak verilen dizinin sort türüne göre kaşılaştırması yapılır. 
[22,27,16,2,18,6]  
Adım2: 22, 27 , 16 , 2, 18, 6  diziyi dolaşıp düzünün en küçük elemanını bulmaya çalışırız. Bulduktan sonra da dizinin ilk elemanı ile yerlerini değiştiririz. 
Adım 3: 2, 27, 16 , 22, 18,  6  bu aşamada dizinin en küçük elemanı bulundu. Şimdi ikinci en küçük elemanı bulmalıyız. 
Adım 4: 2, 6, 16, 22, 18, 27  dizinin  ikinci en küçük elemanı da bulundu ve ikinci sırada olan 27 elemanı ile yer değişti
Adım 5: 2, 6, 16, 22, 18, 27 bu aşamada dizinin üçüncü elemanından daha küçük bir eleman bulmadık ve üçüncü eleman yer değiştirmedi. 
Adım 6: 2, 6, 16, 18, 22, 27  dizi bu aşamada sıralanmış oldu. 
Big o gösterimini yazınız. 
O(n^2)
 
Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı veri öbeğinin ortasında olduğu için avarage case kapsamına girer
 
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
Adım 1: [2,3,5,8,7,9,4,15,6]
Adım 2: [2,3,5,8,7,9,4,15,6]
Adım 3: [2,3,4,8,7,9,5,15,6]
Adım 4: [2,3,4,5,7,9,8,15,6]
 
 www.patika.dev
 
 [Patika.dev](https://www.patika.dev/tr)
 
