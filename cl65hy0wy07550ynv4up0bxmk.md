## Native Platform için özel XML Layoutlar iyi bir fikir mi?

Android ve Microsoft’un mobil yazılım geliştirme platformlarını incelediyseniz son yıllarda “view” katmanlarının business logic’den ayrılmasına aşina olan yazılımcı sayısının artmasından hem de HTML’in kitlelerce benimsenişinden dolayı XML layout’lar üzerine kurulmuş olduğunu fark etmişsinizdir.

Bu mimaride view tarafındaki “element”ler genellikle Flash’dan tanıdık gelecek storyboard üzerinde belirtilen transitionlar ile animasyon kazanıyor. Yine belirli nesne özelliklerinin değiştirilerek view ve business logic arası iletişimin sağlanıyor. Bunun HTML’in çıkış noktasından çok daha derin bir mimari ve tasarıma sahip olduğunu inkar edemeyiz.

Ancak her iki platformda da geliştirme yapmış biri olarak ifade etmeliyim ki, pratikte bir noktada sorun yaşanıyor. Learning Curve’ü düşük olsa dahi her XML Layout’un kendine has component ve özelliklerini, business logic’de bunların nasıl kullanıldığını ve nasıl manipüle edilebileceğini öğrenmek çoğu zaman çözüm geliştirenlerin iyi developer olmasıyla değil de, o platformda “fazla” zaman geçirmiş developer olmasına yol açıyor.

Bir “markup”a bağlı bir yapıdan bahsediyorsak, benim görüşüm HTML/CSS/JS’nin yıllarca olgunlaşarak, challenge’ı yaşarak geldiği noktayı kapsamak ve bunu yaparken developerların faydalandığı tool ve practise’leri dışarıda bırakıyor olmanın karlı olmadığı yönünde. Şirketlerin kendine ait development environment kurma refleksinin zayıf argümanlarını bir yana koyalım, ne android ne windows platformları temelde HTML/CSS/JS’nin sağladığı kombinasyondan fazlasını vaad edebilir durumda değil.

Bir platform oluşturuyor olsam benim tercihim kesinlikle özel bir XML Layout tasarlamaktansa HTML/CSS/JS’i kullanmanmanın yolunu aramak olurdu. İhtiyaçları komunitenin belirlemediği, sürekliliğini ve gelişimini sağlamadığı tüm platformlar yok olmaya mahkum oluyorlar. XAML, XUL, XML Layout gibi standartlar firmaların “bir sonraki” trend’e yetişme çabası içinde kaybolup asla olgunlaşamadılar diye düşünüyorum keza bugün bunlar artmak yerine azalma trendinde görünen teknolojiler.

Bu noktada XML layout’ların design guideline’lar içinde verilen belirli arabirim bileşenlerine (swipe tab navigation gibi) doğal desteği ve HTML kadar genişliğe sahip olmaksızın nispeten daha hızlı çalışacak object model yapısının savunulacağını biliyorum. Bu nedenle, bu noktada W3C’nin yalnızca bu tarz durumlar için HTML’in ufak bir subset’ini oluşturabileceğini veya belirli bir yere kadar getirdikleri XHTML standartını geliştirmeye devam etmeleri gerektiğini düşünmekteyim.

*Originally published at* [*eser.ozvataf.com*](http://eser.ozvataf.com/native-platform-icin-ozel-xml-layoutlar-iyi-bir-fikir-mi/) *on December 15, 2013.*