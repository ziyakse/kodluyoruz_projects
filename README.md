# Kodluyoruz-Insertion-Sort-Project

_Sayı dizisinin ilk hali: [22,27,16,2,18,6]_

1. 27 sayısını (1.index) tutarak solundaki ile karşılaştırıyoruz. 27 sayısı 22 sayısından büyük olduğu için sıkıntı yok.
2. 16 sayısı (2.index) ile soldakiler ile karşılaştırıyoruz. 27'den küçük. Sonra bir solundakine daha bakıyoruz 22'den de küçük. Bu yüzden en küçük olduğunu farz ediyoruz ve en sola alıyoruz. Diğer sayıları da bir sağa kaydırıyoruz.

[**16**,**22**,**27**,2,18,6]

2. Sıra 3.index yani 2 sayısına bakmada. 2 sayısını soldakiler ile karşılaştırıyoruz ve 27'den, 22'den 16'dan da küçük olduğunu görüp en başa koyup diğer hepsini bir sağa kaydırıyoruz.

[**2**,**16**,**22**,**27**,18,6]

3. sıra 4.index yani 18 sayısına bakmakta. Daha önce anlattığım işlemleri yine yapıyorum ve sonuçları adım adım gösteriyorum:

[2,16,**18**,**22**,**27**,6]

[2,**6**,**16**,**18**,**22**,**27**] &rarr; Son hali.

Big-O gösterimi: işlemler 1'den n'e kadar gideceği için n.(n+1)/2 den n^2.

O(n^2).

Time Complexity: 18 sayısı ortada yerleşim yaptığından ne çok yol kat etmiştir ve bilgisayarı yormuştur ne de hiç hareket etmeyip enerji tasarrufu sağlamıştır. O yüzden Average case diyebiliriz.