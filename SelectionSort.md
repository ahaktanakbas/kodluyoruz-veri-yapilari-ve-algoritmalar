# Kodluyoruz - Veri Yapıları ve Algoritmalar
## Selection Sort Projesi


*[22,27,16,2,18,6] -> Insertion Sort*
*Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.*

1. [*22,* 27, 16, *2*, 18, 6]
2. [**2,** *27,* 16, 22, 18, *6*]
3. [**2, 6,** *16,* 22, 18, 27]
4. [**2, 6, 16,** *22,* *18,* 27]
5. [**2, 6, 16, 18,** *22,* *27*]
6. [**2, 6, 16, 18, 22, 27**]

*Big-O gösterimini yazınız.*

Dizi 6 elemandan oluşmaktadır. (n=1)

1. [*22,* 27, 16, *2*, 18, 6] --> n
2. [**2,** *27,* 16, 22, 18, *6*] --> n-1
3. [**2, 6,** *16,* 22, 18, 27] --> n-2
4. [**2, 6, 16,** *22,* *18,* 27] --> n-3
5. [**2, 6, 16, 18,** *22,* *27*] --> n-4
6. [**2, 6, 16, 18, 22, 27**] --> n-5=**1**

1+(n-5)+...+(n-1)+n=n.(n-1)/2=(n²-n)/2
En yüksek dereceli değer n² olduğu için ***O(n²)***

*Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız*

*Average case: Aradığımız sayının ortada olması*
*Worst case: Aradığımız sayının sonda olması*
*Best case: Aradığımız sayının dizinin en başında olması*

Dizinin sıralı hali şu şekilde: [2, 6, 16, 18, 22, 27]
Aradığımız eleman 18 ise ise dizinin 4. elemanıdır.
Bu sebeple 18 sayısının bulunması **average case** kapsamındadır.


*[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.*

0. [*7,* 3, 5, 8, *2,* 9, 4, 15, 6]
1. [**2,** *3,* 5, 8, 7, 9, 4, 15, 6]
2. [**2, 3,** *5,* 8, 7, 9, *4,* 15, 6]
3. [**2, 3, 4,** *8,* 7, 9, *5,* 15, 6]
4. [**2, 3, 4, 5,** 7, 9, 8, 15, 6]
