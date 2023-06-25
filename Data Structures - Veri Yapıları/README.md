# Veri Yapıları

### Bilgisayar Mimarisi

Bilgisayar Mimarisi, bilgisayar parçalarının
iç yapıları ve aralarındaki haberleşme
bağlantıları ile ilgilidir.

![img.png](img.png)

| Mimari                                                                                                                                                                                         |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Bilgisayar donanımı**, bir bilgisayarı oluşturan fiziksel parçaların genel adıdır.                                                                                                           |
| **Mikro kod**, mikroişlemcinin komut seti ile yazılmış olan yazılımlardır.                                                                                                                     |
| **Çevirme Dili** (Assembly Language) bilgisayar programlarını yazmak için kullanılan düşük seviyeli bir programlama dilidir.                                                                   |
| **Çekirdek**, işletim sisteminin kalbidir. Uygulamalar ve donanım seviyesindeki bilgi işlemleri arasında bir köprü görevi görür.                                                               |
| **İşletim sistemi** (Operating System), bilgisayarda çalışan, bilgisayar donanım kaynaklarını yöneten ve çeşitli uygulama yazılımları için yaygın servisleri sağlayan bir yazılımlar bütünüdür |

#### Önbellek

- Günümüz bilgisayarlarında, ön bellek kullanılarak bellekle
  tek yoldan iletişim ve buyrukla verinin aynı bellekte
  bulunma sorunu çözülmüştür.
- Ana bellek ile merkezi işlem birimi arasında görev yapan
  ve ana bellekten çok daha hızlı olan bir bellektir.
- Önbellek, işlem esnasında çok sık kullanılan
  bilgisayar talimatları ve geçici olarak tutulan bilgiler için bir
  “yaz-boz tahtası” olarak kullanılır.
- CPU ’nun ana bellekten veri alırken harcadığı zamanı
  azaltır; bu da bilgisayarı hızlandırır.

#### Mikroişlemci

- Bilgisayarın kalbidir. İşlemcinin görevi,
  buyrukların bellekten getirilmesi, çözülmesi ve
  çalıştırılması, sonuçların gözlenmesi, program
  işlenirken diğer donanım birimlerinden gelen
  kesme (interrupt) isteklerine cevap vermesi gibi
  işlemlerdir
- Günümüzde bu yapıya uygun iki bellek tipi
  vardır: ROM (Read Only Memory) ve RAM
  (Random Access Memory).
- ROM üzerindeki bilgiler
  kalıcıdır. Mikrokodların
  bulunduğu bellektir. Firma
  tarafından yüklenir.
- RAM üzerindeki bilgiler ise
  istenildiği zaman okunabilir ve
  yazılabilir. Elektrik
  kesintilerinde RAM üzerindeki
  tüm bilgiler silinir.
- RAM bellekler de SRAM
  (Statik RAM) ve DRAM
  (Dynamic RAM) olmak üzere
  2 çeşittir. SRAM çok pahalı ve
  hızlıdır, önbellek olarak
  kullanılırlar.

![img_1.png](img_1.png)

#### BIOS

- ROM Bellek (Read Only Memory, tr: Salt Okunur
  Bellek) içinde yer alan bir tür yazılımdır.
- Bilgisayar kapatılsada ROM içinde tutulur.
- Bilgisayar açıldığı anda işlemciye tüm diğer
  donanımları sırasıyla tanıtır.
- Donanımların temel iletişim protokollerini belirler.
- İşletim sisteminin başlangıç öğelerinin Herhangi bir
  sürücüden (HDD, CD-ROM vb.) yüklenmesini sağlar.
- İşletim sistemi çalışırken donanım ve işletim
  sistemi arasındaki ilişkileri düzenler.

#### Assebly dili

- Assembly dili, programlar yazmak için kullanılan
  düşük seviyeli bir programlama dilidir.
- Bir assembly dil programı, çevirici “Assembler” olarak
  adlandırılan faydalı bir program tarafından hedef
  bilgisayarın makine koduna çevrilir.
- Assembly insanlar tarafından anlaşılması zor olan
  makina dilinin sayısal ifadelerini, insanlar tarafından
  anlaşılarak programlanması daha kolay olan alfabetik
  ifadelerle değiştirerek düşük seviyede programlama
  için bir ortam oluşturur.
- Assembly kullanmanın amacı, ilk bilgisayarlarda
  yazılan programların daha az hata içermesi ve daha az
  zaman almasını sağlamaktır.

![img_2.png](img_2.png)

#### Çekirdek (Kernel)

- İşletim sistemi çekirdeği, kısaca çekirdek
  (kernel), işletim sisteminin kalbidir
- Uygulamalar ve donanım
  seviyesindeki bilgi işlemleri arasında bir
  köprü görevi görür.
- Çekirdeğin görevleri sistemin
  kaynaklarını yönetmeyi de
  kapsamaktadır.
- İşletim sistemi görevleri,
  tasarımları ve uygulanmalarına
  göre farklı çekirdekler tarafından farklı
  şekillerde yapılır.
- Sistem açılırken belleğe yüklenir
  ve sistem kapatılıncaya kadar bellekte
  kalır.
- Linux çekirdeği açık kaynak kodlu olduğu
  için üzerine yeni işletim sistemleri
  geliştirilebilir. (Pardus)

![img_3.png](img_3.png)

#### İşletim Sistemleri

- İşletim sistemi, bilgisayarda çalışan, bilgisayar donanım
  kaynaklarını yöneten ve çeşitli uygulama yazılımları için
  yaygın servisleri sağlayan bir yazılımlar bütünüdür.
- İşletim sistemleri sadece bilgisayar, video oyun konsolları,
  cep telefonları ve web sunucularında değil; arabalarda,
  beyaz eşyalarda hatta kol saatlerinin içinde bile yüklü
  olabilir.
- İşletim sistemleri işlevsellerinin genişliği ile değil,
  donanımı belli bir amaç doğrultusunda
  programlayabilme nitelikleriyle değerlendirilmelidir.

#### Veri

- Veri, algoritmalar tarafından işlenen en temel
  elemanlardır(sayısal bilgiler, resim, metinsel bilgiler, sesler
  ve girdi çıktı bilgileri vb. ) Bir algoritmanın etkin, anlaşılır
  ve doğru olabilmesi için, algoritmanın işleyeceği verilerin
  düzenlenmesi gerekir.

#### Veri Yapıları

###### Veri Yapısı

- Verinin veya bilginin bellekte tutulma şeklini veya düzenini gösterir.
- Tüm programlama dillerinin genel olarak, tam sayı, kesirli sayı, karakter ve sözcük
  saklanması için temel veri yapıları vardır
- Programcı bu veri yapılarını, bunların bellekte nasıl saklandığı konusuyla
  ilgilenmeksizin bolca kullanır
- Tasarlanacak program, temel veri yapısı dışında farklı veri yapısına ihtiyaç
  duyuyorsa, bunlar kullanılan programlama dilinin elverdiği ölçüde
  tanımlanmalıdır. Örneğin; struct (topluluk) ve union (ortaklık).

###### Veri Modeli

- Verilerin birbirleriyle ilişkisel veya sırasal durumunu gösterir;
  problemin çözümü için kavramsal bir yaklaşım yöntemidir denilebilir.
- Bilgisayar ortamında uygulanacak tüm matematik ve mühendislik problemleri
  bir veri modeline yaklaştırılarak veya yeni veri modelleri tanımlaması yapılarak
  çözülebilmektedir.
- Her program en azından bir veri modeline dayanır.
- Uygun veri modelinin seçilmesi ve kullanılması; uygulama için en etkin
  programın yazılmasını sağlar (Etkinlik: hız veya bellek gereksinimi olabilir).

#### Algoritma

- Bir problemin çözümünde kullanılan komutlar dizisi. Bir
  problemi çözmek için geliştirilmiş kesin bir yöntemdir.
  Bir algoritma, bir programlama dilinde (Java, C, Python
  gibi) ifade edildiğinde **program** adını alır.

### Veri Yapılarına Neden İhtiyaç Vardır?

- Bilgisayar yazılımları gün geçtikçe daha karmaşık bir hal
  almaktadır.
- Yazılımların programlanması ve yönetimi zorlaşmaktadır.
- Örneğin 8 milyar sayfanın indekslenmesi (Google)
- Veri yapıları, daha etkin ve daha doğru program yazmayı sağlar.

İyi bir yazılım için gereksinimler:

- Temiz birtasarım
- Kolay bakım ve yönetim
- Güvenilir
- Kolay kullanımlı
- Hızlı algoritmalar

`Örnek:`
Her biri satır başına ortalama 10 kelimeden ve yine ortalama 20 satırdan oluşan 3000 metin koleksiyonu olduğunu
düşünelim.<br>
→600,000 kelime<br>
Bu metinler içinde “dünya” kelimesi ile eşleşecek bütün kelimeleri bulmak isteyelim<br>
Doğru eşleştirme için yapılacak karşılaştırmanın 1 sn. sürdüğünü varsayalım.<br>
`**Ne yapılmalıdır?**`

**Örnek** <br>

1. [ ] Çözüm.1:<br>
   `Sıralı eşleştirme:` 1 sn. x 600,000 kelime= **166 saat**<br>
2. [ ] Çözüm.2:<br>
   `İkili Arama (Binary searching):`<br>
   kelimeler sıralanır<br>
   sadece tek yarıda arama yapılır<br>
   toplam adım sayısı log 2 N= log 2 600000 yaklaşık 20 adım<br>
   (çevrim) **20 sn**.<br>
   **20 saniye veya 166 saat!**

### Veri Yapılarının Sınıflandırılması

- Veri Yapıları -> **Temel Veri Yapıları** ve **Tanınlamalı (Bileşik) Veri Yapıları**

| Temel Veri Yapıları                                                                                                           | Tanınlamalı (Bileşik) Veri Yapıları                                                                                                                                                       |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Temel veri yapıları**, daha çok programlama dilleri tarafından doğrudan değişken veya sabit bildirimi yapılarak kullanılır. | **Tanımlamalı veri yapıları**, kendisinden önceki tanımlamalı veya temel veri yapıları üzerine kurulurlar; yani, önceden geçerli olan veri yapıları kullanılarak sonradan tanımlanırlar.  |

#### Temel Veri Yapıları

- Tüm programlama dillerinin, genel olarak, karakter, tamsayı, kesirli
  sayı ve sözcük (karakter katarı) saklanması için temel veri yapıları
  vardır. Veri yapısı, aslında, ham olarak 1 ve 0’lardan oluşan verinin
  yorumlanmasını belirleyen biçimleme (formating) düzenidir.
  Örneğin, 62 sayısının ikili tabandaki karşılığı, 111110 olarak
  bellekte saklanır.
- Temel veri yapıları aşağıdaki gibi sınıflanabilir:
  ![img_4.png](img_4.png)

#### Tanımlamalı (Bileşik) Veri Yapıları

- Tanımlamalı veri yapısı, temel veya daha önceden tanımlanmış veri yapılarının
  kullanılıp yeni veri yapıları oluşturulmasıdır.
- Üç değişik şekilde yapılabilir:

| Tanımlamalı (Bileşik) Veri Yapıları | Açıklama                                                                                                                                                                                                      |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Topluluk (Struct) Oluşturma         | Birden çok veri yapısının bir araya getirilip yeni bir veri yapısı ortaya çıkarmaktır. (Java dilinde sınıflar)                                                                                                |
| Ortaklık (Union) Oluşturma          | Birden çok değişkenin aynı bellek alanını kullanmasını sağlayan veri yapısı tanımlamasıdır. Ortaklıkta en fazla yer işgal eden veri yapısı hangisi ise, ortaklık içerisindeki tüm değişkenler orayı paylaşır. |
| Bit Düzeyinde Erişim                | Verinin her bir bit’i üzerinde diğerlerinden bağımsız olarak işlem yapılması olanağı sunar                                                                                                                    |

Not :  Her birinin kullanım amacı farklı farklı olup uygulamaya göre bir tanesi veya
hepsi bir arada kullanılabilir. Genel olarak, en çok kullanılanı topluluk
oluşturmadır; böylece birden fazla veri yapısı bir araya getirilip/paketlenip yeni
bir veri yapısı/türü ortaya çıkarılır

- C dilinde tanımlamalı veri yapılarına örnek aşağıda
  verilmiştir:

  ![img_5.png](img_5.png)

### Veri Modelleri

- Veri modelleri, tasarımı yapılacak programın en uygun ve etkin şekilde
  olmasını sağlar ve daha baştan programın çalışma hızı ve bellek
  gereksinimi hakkında bilgi verir. Çoğu zaman, programın çalışma hızıyla
  bellek gereksinimi miktarı doğru orantılıdır denilebilir.
  Veri modelleri, genel olarak, aşağıdaki gibi verilebilir:

| Veri Modelleri               |
|------------------------------|
| Bağlantılı Liste (Link List) |
|Ağaç (Tree)|
|Graf (Graph)|
|Durum Makinesi (State Machine)|
|Veritabanı-İlişkisel (Database Relational)|
|Ağ Bağlantı (Network Connection)|


#### Liste ve Bağlantılı Liste Veri Modeli
- Liste veri modeli, aynı kümeye ait olan verilerin bellekte
  art arda tutulması ilkesine dayanır. Veriler belirli bir düzen
  içerisinde (sıralı vs.) olabilir veya olmayabilir; önemli olan tüm
  verilerin art arda gelen sırada tutulmasıdır.

  ![img_6.png](img_6.png)
-  **En yalın liste veri modeli** bir boyutlu dizi
   üzerinde tutulanıdır. Böylesi bir listeye eleman
   ekleme işlemi oldukça kolaydır; genel olarak,
   yeni gelen elemanlar listenin sonuna eklenir.
   Yalın listede bir sonraki eleman hemen o elemanın işgal ettiği bellek alanından sonradır

    ![img_7.png](img_7.png)
  - **Bağlantılı liste (link list)** ise, elemanların kendi
    değerlerine ek olarak bir de bağlantı bilgisinin
    kullanılmasıyla sağlanır; bağlantı bilgisi bir
    sonraki elemanın adresi niteliğindedir.

    ![img_8.png](img_8.png)

#### Ağaç Veri Modeli
- Ağaç veri modeli, **düğümlerden** ve **dallardan** oluşur.
- Düğümlerde verilerin kendileri veya bir kısmı tutulurken, dallar
diğer düğümlere olan bağlantı ilişkilerini gösterir. 
- Ağaç veri modeli, özellikle kümenin büyük olduğu ve arama işleminin çok
kullanıldığı uygulamalarda etkin bir çözüm sunar.
- En üstteki düğüm kök (root), kendisine alttan hiçbir bağlantının
olmadığı düğüm yaprak (leaf), diğerleri de ara düğüm (internal
node) olarak adlandırılır. Bir düğüme alttan bağlı düğümlere
çocuk (child), üsten bağlı düğüme de o düğümün ailesi
(parent) denilir.

  ![img_9.png](img_9.png)

  | Türkçe | İngilizce     | Açıklama                                                              |
  |---------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------|
  | Kök | Root          | En üstteki düğüm                                                      |
  | Yaprak | Leaf          | Kendisine alttan hiçbir bağlantının olmadığı düğüm (En alttaki düğüm) |
  | Ara düğüm | Internal Node | Aradaki, arada kalan düğümler                                         |
  | Çocuk | Child         | Bir düğüme alttan bağlı düğümlere denir                               |
  | Aile | Parent        | Bir düğüme üstten bağlı düğüme o düğümün ailesi denir                 |

- Veriniz üzerinde hızlı arama yapmak istiyorsunuz. Aşağıdaki gibi bir ağaç modeli
  kullanabilirsiniz.
  ![img_10.png](img_10.png)

#### Graf Veri Modeli
- Graf veri modeli, aynı kümeye ait olan verilerin şekilde görüldüğü gibi **düğümler**,
  **ayrıtlar (kenarlar)** ve **bunların birleştirilmesinden** oluşur. 
- **Düğümler** _birleşme noktasını_, **ayrıtlar** da _düğümlerin bağlantı ilişkisini_ gösterir. 
- Verilerin kendileri veya bir kısmı, hem düğümlerde hem de ayrıtların bilgi kısmında tutulabilir.
- Graflar, yazılım dünyasından önemli bir yere sahiptir. Örneğin, bir şehrin trafik altyapısından en
  yüksek akışın sağlanması, taşıma şirketinin en verimli taşıma şekli veya network bağlantılarında
  yüksek başarım elde edilmesi gibi problemler.

  ![img_11.png](img_11.png) ![img_12.png](img_12.png)

-  Şehirler arasındaki mesafeleri hesaplayan bir yazılım geliştirmeniz durumda ise
   graf modelini kullanabilirsiniz.

|                     |                                          |
|---------------------|------------------------------------------|
| Düğümler            | Birleşme noktasını gösterir.             |   
| Ayrıtlar (Kenarlar) | Düğümlerin bağlantı ilişkisini gösterir. |


  ![img_13.png](img_13.png)

#### Durum Makinası Veri Modeli
-  Durum makinası veri modeli, bir sistemin davranışını tanımlamak ve
   ortaya çıkarmak için kullanılan bir yaklaşım şeklidir.
-  İşletim sistemlerinde, derleyici ve yorumlayıcılarda, kontrol amaçlı yazılımlarda, sistemin
   davranışını durumlara indirger ve durumlar arası geçiş koşullarıyla sistemi
   ortaya koyar.
-   Durum makinası, yazılım uygulamasında birçok alanda kullanılabilir.
    Örneğin bir robot kolunun hareketi, şifre çözme, gerçek zamanlı işletim
    sistemlerinde proses kontrolü ve genel olarak kontrol alt sistemlerinin
    yazılımla uygulamayı başarılı bir şekilde sonuçlandırma durumlarında
    çözüm olur.
- Durum makinası veri modeli şeklen yönlü graflara benzer,
    ancak, birleşme noktaları graflarda olduğu gibi düğüm olarak
    değil de **durum**, ayrıtlar da **geçiş eğrileri** olarak adlandırılır.
- Durumlar arasındaki geçişler, sistemin o ana kadar ki
    durumlarına ve giriş parametrelerine bağlıdır.
  - Yönlü Graf ve Durum Makinesi isim karşılaştırması
  
    | Graf     | Durum Makinesi            |
      |----------|---------------------------|
      | Düğüm    | **Durum** olarak adlandırılır |
      | Ayrıtlar | **Geçiş Eğrileri** olarak adlandırılır |

  ![img_14.png](img_14.png)

#### Veritabanında İlişkisel Veri Modeli
- Veritabanı ilişkisel veri modeli veritabanı uygulamalarında var olan dört beş
  sınıftan birisidir.
- Veriler şekilde gösterildiği gibi tablolar üzerinden kurulan
  ilişkilere dayanmaktadır:

  ![img_15.png](img_15.png)

- SQL (Structured Query Language), sorgulama dili kullanılarak
  veritabanı üzerinde sorgulama yapılabilir. 
- Access, Microsoft SQL,
  ORACLE, SYBASE, Ingres gibi birçok veritabanı yönetim sistemleri
  ilişkisel veri modelini desteklemektedir.
- Veritabanı yönetim sistemleri, veritabanı oluşturma, tablo yaratma,
  alanları tanımlama gibi işlerin başarılı bir şekilde sonuçlandırmasını ve
  genel olarak veritabanı yönetimini sağlarlar.

#### Ağ Veri Modeli
- Ağ veri modeli, katmalı ağ mimarilerinde, bilgisayarlar arasında **eş katmanlar
(peer layers)** düzeyinde veri alış-verişini sağlayan **dilim (segment)**, **paket
(packet)** ve **çerçeve** yapılarını ortaya koyar ve iletişim için gerekli davranışı
tanımlar.
- Veri haberleşmesinde hemen hemen tüm mimariler katmanlı yapıdadır.
- Tüm mimariler örnek temsil eden OSI 1, başvuru modeli 7, TCP/IP
(Transmission Control Protocol / Internet Protocol) protokol kümesi 4
katmanlıdır.

  ![img_16.png](img_16.png)


### Veri Modelleri
- Aşağıdaki veri modelleri detaylı anlatılacaktır:

| Veri Modeli              | Açıklama                                                                                                                                  |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Liste                    | Sonlu sayıda elemandan oluşan ve elemanları **doğrusal sırada** yerleştirilmiş veri modeli. Herhangi bir elemanına erişimde sınırlama yoktur. |
| Yığıt veya yığın **LIFO**    | Elemanlarına erişim sınırlaması olan, liste uyarlı veri modeli (Last In First Out-**LIFO listesi**)                                       |
| Kuyruk              **FIFO** | Elemanlarına erişim sınırlaması olan, liste uyarlı veri modeli. (First In First Out-**FIFO listesi**).                                    |
| Ağaç                     | **Doğrusal olmayan** belirli niteliklere sahip veri modeli                                                                                    |
| Çizge (Graph)            | Köşe adı verilen düğümleri ve kenar adı verilen köşeleri birbirine bağlayan bağlantılardan oluşan **doğrusal olmayan** veri modeli            |

![img_17.png](img_17.png)

### Veri, Yapı ve Algoritma Arası İlişki
-  Bir programda veri, yapı ve algoritma birbirinden ayrılmaz
   bileşenlerdir ve herbiri önemlidir. 
- Verilerin düzenlenme
   biçimleri önemlidir. Çünkü, yapı iyi tasarlandığında, etkin,
   doğru, anlaşılır ve hızlı çalışıp az kaynak kullanan algoritma
   geliştirmek kolaylaşır.

|                      |                                        |
|----------------------|----------------------------------------|
| **Veri Tipleri**         | Tamsayı, Gerçel Sayı, Karakter ...     |
| **Bileşik Veri Tipleri** | Dizi, Yapı (kayıt), ...                |
| **Veri Yapıları**        | Liste, Yığıt, Kuyruk, Ağaç, Çizge, ... |

- Programlamada veri yapıları en önemli unsurlardan
birisidir. Program kodlarını yazarken kullanılacak veri
yapısının en ideal şekilde belirlenmesi, belleğin ve çalışma
biçiminin daha etkin kullanılmasını sağlar.
- Program içerisinde işlenecek veriler, diziler ile
tanımlanmış bir veri bloğu içerisinden seçilebileceği gibi,
işaretçiler kullanılarak daha etkin şekilde hafızada
saklanabilir.
- Veri yapıları, dizi ve işaretciler ile yapılmasının yanında,
nesneler ile de gercekleştirilebilir.

### Algoritma
- Algoritma, bir problemin çözümünde izlenecek yol
  anlamına gelir.
- Algoritma, belirli bir problemin sonucunu elde etmek
  için art arda uygulanacak adımları ve koşulları kesin
  olarak ortaya koyar. 
- Herhangi bir giriş verisine karşılık,
  çıkış verisi elde edilmesi gereklidir. Bunun dışındaki
  durumlar algoritma değildir.

  ![img_18.png](img_18.png)

- Program tasarlanırken, kullanılacak veri yapısı ve algoritma
doğrudan uygulamaya bağlıdır.
- Bazı uygulamalar için programlama dilinin halihazırda sahip
olduğu veri modelleri yeterliyken, bazı uygulamalar için
programcı, var olan veri modellerini de kullanarak yeni yeni
veri modelleri tanımlar ve programın algoritmik ifadesini
bunlara dayanarak geliştirir.
- Örneğin dizi uygulaması gerektiren bir program tasarımında,
dizi yapısını tanımlamaya gerek yoktur. Çünkü C
programlama dilinde dizi tanımlaması doğrudan değişken
bildirimi yapılırken gerçekleştirilebilir. Ancak, bir ağaç
modeline ihtiyaç olsaydı, ağaç yapısının kurulması için yeni bir
veri yapısına gerek duyulur.

- Bilgisayar uygulamasında, bir yazılım geliştirirken birçok
algoritmaya ihtiyaç duyulur. Örneğin,
  - arama algoritması
  - sıralama algoritması
  - matris veya vektörel işlem algoritması
  - graf algoritması
  - bir matematiksel modelin çözülmesi algoritması
gibi birçok algoritma türü vardır ve uygulama
geliştirirken, bunların biri veya birkaçı her zaman kullanılır.


### Programın Çalışma Hızı ve Büyük O - BIG O
- Programın çalışma hızı karmaşıklık ifadesiyle gösterilir; bu
kavram zaman birimiyle ifade edilmeyip doğrudan işlem adedi
veya döngü sayısıyla ifade edilir.
- Çünkü, programın çalışma hızında zaman miktarı programın
üzerinde koştuğu donanıma çok bağlıdır; dolayısıyla
algoritmaları birbirleriyle karşılaştırmak için zaman miktarını
kullanmak gerçekçi olmayıp yanılgılara neden olmaktadır.
- İlgili algoritmanın bilgisayar donanımından bağımsız olarak
kaç adet işlem veya döngüyle gerçekleştirilebileceği hesaplanır.
- Bu konu daha sonra detaylı işlenecektir.

### Programlama Dilleri
- Programlama dilleri, bilgisayar donanımı fazla bilinmeden
program geliştirmeye imkan veren bir kodlama şeklidir.
- Makine koduyla program geliştirmek oldukça zor ve zahmetli
olduğundan assembly dili ve üst düzey programlama dilleri
geliştirilmiştir.
- Herbiri farklı bir alana yönelmiş veya genel amaçlı olarak
tasarlanmış BASIC, FORTRAN, PASCAL, C, PYHTON vs.
dibi adlandırılan birçok programlama dili vardır.
- C, orta düzel programlama dilidir. Alt düzey ve üst düzey
programlama dillerinin yeteneklerinin bir araya getirilmesini
sağlamıştır.
- Üst düzey ve orta düzey programlama dilleriyle tasarlanan bir
programın makine kodunu üretmek için derleyici olarak
adlandırılan yazılımlar kullanılır.

### Aritmetik Yaklaşımda C Dili Esnekliği ve Özellikleri
- C programlama dili, sahip olduğu özellikler, algoritma tasarımında
sunduğu esneklik ve UNIX/LINUX gibi işletim sistemlerin temel
dili olması nedeniyle program tasarımında, algoritma geliştirmede
ve sistem konfigürasyonunda yoğun olarak kullanılmaktadır.
-Veri modeli oluşturulan her türlü problemin çözümü C diline
dayanılarak tasarlanabilir ve kodlanabilir.
- C dili, üst düzey programlama dilleriyle alt düzey programlama
dilleri arasında, her ikisinin de özelliklerini taşıyan orta düzeyli bir
programlama dilidir.
- Her iki gruba ait dillerin esnek yanlarını ve kolaylıklarını içerdiği için
de hemen hemen her alanda program geliştirme için
kullanılmaktadır.
- Dolayısıyla C diline dayanılarak veri yapısı tanımlaması ve veri
modellerinin kodlanması önem kazanmıştır.

### C Programlama Dili
- C dilinin en önemli esnekliği, sanki bir alt düzey programlama
dili gibi doğrudan bellek adresleriyle çok esnek şekillerde
çalışabilmektedirler.
- Bir değişken, bir fonksiyon veya komut anlamında bir
program, eğer adresleri biliniyorsa her durumda
çalıştırılabilmekte ve oldukça esnek bir tasarım şekli
sunmaktadır.
- Bunun yanı sıra, yeni veri yapıları tanımlayabilme, bit
düzeyinde çalışabilme, disk dosyalarına erişim esnekliği,
işletim sistemi çağrılarını doğal haliyle kullanma gibi birçok
özellik, C dilini, temel bir dil yapmıştır.
- kontrol deyimleri gibi birçok özellik C programlama dilini öne
çıkarmaktadır.
- C dili, bir üst düzey programlama dili gibi de özelliklere
sahiptir.
- Birçok fonksiyon hazır olarak kütüphanelerde
bulunmaktadır.
- Bellek alanlarının statik ve dinamik kullanım şekli, yerel
değişken kavramı, değişkenlerin bellekte veya
mikroişlemci saklayıcılarında tutulması, bellek
adreslerinin tutulduğu işaretçi değişkenler, fonksiyonlara
veri aktarımı ve sonuç gönderilmesi, fonksiyonların
çağrılma şekilleri, esnek yapıdaki döngü ve kontrol
deyimleri gibi birçok özellik C programlama dilini öne
çıkarmaktadır.

### C Dilinde Bilinmesi Gerekenler
- Diziler ve bellek düzeni
- İşaretçiler; işaretçi ve diziler arasındaki ilişki
- Dinamik bellek kullanımı
- Yapısal veri tasarımı; struct ve union deyimleri
- Fonksiyon çağırma yöntemleri, fonksiyona parametre
aktarımı
- Rekürsif fonksiyonların çalışma şekli
- Disk ve saklama birimlerine erişim




---
Kaynak : `rkorkmaz@nku.edu.tr` Veri Yapıları Dersi - Bilgisayar Mühendisliği