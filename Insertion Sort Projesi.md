* **[22,27,16,2,18,6]** -> Insertion Sort
1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
> Kaynaklarda ***Insertion Sort*** için birkaç farklı yöntem gösterilmektedir. Bu ödevde ben, ***soldan başlayarak sırayla*** her bir sayının ***sağındaki sayıdan büyük olması halinde*** o sayıyla yer değiştirmesi ve ardından ***eğer solunda sayı bulunuyorsa onunla kıyaslanarak ondan da küçük olması halinde*** bu soldaki sayıyla da yer değiştirmesi yöntemine göre aşamaları belirledim. Belirtilen durumların ***aksi hallerinde*** sayılar arasında bir ***yer değiştirme gerçekleşmiyor.*** 
>
> [**22**,27,16,2,18,6]
>
> [22,**27**,16,2,18,6] 
>
> [22,27,**16**,2,18,6]
>
> [22,**16,27**,2,18,6]
>
> [**16,22**,27,2,18,6]
>
> [16,22,27,**2**,18,6]
>
> [16,22,**2,27**,18,6] 
> 
> [16,**2,22**,27,18,6]  
>
> [**2,16**,22,27,18,6] 
>
> [2,16,22,27,**18**,6] 
>
> [2,16,22,**18,27**,6] 
>
> [2,16,**18,22**,27,6] 
>
> [2,16,18,22,27,**6**] 
>
> [2,16,18,22,**6,27**]
>
> [2,16,18,**6,22**,27]
>
> [2,16,**6,18**,22,27]
>
> [2,**6,16**,18,22,27]
>
>  

2.	Big-O gösterimini yazınız.
> O(n^2)
3.	Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
>Average Case: Dizi küçükten büyüğe sıralandığında ***ortada kalan değer 16 veya 18*** olduğu için bu iki değerin gerçek konumunda yer aldığı sırasız diziler average case olarak değerlendirilebilir.
>
> Worst Case: **[27,22,18,16,6,2]** Büyükten küçüğe bir sıralama olduğu için her seferinde en yüksek n ve n-t sayılarıyla işleme devam edilir. Bu da worst case senaryoyu oluşturur. 
>
> Best Case: **[2,6,16,18,22,27]** Dizinin doğru sıralamasına sahip olduğu senaryo ise best case senaryodur. Herhangi bir adım gerekmeden dizi doğru sıradadır. 
4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

>18 sayısı ortada yer alan bir değer olduğu için average case kapsamına girer. 

* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

> [**7**,3,5,8,2,9,4,15,6]
>
> 1. [**3,7**,5,8,2,9,4,15,6]
>
> [3,**7**,5,8,2,9,4,15,6]
>
> 2. [3,**5,7**,8,2,9,4,15,6]
>
> [3,5,7,**8**,2,9,4,15,6]
>
> 3. [3,5,7,**2,8**,9,4,15,6]
>
> 4. [3,5,**2,7**,8,9,4,15,6]
