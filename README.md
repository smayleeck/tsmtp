# Teknik Servis Müşteri Takip Programı


Son zamanlarda kendi ihtiyaçlarım doğrultusunda ve mevcut kullandığımız programın hem eskiliğinden olsun hem de yetersizliğinden olsun boş vakitlerimde ChatGPT, Grok ve Gemini yapay zekalarının da yardımıyla bir teknik servis müşteri takip programı geliştirdim. 

Program açıldığında, kullanacağı musteriler.db dosyasını programın bulunduğu klasöre oluşturmakta. Demo olduğu için toplamda 10 müşteri ve 10 servis kaydı oluşturulabiliyor.

### Şimdilik eklediğim özellikler
1. Müşteriler paneli
   - Müşteri kaydı ekleme, düzenleme ve silme (ve bunları kısayol tuşları ile yapabilme)
     - İsim, telefon 1, telefon 2 ve adres bilgilerini kaydetme.
     - Ana ekranda, müşteriye eklenen son servis kaydının tarihini "Son İşlem Tarihi" olarak gösterme.
     - Arama çubuğunda İsim, telefon 1, telefon 2 ve adres bilgilerinden hangisi girilirse girilsin sonuç gösterme.
       
2. Servis kayıtları paneli (kayıtlı müşteriye çift tıklanıldığında açılır sol panelde gizli)
   - Servis kaydı ekleme, düzenleme, silme ve hatırlatıcı ekleme (ve bunları kısayol tuşları ile yapabilme)
     - Fiş no, cihaz, marka, model, çağrı tarihi, işlem tarihi, ücret bilgilerini kaydetme.
     - Ayrıca alt panelde müşteri şikayeti ve yapılan işlem bilgilerini gösterme.
    
3. Stok Yönetimi paneli
   - Ürün kaydı ekleme, düzenleme ve silme
     - Barkod (otomatik barkod oluşturma), ürün adı, marka (listeye ekleme yapılabilir), cihaz (listeye ekleme yapılabilir), satış fiyatı bilgilerini kaydetme.
   - Stok giriş, stok çıkış, stok düzenleme ve stok silme
   - Depo Yönetimi (listeye ekleme yapılabilir)
   - Etiket Bas'tan etiket basılabilir. (Ayarlar panelinden ölçüleri ayarlanabiliyor.)
     
5. Hatırlatıcılar paneli
   - Servis kayıtları panelinden eklenen hatırlatıcı bu panele eklenir. Hatırlatıcı günü geldiğinde Windows bildirimi hatırlatıcı silinene kadar her dakika tetiklenir.
      - Bu paneli yapmamın temel sebebi su arıtma müşterilerinin periyodik bakımlarını takip etmek içindi. Ama periyodik klima bakımlarının da takip edilmesi için ideal.
        
6. Ayarlar paneli
   - Genel ayarlar paneli
     - Program adı değiştirme, 220x100 logo ekleme, program ikonu değiştirme
   - Görünüm paneli
     - Programda kullanılan (neredeyse) bütün renklere erişebilme (varsayılan renklere toplu veya tek tek döndürebilme seçeneği)
   - Etiket ayar paneli
     - Etiket genişliği ve yüksekliği ayarlayabilme.
     - Etikette kullanılan barkod çizgi yüksekliği ayarlayabilme.
   - Veritabanı yedekleme/geri yükleme
   - Excel'den müşteri aktarımı
   - Lisans paneli
     - Programı demo sürümden çıkarmak için gereken Makine ID ve Lisans anahtarları bölümleri bulunmakta.
     
7. Güncel döviz kuru paneli
   - Merkez bankası verilerini alıyor.
  

### Programdan görüntüler
<img width="901" height="549" alt="image" src="https://github.com/user-attachments/assets/e692e900-ec38-4b21-98f3-2d6c95c05362" />

<img width="901" height="549" alt="image" src="https://github.com/user-attachments/assets/2c405e05-e3bd-4685-9ee5-bc848cdffacb" />

<img width="901" height="549" alt="image" src="https://github.com/user-attachments/assets/0363a414-fffe-43be-9446-a57a805273f1" />

<img width="901" height="549" alt="image" src="https://github.com/user-attachments/assets/fae07fd0-2fc9-458f-804c-f5b893e48de1" />

<img width="901" height="549" alt="image" src="https://github.com/user-attachments/assets/db78758a-58fd-47ca-a8f9-b0d54bc85b87" />

<img width="901" height="549" alt="image" src="https://github.com/user-attachments/assets/a3ee6450-2f17-4fbd-9f1e-ab604dd59de7" />

