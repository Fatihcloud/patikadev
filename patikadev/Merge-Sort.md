# Merge-Sort

Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor.

- [16,21,11,8,12,22]-> Verilen liste bu ilk önce ikiye bölelim.

- [16,21,11] [8,12,22]-> Şimdi bunu bir daha ikiye bölelim.

- [16] [21,11] [8] [12,22]-> İki ve daha az parçaya ulaştı durucak ve her biri kendi içinde sıralama yapıcak.

- [16] [11,21] [8] [12,22]-> şimdi yeniden ayrılmış halden bütüne gidilecek ve bu yapılırken sıralamaya devam edilecek.

- [11,16,21] [8,12,22]-> Hala bütün elde edilmedi devam ediyoruz.

- [8,11,12,16,21,22]-> Tam haline ulaştık ve sıralı halinede ulaşmış olduk.

- O(n)*O(log(n)) = O(nlog(n))