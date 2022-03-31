# İnsertion-Sort

Insertion Sort algoritması dizinin ilk elemanından başlayarak son elemana kadar karşılaştırma yaparak istenen değeri bulur ve ilk elemanla istenen değerin yerini değiştirir. 1 kere bu işlem yapıldıktan sonra dizinin ikinci elemanıyla aynı işlem yapılır ve bu şekilde devam eder.

- [22,27,16,2,18,6]->(n) İlk olarak listenin tüm elemanlarında gezer ve en küçük elemanı bulunca baştaki ile yer değiştirir.
- [2,27,16,22,18,6]->(n-1) Şimdi ikinin en küçük eleman olduğunu biliyoruz bu yüzden onu dahil etmeden diğer listenin elemnalarında gezip yine en küçük elemanı buluyoruz.
- [2,6,16,22,18,27]->(n-2) Bu işlemi tüm elemanlar sıralana kadar tekrarlıyoruz.
- [2,6,16,22,18,27]->(n-3) Zaten en küçük eleman o ilk eleman devam ediyor bir işlem yapmıyor.
- [2,6,16,18,22,27]->(1) Burada işlem bitiyor.
- 1'den n'e kadar olan sayıların toplamı n*(n-1)/2 = (n^2-n)/2 Dominant faktör n^2 olduğundan Big-O notation'ı O(n^2) olur.


- Bu algoritma için best case dizinin sıralı olması bu durumda time complexity O(n)
- Worst case (büyükten küçüğe sıralı olması) = average case ve O(n^2) 
- 18 dizinin ortasında yer alır ve average case olur.

## [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort’a göre ilk 4 adımı:

- [7', 3, 5, 8, 2', 9, 4, 15, 6]
- [2, 3', 5, 8, 7, 9, 4, 15, 6]
- [2, 3, 5', 8, 7, 9, 4, 15, 6]
- [2, 3, 5, 8', 7', 9, 4, 15, 6]
- [2, 3, 5, 7', 8, 9, 4, 15, 6]