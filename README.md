# eczane_sistemi
📌 Proje Konusu
Dijital Eczane ve İlaç Teslimat Sistemi
Doktor, eczacı, hasta ve kurye arasındaki ilaç hazırlama ve teslimat sürecini tek bir web platformu üzerinden yönetmeyi amaçlayan bir sistem geliştiriyoruz.

Problem:
Geleneksel süreçte doktorun reçete oluşturması, hastanın eczaneye ulaşması, eczacının ilaçları hazırlaması ve ilacın hastaya ulaştırılması farklı aşamalardan oluşmaktadır. Özellikle yaşlı, hareket kısıtlı veya eczaneye ulaşmakta zorlanan hastalar için ilaçların güvenli şekilde teslim alınması önemli bir problemdir.

 
Çözümümüz:
Geliştireceğimiz web sisteminde 4 farklı kullanıcı rolü bulunacaktır:
Doktor: Sisteme giriş yaparak hastayı seçer ve sistemde bulunan ilaçlardan gerekli olanları seçerek hasta adına reçete oluşturur ve onaylar.
Eczacı: Doktor tarafından oluşturulup onaylanan reçeteyi görüntüler, ilaçların stok durumunu kontrol eder ve ilaçları hasta için hazırlar.
Hasta: Kendisine oluşturulan reçeteyi, ilaçların hazırlanma durumunu ve teslimat sürecini görüntüler. Teslimat için uygun zaman aralığını seçebilir.
Kurye: Eczacı tarafından teslimata hazır hale getirilen siparişi görüntüler ve hastaya ulaştırır. Teslimat, sistem tarafından oluşturulan tek kullanımlık teslimat kodu ile doğrulanır.

 Sistem Akışı
Doktor → Reçete oluşturur- Hasta teslimat zamanını seçer → Eczacı → İlaçları hazırlar → Kurye → Hastaya teslim eder → Hasta → Teslimat koduyla doğrular
