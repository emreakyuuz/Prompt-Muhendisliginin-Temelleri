# Prompt Mühendisliğinin Temelleri

## Giriş
Yapay zeka ve doğal dil işleme (NLP) alanlarında yaşanan hızlı gelişmeler, özellikle büyük dil modellerinin (LLM) kullanımıyla birlikte, yeni ve etkili bir etkileşim biçimi olan "prompt mühendisliği" kavramını hayatımıza sokmuştur. Bu metinde, ChatGPT gibi dil modelleriyle etkili etkileşim kurmanın temellerini ve püf noktalarını detaylı bir şekilde ele alacağız.

## Prompt Mühendisliği Nedir?
Prompt mühendisliği, yapay zeka modellerine verilen talimatların ve soruların nasıl formüle edileceğini belirleyen bir disiplindir. Amaç, modelden istenilen yanıtları en doğru ve verimli şekilde elde etmektir. İyi bir prompt, modelin anlamasını ve doğru şekilde yanıt vermesini kolaylaştırır.

## Bölüm 1: Temel Kavramlar

### 1.1 Prompt Tanımı
Merhaba! Öncelikle, "prompt" nedir, bunu anlamakla başlayalım. Prompt, yapay zeka modeline verdiğiniz bir talimat veya sorudur. Bu talimat, modelin ne yapması gerektiğini belirler.
Diyelim ki ChatGPT ile konuşuyorsunuz ve ona bir hikaye anlatmasını istiyorsunuz. "Bana bir hikaye anlat" dediğinizde, işte bu bir prompt oluyor. Bu, modelin size bir hikaye anlatmasını istediğinizi belirten bir talimat.

### 1.2 Promptun Önemi
Peki, neden prompt bu kadar önemli? Çünkü modelin verdiği yanıt, sizin promptunuzun kalitesine bağlı. İyi bir prompt, modelin sizin ne istediğinizi daha iyi anlamasını sağlar.
Düşünün, bir arkadaşınıza "bir şeyler yap" demek yerine "bana bir kahve yap" dediğinizde, arkadaşınız tam olarak ne yapması gerektiğini bilir. Aynı şekilde, ChatGPT'ye de ne yapması gerektiğini açıkça söylediğinizde, model daha doğru ve faydalı yanıtlar verecektir.

### 1.3 Promptun Temel Bileşenleri
İyi bir promptun bazı temel bileşenleri vardır. Gelin bunları inceleyelim:
- **Açıklık ve Kesinlik**: Açıklık ve kesinlik, iyi bir promptun bel kemiğidir. Belirsiz veya çok genel bir talimat verdiğinizde, model de aynı şekilde belirsiz veya genel yanıtlar verebilir.
- **Bağlam Sağlama**: Bağlam, modelin doğru yanıtlar vermesi için çok önemlidir. Bağlam sağlamadan bir soru sorduğunuzda, modelin ne hakkında konuştuğunuzu anlaması zor olabilir.
- **Sorunun Amacını Belirtme**: Promptunuzun amacını açıkça belirtmek, modelin doğru şekilde yanıt vermesine yardımcı olur. Ne tür bir bilgi istediğinizi veya modelin nasıl bir yanıt vermesini beklediğinizi netleştirmek önemlidir.

## Bölüm 2: Etkili Promptlar Oluşturma
Merhaba arkadaşlar! Bir önceki bölümde promptun ne olduğunu ve neden önemli olduğunu öğrendik. Şimdi ise etkili promptlar oluşturmanın yollarını öğreneceğiz. Hep birlikte daha iyi nasıl promptlar yazabileceğimizi keşfetmek üzere yola çıkalım.

### 2.1 Açıklık ve Kesinlik
İlk adımımız açıklık ve kesinlik. Şimdi, arkadaşınıza bir şey yapmasını isterken nasıl net oluyorsunuz, değil mi? Aynı şekilde ChatGPT ile de net olmalısınız. Belirsiz talimatlar verirseniz, model de belirsiz yanıtlar verebilir.

**Örnekler:**
- Belirsiz: "Bana bir hikaye anlat." 
  - Açık ve Kesin: "Bana üç paragraf uzunluğunda, bir çocuk ve köpeği hakkında mutlu sonla biten bir hikaye anlat."
- Belirsiz: "Bana biraz bilgi ver." 
  - Açık ve Kesin: "Bana Mars gezegeni hakkında beş ilginç bilgi ver."

### 2.2 Bağlam Sağlama
İkinci adımımız bağlam sağlama. Modelin doğru yanıt verebilmesi için ona yeterli bilgi vermeniz gerekiyor. Tıpkı bir arkadaşınıza bir olaydan bahsederken detaylar verdiğiniz gibi.

**Örnekler:**
- Bağlamsız: "Bu nedir?" 
  - Bağlamlı: "Mars'taki en yüksek dağ nedir?"
- Bağlamsız: "Neden?" 
  - Bağlamlı: "Fransız İhtilali'nin ana nedenleri nelerdir?"

### 2.3 Sorunun Amacını Belirtme
Üçüncü adımımız sorunun amacını belirtmek. Modelden ne istediğinizi tam olarak anlatmanız gerekiyor. Ne tür bir bilgi veya yanıt beklediğinizi açıkça ifade edin.

**Örnekler:**
- Belirsiz: "Bana yemek tarifleri ver." 
  - Amaç Belirtilmiş: "Bana vejetaryen yemek tarifleri ver."
- Belirsiz: "Bana yardımcı ol." 
  - Amaç Belirtilmiş: "Bana bu projeyi nasıl planlayabileceğim konusunda yardımcı ol."

### 2.4 İyi Prompt Yazmanın Adımları
Şimdi, öğrendiklerimizi kullanarak iyi promptlar yazmanın adımlarını detaylandıralım ve örneklerle zenginleştirelim.

#### 1. ChatGPT'ye Rol Verin
Modelin belirli bir perspektiften yanıt vermesini sağlayarak daha spesifik ve ilgi çekici yanıtlar alabilirsiniz. İşte bazı örnekler:
- "Sen bir gazetecisin, bana son dakika haberini yaz."
- "Sen bir tarih öğretmenisin, bana Rönesans dönemi hakkında bilgi ver."
- "Sen bir yemek şefisin, bana özgün bir yemek tarifi öner."
- "Sen bir doktorusun, bana grip belirtilerini açıkla."
- "Sen bir çocuk kitabı yazarıydın, bana bir çocuk hikayesi yaz."
- "Sen bir teknoloji analistisin, son teknoloji trendlerini değerlendir."
- "Sen bir film eleştirmenisin, bana son izlediğin filmi değerlendir."
- "Sen bir spor yorumcususun, dünkü maçın özetini ver."
- "Sen bir seyahat blog yazarıydın, bana Paris’te gezilecek yerleri anlat."
- "Sen bir finans danışmanısın, bana yatırım tavsiyeleri ver."

#### 2. Hedefi Tanımlayın
Promptunuzun neyi başarmasını istediğinizi açıkça belirtin:
- "Bir makale yaz."
- "Bir şiir yaz."
- "Bir hikaye anlat."
- "Bir ürün incelemesi yap."
- "Bir yemek tarifi yaz."
- "Bir teknik doküman hazırla."
- "Bir blog yazısı yaz."
- "Bir konuşma hazırla."
- "Bir e-posta yaz."
- "Bir rapor oluştur."

#### 3. Kısıtlamaları Belirleyin
Promptunuzu belirli kısıtlamalarla daha spesifik hale getirin:
- "Şiirsel bir dil kullan."
- "Teknik terimler kullanma."
- "Kısa ve öz yaz."
- "Halk dili kullan."
- "Resmi bir dil kullan."
- "Bilimsel bir ton kullan."
- "Eğlenceli bir tarzda yaz."
- "Diyalog şeklinde yaz."
- "Akademik bir üslup kullan."
- "Özetle."

#### 4. Sonucu Biçimlendirin
Sonucun nasıl olmasını istediğinizi belirtin:
- "Emoji ile cevapla."
- "Kodla cevapla."
- "Liste formatında yaz."
- "Tablo şeklinde sun."
- "Grafik ile açıkla."
- "Madde işaretleri kullan."
- "Paragraflar halinde yaz."
- "Görsel ekle."
- "Özetle."
- "Metin kutusu içinde göster."

## Bölüm 3: Gelişmiş Teknikler
Merhaba arkadaşlar! Şimdiye kadar temel kavramları ve etkili promptlar oluşturmanın yollarını öğrendik. Şimdi, daha karmaşık ve gelişmiş tekniklerle nasıl daha verimli promptlar oluşturabileceğimizi inceleyeceğiz. Hazırsanız, başlayalım!

### 3.1 Zincirleme Talimatlar
Karmaşık görevler için, talimatlar zinciri oluşturmak etkili bir yöntemdir. Bu, modelin adım adım talimatları takip etmesine ve daha karmaşık sonuçlar üretmesine olanak tanır.

**Örnekler:**
1. Karakter Yaratma ve Hikaye Yazma:
    - "Önce bir karakter yarat ve bu karakterin özelliklerini listele. Sonra bu karakterin bir gününü anlat."
    - Yanıt:
        - Karakter: 10 yaşında, kahverengi saçlı, meraklı bir çocuk.
        - Günlük hayatı: Okula gider, arkadaşlarıyla oynar ve akşam ailecek film izlerler.
2. Bilimsel Araştırma Hazırlama:
    - "Önce bir hipotez belirle, ardından bu hipotezi test etmek için deney tasarla ve sonuçları değerlendir."
    - Yanıt:
        - Hipotez: Bitkiler müzik dinlediğinde daha hızlı büyür.
        - Deney: İki grup bitki, biri müzikle diğeri sessiz ortamda yetiştirilir.
        - Sonuç: Müzikle büyüyen bitkiler %20 daha hızlı büyümüştür.
3. Ürün İncelemesi Yazma:
    - "Önce ürünün teknik özelliklerini listele, ardından kullanıcı deneyimlerine dayanarak bir inceleme yaz."
    - Yanıt:
        - Teknik Özellikler: 6.5 inç ekran, 128GB depolama, 48MP kamera.
        - İnceleme: Ekran kalitesi harika, depolama yeterli, kamera performansı gece çekimlerinde de çok iyi.

### 3.2 Örnekler Verme
Modelin istenilen formatta yanıt vermesi için, prompt içerisinde örnekler vermek faydalıdır.

**Örnekler:**
1. Makale Yazma:
    - "Aşağıdaki formatta bir makale yaz: [Başlık]: [İçerik]"
    - Örnek:
        - Başlık: "Yapay Zeka ve Geleceği"
        - İçerik: "Yapay zeka, son yıllarda hızla gelişen bir teknoloji..."
2. Diyalog Yazma:
    - "Aşağıdaki formatta bir diyalog yaz: [Kişi A]: [Konuşma] [Kişi B]: [Konuşma]"
    - Örnek:
        - Kişi A: "Merhaba, bugün nasılsın?"
        - Kişi B: "Merhaba! İyiyim, teşekkürler. Sen nasılsın?"
3. Reçete Yazma:
    - "Aşağıdaki formatta bir reçete yaz: [İlaç Adı]: [Dozaj] [Kullanım Talimatı]"
    - Örnek:
        - İlaç Adı: "Paracetamol"
        - Dozaj: "500 mg"
        - Kullanım Talimatı: "Günde 3 kez, yemeklerden sonra alın."

### 3.3 Negatif Örnekler
Modelin ne yapmaması gerektiğini belirtmek de önemlidir. Bu, istenmeyen sonuçlardan kaçınmanızı sağlar.

**Örnekler:**
1. Kısaltmalar Kullanma:
    - "Yanıtında kısaltmalar kullanma."
    - Yanıt: "Merhaba, bugün hava çok güzel."
2. Resmi Dil Kullanma:
    - "Resmi bir dil kullanma, daha samimi bir üslup kullan."
    - Yanıt: "Selam, nasılsın? Bugün harika bir gün değil mi?"
3. Teknik Terimler Kullanma:
    - "Teknik terimler kullanma, daha basit bir dil kullan."
    - Yanıt: "Bilgisayarlar, karmaşık hesaplamaları hızlıca yapabilir."

### 3.4 Sonucu Biçimlendirin
Sonucun nasıl olmasını istediğinizi belirterek, modelin yanıtlarını daha kullanışlı hale getirebilirsiniz.

**Örnekler:**
1. Emoji ile Cevapla:
    - "Yanıtında emoji kullan."
    - Yanıt: "Bugün hava çok güzel! ☀️"
2. Kodla Cevapla:
    - "Yanıtında Python kodu kullan."
    - Yanıt:
        ```python
        def merhaba_dunya():
            print("Merhaba Dünya!")
        ```
3. Liste Formatında Yaz:
    - "Yanıtında liste formatı kullan."
    - Yanıt:
        - Görev 1: Araştırma yap.
        - Görev 2: Rapor yaz.
        - Görev 3: Sunum hazırla.
4. Tablo Şeklinde Sun:
    - "Yanıtını tablo şeklinde sun."
    - Yanıt:
        | Görev        | Durum     |
        |--------------|-----------|
        | Araştırma    | Tamam     |
        | Rapor Yazma  | Devam     |
        | Sunum        | Başladı   |
5. Grafik ile Açıkla:
    - "Yanıtını grafik ile açıkla."
    - Yanıt: (Burada bir grafik çizerdi)
6. Madde İşaretleri Kullan:
    - "Yanıtında madde işaretleri kullan."
    - Yanıt:
        - İlk adım: Araştırma yap.
        - İkinci adım: Verileri analiz et.
        - Üçüncü adım: Sonuçları yaz.
7. Paragraflar Halinde Yaz:
    - "Yanıtını paragraflar halinde yaz."
    - Yanıt: "Yapay zeka, modern dünyada hızla gelişen bir alandır. Birçok sektörde devrim niteliğinde yenilikler yapmaktadır. Örneğin, sağlık alanında..."
8. Görsel Ekle:
    - "Yanıtında görsel kullan."
    - Yanıt: (Burada bir görsel eklenirdi)
9. Özetle:
    - "Yanıtını özetle."
    - Yanıt: "Yapay zeka, birçok alanda yenilikler yapıyor. Özellikle sağlık ve teknoloji sektörlerinde büyük gelişmeler sağlıyor."
10. Metin Kutusu İçinde Göster:
    - "Yanıtını metin kutusu içinde göster."
    - Yanıt:
        ```
        Yapay zeka, modern dünyada hızla gelişen bir alandır. Birçok sektörde devrim niteliğinde yenilikler yapmaktadır.
        ```

## Bölüm 4: Uygulama Örnekleri
Merhaba arkadaşlar! Şimdiye kadar iyi bir prompt yazmanın temel prensiplerini ve gelişmiş teknikleri öğrendik. Şimdi, bu bilgileri kullanarak çeşitli senaryolar için örnekler oluşturacağız. Bu örnekler, farklı sektörlerde ve durumlarda nasıl etkili promptlar oluşturabileceğimizi gösterecek.

### 4.1 Basit Sorular
Basit sorular, bilgi almak veya hızlı yanıtlar almak için kullanılan temel promplardır.

**Örnekler:**
1. Genel Bilgi:
    - Prompt: "Dünya'nın en yüksek dağı nedir?"
    - Yanıt: "Dünya'nın en yüksek dağı Everest Dağı'dır."
2. Tarih Bilgisi:
    - Prompt: "Rönesans ne zaman başladı?"
    - Yanıt: "Rönesans, 14. yüzyılın sonlarında İtalya'da başlamıştır."
3. Coğrafya:
    - Prompt: "Amazon Nehri hangi kıtada bulunur?"
    - Yanıt: "Amazon Nehri, Güney Amerika kıtasında bulunur."
4. Bilim:
    - Prompt: "Su molekülünün kimyasal formülü nedir?"
    - Yanıt: "Su molekülünün kimyasal formülü H2O'dur."
5. Sanat:
    - Prompt: "Vincent van Gogh'un ünlü tablosu 'Yıldızlı Gece' hangi yıl yapılmıştır?"
    - Yanıt: "'Yıldızlı Gece' 1889 yılında yapılmıştır."

### 4.2 Karmaşık Talimatlar
Karmaşık talimatlar, daha detaylı ve adım adım bilgi veya görevler gerektiren durumlar için kullanılır.

**Örnekler:**
1. Karakter Yaratma ve Hikaye Yazma:
    - Prompt: "Önce bir karakter yarat ve bu karakterin özelliklerini listele. Sonra bu karakterin bir gününü anlat."
    - Yanıt:
        - Karakter: 10 yaşında, kahverengi saçlı, meraklı bir çocuk.
        - Günlük hayatı: Okula gider, arkadaşlarıyla oynar ve akşam ailecek film izlerler.
2. Bilimsel Araştırma Hazırlama:
    - Prompt: "Önce bir hipotez belirle, ardından bu hipotezi test etmek için deney tasarla ve sonuçları değerlendir."
    - Yanıt:
        - Hipotez: Bitkiler müzik dinlediğinde daha hızlı büyür.
        - Deney: İki grup bitki, biri müzikle diğeri sessiz ortamda yetiştirilir.
        - Sonuç: Müzikle büyüyen bitkiler %20 daha hızlı büyümüştür.
3. Ürün İncelemesi Yazma:
    - Prompt: "Önce ürünün teknik özelliklerini listele, ardından kullanıcı deneyimlerine dayanarak bir inceleme yaz."
    - Yanıt:
        - Teknik Özellikler: 6.5 inç ekran, 128GB depolama, 48MP kamera.
        - İnceleme: Ekran kalitesi harika, depolama yeterli, kamera performansı gece çekimlerinde de çok iyi.

### 4.3 Zincirleme Talimatlar ve Örnekler
Zincirleme talimatlar, modelin adım adım ilerleyerek daha karmaşık görevleri yerine getirmesini sağlar. Örnekler vererek modelin istenilen formatta yanıt vermesini sağlayabilirsiniz.

**Örnekler:**
1. Makale Yazma:
    - Prompt: "Aşağıdaki formatta bir makale yaz: [Başlık]: [İçerik]"
    - Örnek:
        - Başlık: "Yapay Zeka ve Geleceği"
        - İçerik: "Yapay zeka, son yıllarda hızla gelişen bir teknoloji..."
2. Diyalog Yazma:
    - Prompt: "Aşağıdaki formatta bir diyalog yaz: [Kişi A]: [Konuşma] [Kişi B]: [Konuşma]"
    - Örnek:
        - Kişi A: "Merhaba, bugün nasılsın?"
        - Kişi B: "Merhaba! İyiyim, teşekkürler. Sen nasılsın?"
3. Reçete Yazma:
    - Prompt: "Aşağıdaki formatta bir reçete yaz: [İlaç Adı]: [Dozaj] [Kullanım Talimatı]"
    - Örnek:
        - İlaç Adı: "Paracetamol"
        - Dozaj: "500 mg"
        - Kullanım Talimatı: "Günde 3 kez, yemeklerden sonra alın."

### 4.4 Negatif Örnekler
Negatif örnekler, modelin ne yapmaması gerektiğini belirterek istenmeyen sonuçlardan kaçınmanızı sağlar.

**Örnekler:**
1. Kısaltmalar Kullanma:
    - Prompt: "Yanıtında kısaltmalar kullanma."
    - Yanıt: "Merhaba, bugün hava çok güzel."
2. Resmi Dil Kullanma:
    - Prompt: "Resmi bir dil kullanma, daha samimi bir üslup kullan."
    - Yanıt: "Selam, nasılsın? Bugün harika bir gün değil mi?"
3. Teknik Terimler Kullanma:
    - Prompt: "Teknik terimler kullanma, daha basit bir dil kullan."
    - Yanıt: "Bilgisayarlar, karmaşık hesaplamaları hızlıca yapabilir."

### 4.5 Sonucu Biçimlendirin
Sonucun nasıl olmasını istediğinizi belirterek, modelin yanıtlarını daha kullanışlı hale getirebilirsiniz.

**Örnekler:**
1. Emoji ile Cevapla:
    - Prompt: "Yanıtında emoji kullan."
    - Yanıt: "Bugün hava çok güzel! ☀️"
2. Kodla Cevapla:
    - Prompt: "Yanıtında Python kodu kullan."
    - Yanıt:
        ```python
        def merhaba_dunya():
            print("Merhaba Dünya!")
        ```
3. Liste Formatında Yaz:
    - Prompt: "Yanıtında liste formatı kullan."
    - Yanıt:
        - Görev 1: Araştırma yap.
        - Görev 2: Rapor yaz.
        - Görev 3: Sunum hazırla.
4. Tablo Şeklinde Sun:
    - Prompt: "Yanıtını tablo şeklinde sun."
    - Yanıt:
        | Görev        | Durum     |
        |--------------|-----------|
        | Araştırma    | Tamam     |
        | Rapor Yazma  | Devam     |
        | Sunum        | Başladı   |
5. Grafik ile Açıkla:
    - Prompt: "Yanıtını grafik ile açıkla."
    - Yanıt: (Burada bir grafik çizerdi)
6. Madde İşaretleri Kullan:
    - Prompt: "Yanıtında madde işaretleri kullan."
    - Yanıt:
        - İlk adım: Araştırma yap.
        - İkinci adım: Verileri analiz et.
        - Üçüncü adım: Sonuçları yaz.
7. Paragraflar Halinde Yaz:
    - Prompt: "Yanıtını paragraflar halinde yaz."
    - Yanıt: "Yapay zeka, modern dünyada hızla gelişen bir alandır. Birçok sektörde devrim niteliğinde yenilikler yapmaktadır. Örneğin, sağlık alanında..."
8. Görsel Ekle:
    - Prompt: "Yanıtında görsel kullan."
    - Yanıt: (Burada bir görsel eklenirdi)
9. Özetle:
    - Prompt: "Yanıtını özetle."
    - Yanıt: "Yapay zeka, birçok alanda yenilikler yapıyor. Özellikle sağlık ve teknoloji sektörlerinde büyük gelişmeler sağlıyor."
10. Metin Kutusu İçinde Göster:
    - Prompt: "Yanıtını metin kutusu içinde göster."
    - Yanıt:
        ```
        Yapay zeka, modern dünyada hızla gelişen bir alandır. Birçok sektörde devrim niteliğinde yenilikler yapmaktadır.
        ```

## Özet
Bu bölümde, öğrendiğimiz teknikleri çeşitli senaryolar için uygulayarak nasıl etkili promptlar oluşturabileceğimizi gördük. Basit sorular, karmaşık talimatlar, zincirleme talimatlar, negatif örnekler ve sonuç biçimlendirme gibi yöntemlerle, ChatGPT ile daha verimli ve amaca yönelik etkileşimler kurabilirsiniz. Şimdi, öğrendiğiniz bu teknikleri kendi projelerinizde kullanarak farkı görün!
