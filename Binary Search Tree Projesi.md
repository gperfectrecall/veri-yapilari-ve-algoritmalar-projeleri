* **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

> Root dizinin ilk sayısı olan 7 olarak belirlenebilir. Dizide sonraki gelen sayı root'tan küçükse ağacın solundan, büyükse ağacın sağından ilerlenir. Bu durumda;
>
> |   |   |   |   |   |   | 7 |   |   |   |   |
> |---|---|---|---|---|---|---|---|---|---|---|
> |   |   |   |   |   | / |   | \ |   |   |   |
> |   |   |   |   | 5 |   |   |   | 8 |   |   |
> |   |   |   | / |   | \ |   |   |   | \ |   |
> |   |   | 1 |   |   |   | 6 |   |   |   | 9 |
> |   | / |   | \ |   |   |   |   |   |   |   |
> | 0 |   |   |   | 3 |   |   |   |   |   |   |
> |   |   |   | / |   | \ |   |   |   |   |   |
> |   |   | 2 |   |   |   | 4 |   |   |   |   |
>
> Root 5 olsaydı ağaç çok daha dengeli bir şekilde yayılmış olacaktı. 