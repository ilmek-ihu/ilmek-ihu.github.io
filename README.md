# İlmek Takvimi ve Web Sitesi

İbn Haldun Üniversitesi İslam Medeniyeti Kulübü (İlmek) için kurulan etkinlik takvimi sisteminin devir notu. Sistemi devralan YK üyeleri ve yeni bir yapay zekâ sohbetinde kaldığımız yerden devam etmek için hazırlandı.

Site: https://ilmek-ihu.github.io

## Sistem nasıl çalışıyor?

1. Kulübün Google hesabında iki takvim var: **İLMEK-Hanımefendiler** ve **İLMEK-Beyefendiler**.
2. Üyeler siteye girip kendi takvimlerine **bir kere** abone oluyor.
3. YK takvime etkinlik ekledikçe veya değiştirdikçe, etkinlik abonelerin telefonlarına kendiliğinden düşüyor.
4. Haftalık WhatsApp duyurusu devam ediyor. Takvim onun yerine geçmiyor, üzerine eklenen bir kolaylık.

## Hesaplar

| Ne | Nerede |
|---|---|
| Kulüp Google hesabı | Takvimlerin sahibi |
| GitHub hesabı | `ilmek-ihu` |
| Site deposu | github.com/ilmek-ihu/ilmek-ihu.github.io |

YK üyeleri takvimlere ve siteye kulüp hesabı üzerinden erişir, ayrıca kişisel yetki verilmez. Yönetim devrinde bu iki hesap birlikte devredilir.

## Takvimler

**İLMEK-Beyefendiler**
- Takvim kimliği: `c_31ff3e26371275fcccff39e283a901d3920947cc4fa4dbd7c2df0e9af7b06cc7@group.calendar.google.com`
- Android/Google aboneliği: https://calendar.google.com/calendar/u/0?cid=Y18zMWZmM2UyNjM3MTI3NWZjY2NmZjM5ZTI4M2E5MDFkMzkyMDk0N2NjNGZhNGRiZDdjMmRmMGU5YWY3YjA2Y2M3QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20
- iCal adresi (iPhone): https://calendar.google.com/calendar/ical/c_31ff3e26371275fcccff39e283a901d3920947cc4fa4dbd7c2df0e9af7b06cc7%40group.calendar.google.com/public/basic.ics

**İLMEK-Hanımefendiler**
- Takvim kimliği: `c_acf9c50f403b5b0c59c4dd7db16910f25c5cdc1859e7d269fa8e4f1c253ecc41@group.calendar.google.com`
- Android/Google aboneliği: https://calendar.google.com/calendar/u/0?cid=Y19hY2Y5YzUwZjQwM2I1YjBjNTljNGRkN2RiMTY5MTBmMjVjNWNkYzE4NTllN2QyNjlmYThlNGYxYzI1M2VjYzQxQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20
- iCal adresi (iPhone): https://calendar.google.com/calendar/ical/c_acf9c50f403b5b0c59c4dd7db16910f25c5cdc1859e7d269fa8e4f1c253ecc41%40group.calendar.google.com/public/basic.ics

**Yapılmış ayarlar (iki takvimde de)**
- Herkese açık: **açık**, seçenek **"Etkinlik ayrıntılarını görme"** (yani tüm ayrıntılar görünür; "serbest/meşgul" seçeneği değil).
- Davetiyeleri otomatik kabul: **"Davetiyeleri gösterme"** (dışarıdan biri takvime etkinlik sokamasın diye).
- "Diğer bildirimler" e-postaları: **Yok**.
- iCal **gizli** adresi kimseyle paylaşılmaz.

## Haftalık iş akışı

**Etkinlik kuralları**
- Hanımlara yönelik etkinlik: sadece Hanımefendiler takvimine.
- Beylere yönelik etkinlik: sadece Beyefendiler takvimine.
- Ortak etkinlik: **iki takvime de** eklenir ve başlığın sonuna **(Ortak)** yazılır, örn. "Hayır Çarşısı (Ortak)". Değişiklik olursa iki takvimde de düzeltilir.
- Her etkinlikte başlangıç ve bitiş saati, konum (örn. "Katar Odası, İTBF B0.03, İbn Haldun Üniversitesi") ve kısa açıklama olsun.
- Saati belli olmayan etkinlik geçici olarak "tüm gün" girilir, saat netleşince düzeltilir.

**Toplu ekleme (.ics dosyasıyla)**
1. Haftanın etkinlikleri iki .ics dosyası olarak hazırlanır (Hanımefendiler, Beyefendiler).
2. Bilgisayardan Google Takvim → ⚙️ Ayarlar → **İçe ve dışa aktar** → dosyayı seç → **"Takvime ekle"** kısmında doğru takvimi seç → İçe aktar.
3. Aynı dosya iki kez yüklenirse etkinlikler çift görünür. Sonraki düzeltmeler takvimden elle yapılır.

## Site

- Depodaki dosyalar: `index.html` (sitenin kendisi, logo dosyanın içine gömülü), `og.png` (WhatsApp link önizleme görseli), `README.md` (bu not).
- Güncelleme: depoda **Add file → Upload files** → aynı adlı dosyayı sürükle → **Commit changes**. 1-2 dakikada yayına girer.
- Sayfa, telefonun iPhone mu Android mi olduğunu kendisi anlar ve ona göre doğru abonelik butonunu gösterir. Seçim hatırlanmaz, sayfa her açılışta seçimsiz gelir.

**Görsel kimlik**
- Renkler: turkuaz `#47a397` (logo rengi), antrasit `#2c3a40`, bakır `#a8714f`, kâğıt zemin `#f2efe9`. Koyu mod da var.
- Yazı karakterleri: başlık Oswald (büyük harf), vurgu Playfair Display italik, metin Source Sans 3.
- Arka planda hafif sekiz köşeli yıldız (girih) deseni, sağda turkuaz şerit. Afişlerimizin diliyle uyumlu.
- Slogan: **"hiçbir ilmeği kaçırma"**

## Açık işler (son durum: 18 Ekim 2026)

- [ ] iPhone ve Android'de abonelik testi (iPhone abonelik butonunun çalıştığı doğrulanacak; çalışmazsa elle ekleme talimatı geri eklenecek).
- [x] Google Sites'taki eski deneme sitesi yayından kaldırıldı.
- [ ] İlk WhatsApp duyurusu yeni linkle atılacak.
- [ ] Hadis Halkası konumu ve Psiko Rota saati netleşince takvimde düzeltilecek.
- [ ] Karar bekliyor: iPhone kullanıcılarına hatırlatma için "Ayarlar → Takvim → Varsayılan Uyarı Zamanları" notu eklensin mi? (Bu ayar telefondaki tüm etkinlikleri etkiler; abone olunan takvimlerde çalıştığı test edilmeli.)

## İleriye dönük fikirler

- Siteyi kulübün web sitesine genişletmek: hakkımızda, afiş arşivi, kayıt formları, takvimin gömülü görünümü.
- İleride kendi alan adı (örn. ilmek.org) GitHub Pages'e bağlanabilir.

## Yapay zekâ ile devam ederken

Yeni bir sohbette bu dosyayı (ve gerekirse `index.html`'i) ekleyip şunu yazın:

> "Bu, İlmek kulübü için kurduğumuz takvim sisteminin devir notu. Buradan devam etmek istiyorum: [yapmak istediğiniz şey]"
