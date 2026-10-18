# boz405u0202-lms-tasarim-sprinti--devi
# LMS Kaynak Yönetimi İçin Hızlı Tasarım Sprinti (MTS)

Bu proje, **Mühendislik Tasarım Süreci'nin (MTS)** beş temel aşamasını (Empati, Tanımlama, Fikir Üret, Prototiple, Test Et) kullanarak bir eğitim teknolojisi problemi olan **"kaynak karmaşasına"** yönelik kullanıcı odaklı bir çözüm üretmek amacıyla gerçekleştirilmiştir.

---

## 📋 Proje Adımları

### Adım 1: Empati & Tanımlama
* **Empati Haritası ("Üniversite Öğrencisi" Personası):**
  * **Ne Görüyor?** Haftalık başlıklar altında yığılmış onlarca PDF, slayt, video ve link; karmaşık isimlendirmeler ve telefonda zor açılan arayüzler.
  * **Ne Duyuyor?** *"Hoca geçen hafta hangi slaytı yüklemişti?", "Aramak yerine arkadaştan WhatsApp'tan isteyeceğim."*, hocadan *"Hepsi LMS’te var"* uyarısı.
  * **Ne Düşünüyor & Hissediyor?** Önemli sınavlar öncesi aradığı kaynağa ulaşamayınca yaşanan yoğun stres, mide bulantısı ve *"Çalışmaya başlamadan yoruldum"* hissi.
  * **Ne Söylüyor & Yapıyor?** Standart arama çubuğundan sonuç alamayınca dosyaları indirip kendi klasörlerine manuel düzenliyor veya çalışmayı erteliyor.
  * **Acısı:** Çalışmak istediği kaynağı bulmak için, çalışmaktan daha fazla zaman ve enerji harcamak.
  * **Kazancı:** Ders materyallerine anında, filtrelenmiş ve kişiselleştirilmiş bir arayüzle tek tıkla ulaşabilmek.

* **Problem Çerçeveleme:**
  * **Net Problem Cümlesi:** Üniversite öğrencisi, çalışmaya oturduğu anda doğru kaynağı tek bakışta bulmaya ihtiyaç duyuyor; çünkü asıl yorulduğu yer çalışmanın kendisi değil, kaynak aramakla harcadığı enerji; bu yüzden motivasyonu daha ilk adımda tükeniyor.
  * **"Nasıl Yapabiliriz?" (HMW) Sorusu:** Öğrencinin LMS’i açtığı ilk 10 saniyede “şimdi neyi çalışmalıyım?” sorusunun cevabını görmesini ve kaynak aramadan binlerce dosya arasından aradığını saniyeler içinde bulabilmesini nasıl sağlayabiliriz?

---

### Adım 2: Fikir Üret (Beyin Fırtınası ve Seçim)
Beyin fırtınası sürecinde üretilen fikirler arasından kullanıcı deneyimini en çok iyileştiren **3 ana özellik** seçilmiştir:
1. **Akıllı Etiket ve Renk Kodlama Sistemi:** Dosyaların türüne (Slayt, Makale, Ödev, Video) ve zorluk derecesine göre otomatik renkli etiketler alması, filtreleme butonlarıyla hızlı erişim.
2. **Yapay Zekâ Destekli 3 Satırlık Özet:** Her kaynağın altında içeriği hızlıca özetleyen yapay zekâ önizlemesi.
3. **“Bugün ne çalışayım?” Butonu:** Sınav tarihlerine ve öğrencinin tercihlerine göre günlük 2-3 kritik kaynak öneren akıllı yönlendirici.

* **Seçim Gerekçesi:** Bu özellikler öğrencilerin "hangi konudan başlasam?" karar verme stresini azaltır, dosyaları indirmeden AI özetleriyle hızlı tarama imkanı sunarak bilişsel yükü en aza indirir.

---

### Adım 3: Prototiple (3 Ekran Tasarımı)
Tasarlanan düşük sadakatli (low-fidelity) mobil/web arayüz akışı:

* **Ekran 1 (Bugün):** Günlük önerilen kaynaklar, AI özetleri ve *"Bugün ne çalışayım?"* akışı.
* **Ekran 2 (Konular & Filtre):** Hızlı filtreleme butonları (`Slayt`, `Video`, `Ödev`, `Makale`) ve renk kodlu etiket listesi.
* **Ekran 3 (Planım):** Sınav tarihleri, günlük çalışma süresi ve kişiselleştirme ayarları.

*(Prototip görselini repoya ekledikten sonra buraya ekleyebilirsin: `![Prototip Ekranları](ekran-goruntusu.png)`)*

---

### Adım 4: Test & İterasyon
* **Kullanıcı Testi:** Prototip bir kullanıcıya *"Yarın vizen var. Bugün ne çalışacağını bul, ardından Türev ödevini bul"* senaryosuyla test ettirildi.
* **Alınan Geri Bildirimler:** Günlük hatırlatmalar çok beğenildi; ancak kaynakların üzerindeki süre dakikalarının (örn: 15 dk) kullanıcıda yarış stresi yarattığı ve sağ üstteki ayar simgesinin ilk başta anlaşılamadığı belirtildi.
* **Hızlı İterasyon:** Dakika baskısı yaratan ifadeler "tahmini süre" olarak sadeleştirildi ve simgeler netleştirildi.

---

### Adım 5: Bireysel Öğrenim Yansıması
Bu süreçte Mühendislik Tasarım Süreci’nin (MTS) en çok **Test & İterasyon** aşamasında zorlandım çünkü tasarladığım bir özelliğin (dakika sayacının) kullanıcıda stres yaratabileceğini test etmeden fark edemezdim. En çok **Empati ve Problem Çerçeveleme** aşamasında öğrendim; öğrencinin asıl sorunubun dosya çokluğundan ziyade "nereden başlayacağını bilememe" kararsızlığı olduğunu fark etmek bakış açımı değiştirdi. Bu deneyimin en değerli çıktısı, arayüz tasarlarken teknolojiden önce gerçek kullanıcının duygusal durumunu ve bilişsel yükünü gözetmenin ne kadar hayati olduğunu anlamak oldu.
