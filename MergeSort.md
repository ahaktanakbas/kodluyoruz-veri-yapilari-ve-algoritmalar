# Kodluyoruz - Veri Yapıları ve Algoritmalar
## Merge Sort Projesi


*[16,21,11,8,12,22] -> Merge Sort*
*Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.*

>                                        [16,21,11,8,12,22]
>   1.                          [16,21,11]                  [8,12,22]
>   2.                      [16]       [21,11]           [8]       [12,22]
>   3.                      [16]   [21]   [11]           [8]   [12]   [22] 
>   4.                      [16]       [11,21]           [8,12]       [22]
>   5.                          [11,16,21]                  [8,12,22]
>   6.                                   [8,11,12,16,21,22]
>



*Big-O gösterimini yazınız.*

Her aşamada dizi ikiye bölünüyor. Bu sebeple n elemanlı dizi için;

> 2ˣ=n
>
> x=logn (Logaritma 2 tabanında)
>
> O(logn)