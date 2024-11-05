# BMÜ329 Veri Tabanı Sistemleri Dersi Dönem Projesi Gereksinimleri ve E-R Diyagramı

## Proje Başlığı: Endüstriyel Otomasyon ve Haberleşme Ürünleri Yönetim Sistemi

**Proje Ekibindeki Kişiler:**
- **220260020** - Muhammed Salih Üstün
- **220260054** - Emre Gülek
- **220260092** - Muhammed Gökhan Şentürk

---

## Endüstriyel Otomasyon ve Haberleşme Ürünleri Yönetim Sistemi

### 1. Cihaz Yönetimi


#### 1.1 Cihaz Listesi Görüntüleme

    •    Kullanıcılar, kendilerine tanımlı cihazların temel özelliklerini (cihaz adı, seri numarası, cihaz tipi) görüntüleyebilmelidir.
    •    Teknik Destek Ekibi ve Yöneticiler, tüm cihazların teknik ve donanım özelliklerine (çevresel koşullar, güç besleme, haberleşme portları) erişebilir.
    •    Yönetici ve Çözüm Ekipleri, cihazların tüm detaylarına erişim sağlayarak bu bilgileri düzenleyebilmelidir.

#### 1.2 Cihaz Özelliklerini Güncelleme

    •    Teknik Destek Ekibi cihazların çevre koşulları (çalışma sıcaklıkları, nem koşulları), haberleşme protokolleri (Ethernet, GSM, RS485), güç besleme ve garanti bilgileri gibi temel teknik özelliklerini güncelleyebilmelidir.
    •    Yönetici ve Çözüm Ekipleri, cihazların programlanabilir fonksiyonları, haberleşme protokolleri ve giriş/çıkış portları gibi kritik özellikleri düzenleyebilir.

### 2. Donanım ve Yazılım Yetenekleri


#### 2.1 Donanım Yetenekleri

    •    Teknik Destek Ekibi, cihazların donanım özelliklerini (USB portları, dijital/analog girişler, RS485 destekleri gibi) inceleyebilmelidir.
    •    Çözüm Ekipleri, cihaz donanımını geliştirebilmek için cihazlara yeni haberleşme portları ekleyebilir veya mevcut portları düzenleyebilir.
    •    Yöneticiler, donanım bileşenlerinin (LED sinyalleri, GPIO çıkışları, optik sinyaller) ayarlarını değiştirme yetkisine sahip olmalıdır.

#### 2.2 Yazılım Yetenekleri

    •    Teknik Destek Ekibi, cihazların yazılım yeteneklerini (programlama fonksiyonları, IoT uyumluluğu, Modbus, TCP/IP desteği gibi) izleyebilir ve gerekli yazılım güncellemelerini yönetebilir.
    •    Çözüm Ekipleri, yeni yazılım özellikleri geliştirebilir ve mevcut yazılımı optimize edebilir. Ayrıca, cihazların NTP zamanı senkronizasyonu, MODBUS haberleşmesi gibi kritik işlevlerini yönetebilir.

### 3. Haberleşme Protokolleri ve Portları


#### 3.1 Protokoller

    •    Teknik Destek Ekibi, cihazların haberleşme protokollerini (Ethernet, Modbus, TCP/IP, RS485) yapılandırma ve güncelleme yetkisine sahip olmalıdır.
    •    Çözüm Ekipleri, haberleşme protokollerini geliştirme ve cihazın ağ bağlantılarını optimize etme yetkisine sahiptir. Ayrıca, SMS, DTMF gibi iletişim protokollerini de yönetebilmelidir.

#### 3.2 Bağlantı Portları

    •    Kullanıcılar, cihazların haberleşme portlarını (Ethernet, RS485, USB) yalnızca görüntüleyebilir.
    •    Teknik Destek Ekibi, bu portların çalışma durumlarını kontrol edebilir ve ayarlarını değiştirebilir.
    •    Yönetici ve Çözüm Ekipleri, cihazların port konfigürasyonlarını tamamen değiştirme ve yeni port ekleme yetkisine sahiptir.

### 4. Çevresel Koşullar ve Güç Yönetimi


#### 4.1 Çevresel Koşullar

    •    Teknik Destek Ekibi, cihazların çevre koşullarına (çalışma sıcaklık aralığı, nem, toz dayanıklılığı) ilişkin verileri düzenleyebilir.
    •    Çözüm Ekipleri, cihazların çevre koşullarına uyum sağlaması için yeni çevresel koşullar ve çalışma senaryoları ekleyebilir.

#### 4.2 Güç Yönetimi

    •    Kullanıcılar, cihazların güç tüketim durumunu ve enerji besleme bilgilerini görüntüleyebilir.
    •    Teknik Destek Ekibi, cihazların güç besleme ayarlarını (güç giriş türü, enerji tasarruf modları) düzenleyebilir.
    •    Yönetici, cihazların tüm güç yönetim işlevlerini denetleyebilir ve gerektiğinde yeni güç yönetimi protokolleri uygulayabilir.

### 5. Garanti ve Sertifikalar


#### 5.1 Garanti Yönetimi

    •    Kullanıcılar, cihazların garanti bilgilerini (başlangıç/bitiş tarihleri, garanti veren firma) görüntüleyebilir.
    •    Teknik Destek Ekibi, cihazların garanti süresi uzatmalarını ve garanti kapsamındaki servis kayıtlarını güncelleyebilir.

#### 5.2 Sertifikalar

    •    Teknik Destek Ekibi, cihazların sertifikasyon bilgilerini (IEC standartlarına uygunluk, kalite belgeleri) takip edebilir.
    •    Yönetici, yeni sertifikalar ekleyebilir ve sertifikaların geçerliliğini kontrol edebilir.

### 6. Test ve Yükseltmeler


#### 6.1 Test Yönetimi

    •    Teknik Destek Ekibi, cihazların donanım ve yazılım testlerini yönetebilir ve NTP, SNMP, Test Sinyalleri gibi test sonuçlarını kaydedebilir.
    •    Çözüm Ekipleri, cihazların test sonuçlarını analiz ederek yeni özellikler ekleyebilir ve optimizasyonlar yapabilir.

#### 6.2 Yazılım ve Donanım Yükseltmeleri

    •    Yönetici, cihazların yazılım güncellemelerini yönetir ve yükseltmeleri onaylar.
    •    Çözüm Ekipleri, yeni yazılım sürümleri ve donanım geliştirmeleri uygulayabilir.

---

## E-R DİYAGRAMI

![E-R Diyagramı](https://github.com/user-attachments/assets/55d6d3ec-b512-4b26-9b20-c5f04982f24d)




