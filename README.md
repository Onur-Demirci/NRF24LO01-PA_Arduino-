# NRF24LO01-PA_Arduino-
Dikkat edilmesi gerekenler  
1. Arduino üzerinde  CE,CSN pinlerinin doğru bağlanmış ve pin atamalarının doğru atılmış olması
2. 3.3v Regülatörünün harici bir regüle üzerinden sabit verilmesi.
3. LCD ekran kütüphanesinin yüklenmesi gerekmekte ve eğer ekran kullanılacak ise EPROM gibi ek hafıza birimi kullanılmalıdır. (Şu anki devrede mevcut değildir!!)
4. butonlar pull-up dirençleri ile bağlanmalıdır veya pull-down
5. kanallar üzerinde delay eklenmemeli fonksiyona bağlı ekran stringleri atılmamalı.
