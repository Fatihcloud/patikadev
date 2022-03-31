## İnsertion-Sort

Insertion Sort algoritması dizinin ilk elemanından başlayarak son elemana kadar karşılaştırma yaparak istenen değeri bulur ve ilk elemanla istenen değerin yerini değiştirir. 1 kere bu işlem yapıldıktan sonra dizinin ikinci elemanıyla aynı işlem yapılır ve bu şekilde devam eder.

- [22,27,16,2,18,6]-> İlk olarak listenin tüm elemanlarında gezer ve en küçük elemanı bulunca baştaki ile yer değiştirir.
- [2,27,16,22,18,6]-> Şimdi ikinin en küçük eleman olduğunu biliyoruz bu yüzden onu dahil etmeden diğer listenin elemnalarında gezip yine en küçük elemanı buluyoruz.
- [2,6,16,22,18,27]-> Bu işlemi tüm elemanlar sıralana kadar tekrarlıyoruz.
- [2,6,16,22,18,27]-> Zaten en küçük eleman o ilk eleman devam ediyor bir işlem yapmıyor.
- [2,6,16,18,22,27]-> Burada işlem bitiyor.