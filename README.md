# Insertion-Sort-Projesi
[22,27,16,2,18,6] -> Insertion Sort

*Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1) İlk eleman sıralı, 22 sayısına göre düzenleme yapalım. [22,27,16,2,18,6]
2) İkinci elemana bakalım. 27 22den büyük bu yüzden yeri sabit kalır. [22,27,16,2,18,6]
3) Üçüncü elemana baktığımızda 22 ve 27den küçük olduğu için en başa gelir. [16,22,27,2,18,6]
4) Dördüncü elemana baktığımızda ise 2 önceki sayıların tamamından küçük olduğu için en başa gelir. [2,16,22,27,18,6]
5) Beşinci eleman olan 18 16dan büyük 22den küçük olduğu için üçüncü sıraya gelir. [2,16,18,22,27,6]
6) Altıncı eleman olan 6 ise 2den büyük 16dan küçük olduğundan ikinci sıraya gelir. [2,6,16,18,22,27]
Dizinin sıralanmış hali: [2,6,16,18,22,27]


*Big-O gösterimini yazınız.
Adım 1 -> n
Adım 2 -> n-1
Adım 3 -> n-2[2,3,4,8,7,9,5,15,6]

....
Adım n-1 -> 1


*Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
18 sayısı dizide ortada bulunuyor, bu nedenle Average case kapsamına girer.

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


*[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1) Dizideki en küçük eleman başa gelir. [2,7,3,5,8,9,4,15,6]
2) Geriye kalanlar arasından en küçük ikinci sıraya gelir. [2,3,7,5,8,9,4,15,6]
3) Geriye kalanlar arasından en küçük üçüncü sıraya gelir. [2,3,4,7,5,8,9,15,6]
4) Geriye kalanlar arasından en küçük dördüncü sıraya gelir. [2,3,4,5,7,8,9,15,6]
