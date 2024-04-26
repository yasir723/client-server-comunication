# Client - Server Comunication
Bir client app (Firefox, Google Chrome vb.) kullanarak her hangi bir web sitesini açmak için bir `Server`'e belirli bir `HTTP Request` göndererek açılır. örnek olarak `www.google.com` açmak için google adılı serverine request gönderiliyor ve bu server gönderilen request'i işletiyor ve ona göre `HTML` şeklinde sonuç gönderir

Browser (tarayıcı) HTML kodunu anlıyor ve bizim anlamamız için HTML kodunu `view` şekline dönüştüryor. Bu tür iletişimlere `HTTP is stateless` denir. çünkü server'in client hakkında hiç bir bilgisi olmuyor, sadece ve sadece ona gelen taleplere sonuç veriyor, bu client'in kim olduğunu tespit edemiyor

<div align="center">
    <h3></h3>
    <img src="https://github.com/yasir723/web-guvenligi/assets/111686779/f5f3f403-9df7-4cd2-8c66-4d747e7aede9">
</div>
