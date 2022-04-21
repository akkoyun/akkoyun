![Repos Badge](https://badges.pufler.dev/repos/akkoyun) [![Visits Badge](https://badges.pufler.dev/visits/akkoyun/akkoyun)](http://www.github.com/akkoyun) [![Want to buu](https://img.shields.io/badge/Web_Store-Tindie-blue.svg)](https://www.tindie.com/stores/akkoyun)

## DWIN TFT Dokunmatik Ekranlar

**DWIN** ile tanışalı 1 yıldan fazla oldu, bu süre içerisinde bir çok endüstriyel projede kullanma fırsatımız oldu. Sizlerinde projelerinizde kolayca kullanabilmeniz için dWin ve alternatif üretici olan Nextion arasındaki farkları anlatmaya çalışacağım.

DWIN ekranlarının en cazip yönü fiyat / Performans oranı üst seviyede olması ve rakiplerine nazaren çok avantajlı olmasıdır. Uygulamalarınıza özel ebat, çözünürlük ve koşullar yanı sıra kapasitif, rezisif yada dokunmatiksiz seçenekler ile çok geniş bir ürün yelpazesine sahiptir. 

Sizde projeleriniz de dWin ürünlerini kullanmak isteyip endişelere sahipseniz ücretsiz numune isteyerek ön testlerinizi kolayca yapabilirsiniz. Ayrıca ekran tasarımları ve her türlü sorularınız için bizimle iletişime geçebilirsiniz.

**Ücretsiz numune için lütfen bize yazınız. (Aşağıda yer alan listeden ürün kodunu seçebilirsiniz)**

[![E-Mail](https://img.shields.io/badge/Teknik_Destek-Mehmet_Gunce_Akkoyun-blue.svg)](mailto:akkoyun@me.com) [![E-Mail](https://img.shields.io/badge/Teknik_Destek-Recep_Senbas-blue.svg)](mailto:recepsenbas@gmail.com)

---

### Fiyat Karşılaştırması

Aşağıda aynı Teknik Özellikler sahip iki ekran arasında fiyat karşılaştırması var;

* DWIN   5", 800 x 480, Kapasitif Dokunmatik:  22.10 ABD Doları. (Bkz. [Kaynak 1](https://www.alibaba.com/product-detail/DWIN-LCD-Module-5-0-inch_62593509775.html?spm=a2700.galleryofferlist.normal_offer.d_title.5489d07aU8WWFO))
* Nextion 5", 800 x 480, Rezistif Dokunmatik:  60.00 ABD Doları. (Bkz. [Kaynak 2](https://www.alibaba.com/product-detail/Nx8048t050-Nx8048t050-Tft-Display-5-0_1600056199459.html?spm=a2700.galleryofferlist.normal_offer.d_image.67df2db4pAK9fL&s=p))

---

### 2022 Fiyat Listeleri

* [Endüstriyel Sınıf LCD Fiyat Listesi](/dWin/DWIN%20HMI%20LCD%20Display%20for%20industrial%20grade%20end%20applications.pdf)
* [Medikal Sınıf LCD Fiyat Listesi](/dWin/DWIN%20HMI%20LCD%20Display%20for%20medical%20grade%20end%20applications.pdf)
* [Ticari Sınıf LCD Fiyat Listesi](/dWin/DWIN%20HMI%20LCD%20Display%20for%20commercial%20grade%20end%20applications.pdf)
* [COF Sınıf LCD Fiyat Listesi](/dWin/DWIN%20HMI%20LCD%20Display%20for%20COF%20grade%20end%20applications.pdf)

Yukarda gördüğünüz gibi fiyat konusunda müthiş fark söz konusu, Peki ya performans ve kalite konusunda nasıl bir fark var? Aşağıdaki tabloya bakarsanız aslında daha az parayla çok daha iyi ekran alabileceğinizi anlarsınız.

| | dWin 5" TFT LCD | Nextion 5" TFT LCD |
|--|----------------|--------------------|
| Renk Çözünürlüğü | 16777216 Renk (24 bit) | 65536 (16 bit) |
| Dokunmatik Teknolojisi | Kapasitif yada Rezisif | Rezisif |
| Çözünürlük | 800x480 | 800x480 |
| Arka Aydınlatma | LED | LED |
| Çalışma Voltajı | DC 4v5-5v0 | DC 6v0-35v0 |
| Çalışma Sıcaklığı | -20C - +70C | -20C - +70C |
| Haberleşme Portu | UART 1 Kanal + RS485 | UART 1 Kanal |
| Yazılım Yükleme | SD & USB | SD & USB |
| Geliştirme Platformu | dWin Digus Tool | Nextion Editor |

---

### Sıkça Sorulan Sorular

##### Bu ekrana güvenerek endüstriyel projeler yapabilir miyim ?

Tabi ki, bende ilk aldığımda tereddüt ettim, ama şimdi arazide çalışan 1000'dan fazla cihazımız var.

##### Peki neden bu ekran ucuz ?

DWIN firması Çin pazarının %80 hakim ve Pandemi'den sonra yurtdışına açılmaya başladı.

##### Ücretsiz numune alabilirmiyim ?

Denemek isteyen kişilere Ücretsiz Numune ekran gönderilebilmektedir. Eğer sizde bir şirket sahibi veya Ar-Ge mühendisi olarak bir firmada çalışıyorsanız örnek isteme formunu doldurarak ücretsiz numune alabilirsiniz. (Örnek isteme limiti 60$ dır.)

##### Nextion LCD yerine DWIN LCD'yi cihazlarıma bağlayabilir miyim ?

Tabi ki, yapmanız gereken tek şey +5V, GND, Tx ve Rx kablolarının lehimlerini söküp DWIN ekranına bağlamak. işte bu kadar basit !

##### Peki ya Haberleşme Kısımı nasıl olacak ?

Haberleşme kısmı, ekrandan data almak için 9 Byte'lık bir veriyi yakaladıktan sonra Adres ve veri kısmını compare ederek işlem yapmak kafi olacaktır, keza 9 Byte'lık veriyi Printf komutu ile gönderebilirsiniz. Bu konuda teknik destek almak için bana ulaşabilirsiniz.

---

[![Support me](https://img.shields.io/badge/Support-PATREON-GREEN.svg)](https://www.patreon.com/bePatron?u=62967889) ![Twitter Follow](https://img.shields.io/twitter/follow/gunceakkoyun?style=social) ![YouTube Channel Views](https://img.shields.io/youtube/channel/views/UCIguQGdaBT1GnnVMz5qAZ2Q?style=social) 
