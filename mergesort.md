Odev 1
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

Odev 1 Cozum
[16,21,11,8,12,22] yapısını ortdan ikiye böleriz,

1-[16,21,11] - [8,12,22] parçaları tekrar ikiye bölmeye devam ediyoruz,

2-[16-21]-[11]--[8,12]-[22] her eleman tek kalana kadar bölemeye devam ediyoruz,

3-[16]-[21]-[11]---[8]-[12]-[22] her eleman tek kaldı bir sonraki adımda gruplar içini küçükten büyüğe sıralıyoruz,

4-[11]-[16]-[21]---[8]-[12]-[22] sıralama yapıldı,

5-[8,11,12,16,21,22] her kümenin ilk elemanlarına bakılarak küçükten başlayarak yazıldı ve sonuç bulundu.

Big-O(nLogn)