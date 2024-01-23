# Kodluyoruz-Merge-Sort-Project

_Sayı dizisinin ilk hali: [16,21,11,8,12,22]_

* Verilmiş olan sayı kümesini her birinin tek bir elemana düşürene dek ortadan bölüp ayırıyoruz.

[16,21,11,8,12,22] &rarr; [16,21,11] ve [8,12,22]

* Daha sonr abu iki kümeyi de bölelim.

[16,21,11] &rarr; **[16]** ve [21,11]

[21,11] &rarr; **[21]** ve **[11]**

* Elimizdeki bu sayıları küçükten büyüğe birleştirelim

[11,21]

[16] sayısını da uygun bir şekilde yerleştirelim

**[11,16,21]** bu sonuçtan önceki son elemanımız.

* Diğer elemanımız için de aynı şeyi uygulayalım.


[8,12,22] &rarr; **[8]** ve [12,22]

[12,22] &rarr; **[12]** ve **[22]**

Sonuç: **[8,12,22]**

* En son olarak da [8,12,22] ile [11,16,21] kümelerini birleştirelim. Birleştirme mantığı: en soldaki sayı, diğer kümenin en solundakinden küçükse yaz değilse diğer kümenin en solundakini yaz.

**[8,11,12,16,21,22]**
