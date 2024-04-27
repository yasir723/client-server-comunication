# İstemci - Sunucu İletişimi (Client - Server Communication)
Bir istemci uygulaması (Firefox, Google Chrome vb.) kullanılarak herhangi bir web sitesi, belirli bir sunucuya `HTTP Request` gönderilerek açılır. Örneğin, `www.google.com` adresini açmak için, istemci Google adlı sunucuya bir istek gönderir ve bu sunucu isteği işler, ardından `HTML` formatında sonuç gönderir.

Tarayıcılar (browsers), HTML kodunu anlar ve bizim görebileceğimiz bir şekle dönüştürür. Bu tür iletişimlere `HTTP stateless` denir. Çünkü sunucunun istemci hakkında hiçbir bilgisi yoktur, sadece gelen taleplere yanıt verir. `İstemcinin kim olduğunu tespit edemez`.

<div align="center">
    <h3></h3>
    <img src="https://github.com/yasir723/web-guvenligi/assets/111686779/f5f3f403-9df7-4cd2-8c66-4d747e7aede9">
</div>

Yukarıdaki senaryoya göre kullanıcı Firefox tarayıcısını kullanarak `http://host/index.php` sitesinin içeriğini görmek ister bu yüzden client tarafından servere bir request gönderilir bu request `index.php sayfasının yerini bildirme talebi` ve madem aranılan sayfa `php` demek server `apache`. Server kendisine ait harddiskte dosyayı arar mevcutsa işleme yapılır (processing PHP) ve eğer dosyada veritabanına bağlantısı varsa veritabanına bağlanır gerekli sonuçları elde edilir ve yine processing PHP'ye geri gönderilir. Veri işlemesi sonrasında HTML uzantılı dosyayı oluşturur. ardından bu dosyayı kullanıcıya geri gönderir
