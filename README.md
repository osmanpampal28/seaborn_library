
<!-- Headers  -->

<!--
# H1
## H2
### H3
#### H4
##### H5
###### H6
-->

<!-- Bold -->
<!-- 
**Bu test Bold**
__Bu Test Bold__
 -->

<!-- italic -->
<!-- 
*Bu Test Italic*
_Bu Test Italic_ 
-->

<!-- StrikeThrough -->
<!-- 
~~Bu Test Çizgili~~ 
-->

<!-- Quoting -->
<!--
 > "Daha emin ve daha doğru olarak yüreyeceğimiz bir yol vardır: Büyük Türk kadınını çalışmamıza ortak kılmaktır" 
 -->

 <!-- Links -->
 <!--
  Go to [Google](https://google.com)

 Go to [Instagram](https://instagram.com)
  -->

<!-- Image -->
<!-- 
![resim](https://link) 
-->

<!-- 
<img src = "..." width = "50", height = "50"> 
-->

<!-- Lists -->
<!-- 
1. A
    1. aa
    2. bb
    3. cc
2. B
3. C 
-->

<!-- 
* A
    * AA
    * bb
    * cc
* B
* C 
-->

<!-- Task List -->
<!-- 
- [x] Task 1
    - [x] Task 2
    - [x] Task 3
- [x] Task 2 
-->

<!-- İgnoring Markdown -->
<!-- 
\*My Project\* 
-->

<!-- Emoji -->
<!-- 
:two_hearts:
:blue_hearts: 
-->

```bash
git clone https://github.com/osmanpampal28/seaborn_library.git

```
# Seaborn Veri Setleri
* **diamonds** <br>
_Belirli bazı elmaslar alınıp özelliklerinin veri seti_
    * carat: Elmas ağırlığı (0.2-5.01 gram)
    * cut: Elmasın kesim kalitesi (Fair, Good, Very Good, Premium, Ideal)
    * color: Elmasın rengi (J en kötüsü, D en iyisi)
    * clarity: Elmasın berraklığı (I1 (En kötü), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (En iyi))
    * depth: Toplam derinlik yüzdesi (z/ortalama(x, y) = 2 * z / (x + y) (43-79))
    * table: Elmasın en geniş noktasına göre derinliği (43-95)
    * price: Elmasın dolar bazında fiyatı (326-18.823)
    * x: Milimetrik cinsten uzunluğu (0-10.74)
    * y: Milimetrik cinsten genişliği (0-58.90)
    * z: Milimetrik cinsten derinliği (0-31.80)

* **iris** <br>
_Belirli bir cinse ait çiçek türlerini birbirinden ayırmak için yaprak uzunlukları ve genişlikleri kullanılır. Türlere göre bu özellikleri tutan veri setidir._
    * sepal_length: Cm cinsinden çanak yaprağın uzunluğu (4.3-7.9)
    * sepal_width: Cm cinsinden çanak yaprağın genişliği (2.0-4.4)
    * petal_length: Cm cinsinden taç yaprak uzunluğu (1.0-6.9)
    * petal_width: Cm cinsinden taç yaprak genişliği (0.1-2.5)
    * species: Bitkinin türü

* **flights** <br>
_Yıl ve aylara göre yapılan uçak kazalarında ölen insanların sayısını tutan veri setidir._
    * year: Kazanın yapıldığı yıl (1949- 1960)
    * month: Kazanın yapıldığı ay
    * passengers: Yolcu sayısı (104-622)

* **fmri** <br>
_Canlılarını beynine bağlanan bir cihaz aracılığıyla gelen sinyallerin yakalanıp, işlenen bir veri setidir._
    * subject: Verilerin toplandığı 14 kişi (14 canlı var ve bunların her biri 76 kez deneye sokuluyor.)
    * timepoint: Zaman noktaları (0-18)
    * event: Verinin nasıl toplandığı bölgeyi ifade ediyor. 
    * signal: Gelen sinyalin gücü (-0.255- 0.564)

* **mpg** <br>
_Arabaların özelliklerine göre sıralandığı veri setidir._
    * mpg: 1 galon benzin ile katedilen yol (1 galon = 3.7 L, 1 mil = 1.6 Km)(9-46.6)
    * cylinders: Arabada bulunan silindir sayısı
    * displacement: Motor hacmi (68-455)
    * horsepower: Beygir gücü (46-230)
    * weight: Ağırlık (1613-5140)
    * acceleration: Saniye cinsinden 0-100 Km/s hıza ulaşma süresi (8-24.8)
    * model_year: 1900'lü yıllara göre araba modeli yılı (70-82)
    * origin: Arabanın üretim yılı
    * name: Arabanın model ismi
    
* **planets** <br>
_Nasa'nın yayınladığı galaksi keşfi ile ilgili veri setidir_
    * method: Galaksilerin bulunması için gereli yöntem adı
    * number: Bulunan galaksilerdeki gezegen sayısı
    * orbital_period: Yörünge dönemini gösterir (0.09-730000)
    * mass: Galaksinin kütlesi (0.003, 25)
    * distance: Bulunan galaksinin bizim galaksimize olan uzaklığı
    * year: Galaksinin Bulunduğu sene (1989-2014)

* **tips** <br>
 _Bir restorandaki ödenen toplam para ile ilişkilendirilen değerlerin tutulduğu veri setidir_
    * total_bill: Hesabın tutarı (dolar) (3.07-50.81)
    * tip: Bırakılan bahşiş tutarı (dolar) (1-10)
    * sex: Hesabı ödeyen kişinin cinsiyeti (Male, Female)
    * smoker: Masada sigara içildi mi (Yes, No)
    * day: Haftanın hangi günü (Thur, Fri, Sat, Sun)
    * time: Günün hangi dilimi (Lunch, Dinner)
    * size: Masaya oturan kişi sayısı







