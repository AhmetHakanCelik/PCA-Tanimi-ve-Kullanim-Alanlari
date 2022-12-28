# PCA Tanımı ve Kullanım Alanları

## Temel Bileşen Analizi (PCA) Nedir?

   Temel Bileşen Analizi (PCA), çok boyutlu uzaydaki bir verinin daha düşük boyutlu bir uzaya izdüşümünü, varyansı maksimizde edecek
 şekilde bulma yöntemidir. Uzayda bir noktalar kümesi için tüm noktalara ortalama uzaklığı en az olan “en uygun doğru” seçilir. Daha 
 sonra bu doğruya dik olanlar arasından yine en uygun doğru seçilerek bu adımlar, yeni bir boyutun varyansı belirli bir eşiğin altına 
 inene kadar tekrarlanır.

![Resim1](https://user-images.githubusercontent.com/76557881/209857525-b9edb06b-5950-4021-ba44-7e93681bc12a.png)

 Bu sürecin sonunda elde edilen doğrular bir doğrusal uzayın tabanlarını oluşturur. Bu taban vektörüne temel bileşen adı verilir. 
 Temel bileşenlerin 3 farklı özelliği vardır ;
 - Verinin temel bileşenleri birbirinden bağımsızdır.
 - Birinci temel bileşen toplam değişkenliği en çok açıklayan bileşendir.
 - Bir sonraki temel bileşen de kalan değişkenliği en çok açıklayan bileşendir.

![Resim]<img width="454" alt="Resim" src="https://user-images.githubusercontent.com/76557881/209857744-58dec75f-b4f1-4c5b-8da5-0e2f2bcd65fd.png"> 


## PCA’ nın Amaçları

Genel Olarak Temel Bileşen Analizi’ nin amaçları ;
- Verilerin boyutunu indirgemek  (değişken sayısını azaltmak) 
- Değişkenler arasındaki ilişki yapısını ortadan kaldırmak
- Diğer istatistiksel analizler için veri toplamak 

  şeklinde ifade edilebilir.

## PCA'nın Kullanıldığı Genel Alanlar

- Genetik
- Sağlık
- Enerji
- Elektronik
- Veri Bilimi

## Makine Öğrenmesinde Kullanımı

Veri Bilimi çalışmalarında çok sayıda değişken ile çalışılması gerekebilir.Bu durum eğitim(training) süresinin fazla olması, aşırı 
öğrenme(overlifting) ve çoklu doğrusal bağlantı(multicollinearity) gibi sorunları beraberinde getirir.Hazırlanan modellerin optimum 
sürede ve performansla çalışması gerekecektir.Bu problemleri aşmak için değişken seçimi ve boyut indirgeme yöntemleri kullanılabilir. 
Değişken seçiminde veri setindeki değişken korunur ya da tamamen kaldırılır. Boyut indirgemede ise mevcut değişkenlerin kombinasyonlarından 
oluşan yeni değişkenler yaratılarak değişken sayısı azaltılır. Böylece veri setindeki tüm özellikler hala mevcut ancak değişken sayısı azaltılmış
olur.

## Genel Kullanım Alanları
- Yüz Tanıma
- Örüntü Tanıma
- Resim Sıkıştırma

# KAYNAKÇA

 - https://en.wikipedia.org/wiki/Principal_component_analysis
 - http://www.zafercomert.com/IcerikDetay.aspx?zcms=78
 - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2757795/












 
