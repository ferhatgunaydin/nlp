# Finansal Sektörde Doğal Dil İşleme (NLP) Kullanımı

Ferhat Günaydın
1030510403
Erciyes Üniversitesi Bilgisayar Mühendisliği Bölümü
## Giriş

Doğal dil işleme (Natural Language Processing / NLP), bilgisayarların insan dilini anlamalarını ve işlemelerini sağlayan çeşitli tekniklerin toplamını ifade etmektedir (Eisenstein, 2019, s. 1). Son on yılda, bu alan günlük yaşantımızın ayrılmaz bir parçası haline gelmiştir. Örneğin, otomatik makine çevirisi internet üzerinde ve sosyal medyada yaygın olarak kullanılmaktadır. Metin sınıflandırma, e-posta hesaplarını spam dolusu mesajlardan korumanın önemli bir rolünü oynamaktadır. Arama motorları basit dize eşleştirmesinden daha gelişmiş dil analizine geçerek etkinliğini artırmıştır. Ayrıca, diyalog sistemleri bilgi edinmenin ve paylaşmanın giderek daha yaygın ve etkili bir yolu olarak popülerlik kazanmıştır.

NLP, biçimsel dilbilimden istatistiksel fizikse kadar birçok farklı zihinsel geleneğe dayanmaktadır (Eisenstein, 2019, s. 1). İşletmeler ve finansal kuruluşlar, bugünün dijital çağında finansal yeteneklerini artırmak için NLP üzerinde önemli çalışmalar yapmaktadır. Finans, metin verileri gibi metinler, analist raporları, finansal basılı medya, web siteleri, forumlar vb. gibi verilere önemli ölçüde dayandığı için NLP'ye büyük oranda bağımlı sektörlerden biridir.

NLP teknikleri, yapılandırılmamış metin bilgilerini anlamlı analizlere dönüştürmek için kullanılmaktadır. Son yıllarda NLP algoritmaları çok daha güvenilir ve ölçeklenebilir hale geldiğinden finans sektörü çalışanlarına da oldukça kolaylık sağlamaktadır.

Finans sektöründe, NLP'nin; risk değerlendirmeleri, güvenilirlik analizi, müşteri sohbet botları, portföy seçimi, varlık tanıma, duygu analizi, konuşma tanıma gibi geniş bir uygulama yelpazesi bulunmaktadır. Bu uygulamaları aşağıda detaylarıyla ele almaktayız:

## 1- Duygu Analizi
Hisse senedi piyasasında başarılı işlem yapmak, belirli hisseler hakkındaki bilgiye dayanmaktadır. Bu bilgiye dayalı olarak, yatırımcılar bir hisseyi almak, elde tutmak veya satmak konusunda karar verebilmektedirler. Üç aylık finansal tabloları analiz etmenin ötesinde, bu şirketler hakkında analistlerin neler söylediğini bilmek de önemlidir ve bu bilgi sosyal medyada bulunabilmektedir.

Sosyal medya analizi, sosyal medya gönderileri içinde bu tür bilgileri izlemeyi ve ticaret için potansiyel fırsatları seçmeyi içerir. Örneğin, bir CEO'nun istifası haberi genellikle olumsuz bir duyguyu ifade eder ve hisse fiyatını olumsuz etkileme potansiyeline sahiptir. Ancak CEO iyi performans göstermiyorsa, hisse piyasası istifa haberini olumlu bir şekilde karşılar ve bu defa hisse fiyatını potansiyel olarak artırabilecektir.

DataMinr[[1]](#_ftn1) ve Bloomberg gibi bazı şirketler, bu tür bilgileri yatırımcılara yardımcı olmak için sunmaktadır. Örneğin, DataMinr, kullanıcılarına pazarı potansiyel olarak etkileyebilecek Dell ile ilgili hisse senedi özel uyarılar ve haberler sunmuştur.

Finansal duygu analizi, rutin duygu analizinden farklıdır. Hem alan hem de amacı bakımından farklıdır. Normal duygu analizinde amaç, bilginin temelde olumlu olup olmadığını bulmaktır (Kochmar, 2022, s. 238). Ancak NLP tabanlı finansal duygu analizinde amaç, piyasanın habere nasıl tepki vereceğini ve hisse senedi fiyatının düşüp düşmeyeceğini görmektir.

BERT (Bidirectional Encoder Representations from Transformers), Google araştırmacıları tarafından 2018 yılında tanıtılan bir sinir ağı mimarisidir. Başka bir ifadeyle, Google'ın NLP için kullandığı sinir ağı temelli bir ön eğitim tekniğidir. BERT, dilin inceliklerini insanlar gibi anlamaya yardımcı olmayı amaçlamaktadır. Bu algoritma, potansiyel olarak Google'ın kullanıcılara daha ilgili ve değerli sonuçlar sunma yeteneğini artırmaktadır. Önceden, Google genellikle kullanıcıların sorgularındaki anahtar kelimelere odaklanmaktaydı. BERT ile Google, sorgudaki her kelimeyi ayrı ayrı değil, aynı zamanda tüm dilsel bağlama ve kullanıcının sorgusundaki kelimeler arasındaki içsel dilsel tutarlılığa odaklanarak anlamaya çalışmaktadır.

BioBERT[[2]](#_ftn2), biyomedikal metin madenciliği için önceden eğitilmiş bir biyomedikal dil temsil modeli olarak oldukça kullanışlı olmuştur ve şimdi araştırmacılar BERT'i finansal alan için uyarlamak üzerinde çalışmaktadır. FinBERT[[3]](#_ftn3), finans hizmetleri sektörü için geliştirilen modellerden biridir. FinBERT, Reuters'ten finansal haberler içeren bir veri kümesi üzerinde çalışmaktadır. Duygu atamalarını gerçekleştirmek için ifade bankası oluşturulmuştur. Bu ifade bankası, işletme veya finans geçmişi olan farklı insanlar tarafından etiketlenen yaklaşık 4.000 cümleden oluşmaktadır. FinBERT, diğer mevcut araçlara göre önemli ölçüde geliştirilmiş bir doğruluk ve F1 skoru ile oldukça başarılı olmuştur. FinBERT kütüphanesi GitHub'ta[[4]](#_ftn4) ilgili verilerle açıktır. Ekonomik duygu sınıflandırması için güçlü bir dil modeli olan bu model, farklı amaçlar için kullanılabilmektedir.

----------

[[1] https://www.dataminr.com/](https://www.dataminr.com/)

[[2] https://academic.oup.com/bioinformatics/article/36/4/1234/5566506?login=false](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506?login=false)

[[3] https://arxiv.org/abs/1908.10063](https://arxiv.org/abs/1908.10063)

[[4] https://github.com/ProsusAI/finBERT](https://github.com/ProsusAI/finBERT)
## 2- Risk Değerlendirmesi

Bankalar, kredi riski değerlendirmesi temelinde başarılı bir kredi ödeme olasılığını incelemektedir. Kredi ödeme olasılığı, genellikle; ödeme kapasitesi, önceki harcama alışkanlıkları ve önceki kredi ödeme geçmişi verilerine dayalı olarak hesaplanmaktadır. Ancak bazı durumlarda bu bilgilere erişimi bulunmamaktadır ya da yetersizdir. Özellikle daha düşük gelirli kesimlerde bu durum geçerlidir. Tahminlere göre, dünya nüfusunun neredeyse yarısı, yoksulluk nedeniyle finansal hizmetleri kullanmamaktadır.

Bu sorunu çözmek için NLP devreye girebilmektedir. NLP teknikleri, kredi riskini değerlendirmek için birden fazla veri noktasını kullanmaktadır. Örneğin, NLP işletme kredilerinde tutumu ve girişimci zihniyetini ölçebilmektedir. Benzer şekilde, tutarsız verileri tespit edebilmekte ve daha fazla inceleme için bu verileri ele alabilmektedir. Ayrıca, kredi sürecinde kredi veren ve kredi alanın duygusal durumları gibi ince ayrıntılar da NLP'nin yardımıyla sürece dahil edilebilmektedir.

Genellikle şirketler, kişisel kredi belgelerinden çok sayıda bilgi yakalamakta ve bunları daha fazla analiz için kredi riski modellerine iletmektedir. Toplanan bilgiler, kredi riskini değerlendirmeye yardımcı olsa da, veri çıkarma hataları yanlış değerlendirmelere yol açabilmektedir. Varlık İsmi Tanıma (Named Entity Recognition / NER), böyle durumlarda faydalı olan bir NLP tekniğidir. NER, kredi anlaşmasından tarih, konum ve ilgili tarafların ayrıntıları dahil olmak üzere ilgili varlıkları çıkarmaya yardımcı olmaktadır.
## 3 - Veri Yapılandırma

Analiz ve araştırma raporları, şirket dosyaları ve periyodik finansal belgeler; yatırımcılar, yatırım firmaları ve finans uzmanlarının değerlendirmesi gereken finansal kaynakların sadece bir kısmıdır. Bu kayıtlar genellikle pdf, XML, HTML, web ve beslemeler gibi formatlarda saklanmaktadır ve bunlar arasında gezinmek zaman alıcı ve yorucu bir iş olabilmektedir.

NLP, kullanılmayan verilerden yararlı bilgiler elde etmeye imkan tanımaktadır. NLP modelleri, finans işletmelerini etkileyebilecek sorunları veya desenleri analiz etmek için eğitilebilmektedir. Böylece, karar verme sürecini etkileyebilecek daha derinlemesine bir analiz imkanı ortaya çıkabilmektedir.
## 4- Portföy Seçimi ve Optimizasyonu

Finansal yatırımcıların temel amacı, uzun vadede sermayesini maksimize etmektir. Finansal piyasalarda yatırım stratejileri; veri bilimi, makine öğrenmesi ve parametrik olmayan istatistiklerle tahmin edilebilmektedir. Geçmişe dönük veriler, bir yatırım döneminin ve bir portföyün başlangıcını tahmin etmek için kullanılabilmektedir. Bu verilere dayanarak yatırımcılar mevcut sermayelerini çeşitli varlıklar arasında çeşitlendirebilmektedir.

NLP, yarı-log-optimal portföy optimizasyonu için kullanılabilmektedir. Yarı-log-optimal portföy seçimi, logaritmik optimal portföy seçiminin hesaplama alternatifidir. Bu sayede çevresel faktörler belirsiz olduğunda maksimum olası büyüme oranı elde edilir. Veri zarflama analizi, arzu edilen ve istenmeyen hisseleri filtreleyerek portföy seçimi için kullanılabilecektir.

## 5- Hisse Senedi Davranışını Tahmin Etmek

Finansal analiz için hisse senedi davranışını tahmin etmek, dalgalanan ve rastgele verilerin yanı sıra uzun vadeli ve mevsimsel varyasyonların neden olabileceği önemli hatalara neden olabilen zorlu bir görevdir.

Bununla birlikte, NLP ile birleştirilen makine öğrenmesi, finansal zaman serileri ile çalışmak için önceki yöntemlere kıyasla çok daha iyi performans göstermektedir. Bu iki teknoloji bir araya geldiğinde büyük veri miktarlarıyla etkili bir şekilde başa çıkabilmekte ve hisse senedi fiyatlarının volatilitesini ve eğilimlerini tahmin etmeyi kolaylaştırmaktadır. Bu sayede, hisse senedi alım satım kararlarına yardımcı olan değerli bir araç ortaya çıkmaktadır.

Finansal analiz için zaman serilerini tahmin etmek, dalgalı ve düzensiz verilerin yanı sıra büyük hatalara neden olabilen uzun vadeli ve mevsimsel değişkenlerin etkisi nedeniyle karmaşık bir görevdir. Ancak, derin öğrenme ile NLP'nin bir araya gelmesi, finansal zaman serileriyle çalışan önceki yöntemleri büyük ölçüde aşar. Bu iki teknoloji, büyük miktarda bilgiyi etkili bir şekilde işlemek için bir araya geldiğinde etkili bir şekilde başa çıkarlar.

## 6 - Müşteri İletişimini Raporlama

Finansal kuruluşlar, müşterilerine yüksek kaliteli hizmetler sunmak zorundadır. Bu da müşteri verilerini anlamayı, kişiselleştirilmiş hizmetleri ve müşteri iletişimini gerektirmektedir. Finans sektöründe vazgeçilmez olan bu husus, örneğin bankalara müşterilerle iletişim kurarken önemli bilgiler sağlamaktadır.

NLP algoritmaları müşterilerin sorunlarını tahmin eder ve tanır, bu da finansal kuruluşların bu sorunları ele alacak politikalar ve hizmetler geliştirmesine imkan tanır. Bu açıdan örneğin chatbotlar (sohbet robotları) finansal kuruluşlar için oldukça kullanışlıdır. Yine NLP ile finansal kuruluşlar SSS (sık sorulan sorular) ya da ayrı bir soru cevap bölümünü kolaylıkla hazırlayabilmektedir.
## 7- Muhasebe ve Denetim

Finansal kuruluşlar, yoğun bir gözetim baskısı altındadır. SPK, BDDK, TMSF gibi önemli kamu kurumları, finansal kuruluşları anbean takip etmektedir. Ayrıca Finansal kuruluşlar sıklıkla halka açık olmalarının gereği olarak KAP’a bildirim yapmaktadır. Gün içindeki sayısız işlemin bir de bu şekilde hızlı raporlanması ve bildirilmesi, finansal kuruluşlar açısından oldukça önem taşıyan bir husustur. Bu bakımdan, muhasebe ve denetim amaçları için NLP büyük önem taşımaktadır.

Finans sektörü çalışanları, günlük işlemlerdeki anormallikleri doğrudan tanımlamak, odaklanmak ve görselleştirmek için NLP'yi kullanmaktadırlar. NLP ile işlem anormalliklerini ve nedenlerini tanımlamak daha az zaman ve çaba gerektirmekte ve ayrıca kara para aklama gibi önemli potansiyel riskleri ve olası dolandırıcılıkları tanımlamaya yardımcı olmaktadır.
## 8- Finans Sektöründe NLP Kullanımının Sunduğu Avantajlar

Finans sektöründe NLP'nin tam anlamıyla kullanılmasının faydalarını özetleyecek olursak, aşağıdaki 5 temel faydadan bahsetmek mümkündür:

### 8.1. Verimlilik

NLP, büyük miktardaki yapılandırılmamış içeriği anlamlı bilgilere anında dönüştürme yeteneğine sahiptir.

### 8.2. Tutarlılık

Tek bir NLP modeli, metinle ilgili farklı yönleri farklı şekillerde çözen insanların oluşturduğu bir ekipten çok daha tutarlı sonuçlar sağlayabilmektedir.

### 8.3. Doğruluk

İnsanlar, hacimli yapılandırılmamış belgelerde içeriği gözden kaçırabilmekte veya yanlış okuyabilmektedirler. NLP destekli sistemlerde bu tür hatalar daha fazla ortadan kaldırılmaktadır.

### 8.4. Ölçeklendirme

NLP teknolojisi kullanarak çeşitli belgeler, iç süreçler, e-postalar, sosyal medya verileri ve daha fazlası üzerinde ölçekli metin analizi mümkündür. Manuel analiz günler alırken, NLP ile büyük miktardaki verinin işlenmesi saniyeler veya dakikalar içinde gerçekleştirilebilmektedir.

### 8.5. Süreç Otomasyonu

NLP, finansal verilerden elde edilen pratik bilgileri tarama ve çıkarma sürecini tamamen otomatikleştirme bakımından fayda sağlamaktadır.
## 9. Finans Sektöründe NLP Kullanımının Kısıtları

Finans sektöründe NLP; süreçleri otomatikleştirmek, hataları azaltmak ve 7/24 müşteri desteği sunmak gibi faydalara sahiptir. Bununla birlikte, finans sektöründe NLP kullanırken kullanımında aşağıda belirtilen bazı zorluklar da gözlemlenmektedir:

### 9.1. Veri Gizliliği

Finansal kuruluşların karşılaştığı en büyük zorluklardan biri veri gizliliğidir. Özelikle bankalar, korunması gereken hassas müşteri verilerine sahiptir. Yapay zeka ve NLP kullanırken, finansal kuruluşlar, makine öğrenme algoritmalarını eğitmek için verileri üçüncü taraf sağlayıcılarla paylaşmak zorunda kalırlar. Burada verilere kimlerin erişebileceği ve verilerin nasıl kullanılacağına ilişkin güvenlik endişeleri ortaya çıkmaktadır.

Ayrıca, bankacılık ve finans sektöründe NLP kullanımıyla ilgili düzenleyici mevzuata ilişkin endişeler de bulunmaktadır. Örneğin, bir banka kredi kararları almak için NLP kullanıyorsa, taraflı karar vermeye ilişkin çekinceler olabilmektedir. Bu nedenle, NLP sistemlerinin karar alma sürecinde nasıl davrandığı konusunda şeffaflık sağlanması gerekmektedir.

### 9.2. Veri Kalitesi

NLP sistemleri etkili bir şekilde çalışmak için büyük miktarda veriye ihtiyaç duymaktadır. Ancak finans kuruluşları belirli ürünler veya müşterilerle ilgili yeterli veriye sahip olmayabilirler. Ayrıca, makine öğrenme modelleri, giriş olarak temiz ve iyi yapılandırılmış veriye ihtiyaç duyar ve finans kuruluşlarının elindeki veri yüksek kalitede olmayabilir. Bu noktada, pahalı ve zaman alıcı veri temizleme süreçlerine ihtiyaç duyulacaktır.

### 9.3. Redde İlişkin Gerekçeler

Finansal hizmetler için NLP tabanlı sistemler bir kişinin hayatını önemli ölçüde etkileme kapasitesine sahiptir. Örneğin, sistem bir müşterinin kredi talebini onaylamazsa, müşterinin geleceğine büyük bir etkisi olabilmektedir. Sistemin kararlarını yalnızca tasarımına dayalı olarak alması durumunda, finans kuruluşlarının talebin reddine ilişkin kararıları müşterilere açıklaması zor olacaktır. Doğru bir gerekçelendirme yapılmadan müşterileri reddetmek, finans kuruluşları açısından müşteri kaybının yanısıra yasal otoriteler karşısında sorumluluklara da yol açabilecektir.

### 9.4. Yüksek Yatırım Maliyeti

Küçük ölçekli kuruluşlar açısından ileri düzey NLP tabanlı sistemlerin maliyeti karşılanamayacak düzeyde olabilmektedir. Yazılım ve ek donanım maliyetlerinin yanı sıra düzenli güncellemelerin planlanması ve uygulanması gerekmektedir. Güncelleme ile ilgili bir sorun ortaya çıkması halinde sistemlerin uzun süre kullanım dışı kalması da beklenebilir. Finans kuruluşları, yasal düzenlemeler neticesine belirli bir hacimde ve yeterli sermayeyle kurulmak zorundadır. Bu nedenle, sistemin pahalılığı finans kuruluşları açısından bir sorun yaratmayacaktır. Ancak sistemin uzun süre kulanım dışı kalması, finans kuruluşlarının çok büyük maliyetlerle karşılaşmasına neden olabilecektir.

## Sonuç

Finans sektöründe, NLP; işlemleri hızlandırmak, riskleri değerlendirmek, finansal duyguları anlamak, portföyler oluşturmak ve muhasebe ile denetimi otomatikleştirmek gibi çok sayıda amaç için kullanılmaktadır. Doğal dil işleme teknikleri son zamanlarda daha kesin ve güvenilir hale gelmiştir, bu da finansal kararları daha verimli ve maliyet etkin hale getirmektedir. Son dönemde NLP, finans kuruluşlarında yaygın bir şekilde kullanılmaktadır.

Ancak, finans sektöründe NLP kullanımı, bazı avantajlara sahip olmasının yanı sıra bazı sınırlılıklara da sahiptir. Finansta NLP kullanımının başlıca avantajları; doğruluk, tutarlılık, ölçeklendirme, verimlilik ve süreç otomasyonudur. Ancak finans sektöründe NLP kullanımının bazı riskleri de bulunmaktadır: algoritmaların insanlar tarafından anlaşılması zor olabilir, gizlilik haklarına ilişkin sorunlar ortaya çıkabilmektedir.

Bununla birlikte; sağlık, eğitim, iş dünyası ve veri bilimi gibi birçok endüstriyi dönüştüren NLP, finans sektöründe de önemli bir dönüşümü beraberinde getirmiştir. Bankalar, NLP destekli sohbet botları kullanarak müşterilerle iletişimlerini geliştirmekteler ve müşteriler NLP sayesinde sorularına daha kolay yanıt bulabilmektedir. Finans kuruluşları ayrıca riskleri yönetmek ve rutin görevleri otomatikleştirmek için NLP kullanmaktadırlar.

Gelecekte, NLP’nin finansal kuruluşların yeni gelir kaynaklarını belirlemelerine, kredi kararları almalarına ve kişiselleştirilmiş finansal danışmanlık sunmalarına yardımcı olmaları beklenmektedir. NLP'nin gelişimine bağlı olarak finans sektörü çok daha büyük dönüşümler yaşayacaktır. Özellikle genç nüfusun artan oranda dijital kanalları tercih etmeleri, NLP’nin finansal kuruluşlar açısından taşıdığı önemi ortaya koymaktadır.

## Kaynakça

 1. Eisenstein, J. (2019). _Introduction to Natural Language
    Processing._ Cambridge, MA: The MIT Press.
    
 2. Kochmar, E. (2022). _Getting Started with Natural Language
    Processing._ Shelter Island, NY: Manning.

