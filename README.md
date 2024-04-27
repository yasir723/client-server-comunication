# İstemci - Sunucu İletişimi (Client - Server Communication)
Bir istemci uygulaması (Firefox, Google Chrome vb.) kullanılarak herhangi bir web sitesi, belirli bir sunucuya `HTTP Request` gönderilerek açılır. Örneğin, `www.google.com` adresini açmak için, istemci Google adlı sunucuya bir istek gönderir ve bu sunucu isteği işler, ardından `HTML` formatında sonuç gönderir.

Tarayıcılar (browsers), HTML kodunu anlar ve bizim görebileceğimiz bir şekle dönüştürür. Bu tür iletişimlere `HTTP stateless` denir. Çünkü sunucunun istemci hakkında hiçbir bilgisi yoktur, sadece gelen taleplere yanıt verir. `İstemcinin kim olduğunu tespit edemez`.

<div align="center">
    <h3></h3>
    <img src="https://github.com/yasir723/istemci-sunucu-iletisimi/assets/111686779/6075801b-e647-4c6c-a62f-09a1ec5e48a7">
</div>

Kullanıcı, Firefox tarayıcısını kullanarak `http://host/index.php` adresindeki içeriği görmek ister. Bu nedenle istemci tarafından sunucuya bir `istek (request)` gönderilir. Bu istek, index.php sayfasının yerini belirten bir taleptir. Sunucu, bu talebi alır ve eğer aranan sayfa bir PHP dosyasıysa, işleme yapmak üzere `Apache` sunucusuna iletir. Sunucu, kendi harddiskinde (HDD) dosyayı arar ve bulunursa `PHP işlemi (Processing PHP)` gerçekleştirir. Eğer dosyada veritabanı bağlantısı varsa, sunucu veritabanına bağlanır ve gerekli verileri elde eder. Sonrasında, PHP işlemi sonucunda oluşturulan `HTML dosyası` kullanıcıya geri gönderilir. Genelde saldırıların çoğu Client tarafına yapılır.

