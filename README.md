# E.ARSLAN PDF Soru-Cevap Asistanı

PDF belgelerinizi yükleyin, belge içeriği üzerinden doğal dil ile sorular sorun ve yapay zekâ destekli yanıtlar alın.

E.ARSLAN PDF Soru-Cevap Asistanı, PDF dokümanları üzerinden soru-cevap işlemleri gerçekleştirmek amacıyla geliştirilmiş yapay zekâ destekli bir uygulamadır.

Uygulama sayesinde uzun PDF belgelerini manuel olarak incelemek yerine belgeyi sisteme yükleyebilir ve doküman içerisindeki bilgiler hakkında doğrudan sorular sorabilirsiniz.

---

## Uygulama Görünümleri

### Masaüstü Görünümü

<div align="center">
  <img src="./Masaüstü-Görünüm.png" alt="E.ARSLAN PDF Soru-Cevap Asistanı - Masaüstü Görünümü" width="900" />
</div>

### Mobil Görünüm

<div align="center">
  <img src="./Mobil-görünüm.png" alt="E.ARSLAN PDF Soru-Cevap Asistanı - Mobil Görünüm" width="360" />
</div>

---

## Özellikler

* PDF belge yükleme
* Yapay zekâ destekli soru-cevap
* Doğal dil ile soru sorabilme
* PDF içeriğinden bilgi sorgulama
* Uzun dokümanlarla çalışma
* Hızlı ve kullanıcı dostu arayüz
* Masaüstü uyumlu tasarım
* Mobil uyumlu responsive tasarım
* Belge içeriğine dayalı yanıt üretme
* PDF içerisindeki bilgileri daha kolay analiz edebilme
* Kullanıcı dostu doküman inceleme deneyimi

---

## Kullanım Amacı

E.ARSLAN PDF Soru-Cevap Asistanı'nın temel amacı, PDF belgelerinde bilgi arama ve belge analiz süreçlerini kolaylaştırmaktır.

Uygulama özellikle aşağıdaki doküman türlerinde kullanılabilir:

* Ders notları
* Eğitim dokümanları
* Teknik dokümanlar
* Kullanım kılavuzları
* Raporlar
* Araştırma dokümanları
* Uzun PDF belgeleri

Kullanıcı PDF dosyasını yükledikten sonra belge içerisindeki bilgiler hakkında doğal bir şekilde soru sorabilir.

Örnek sorular:

```text
Bu dokümanın temel amacı nedir?
```

```text
Dokümanda belirtilen önemli tarihler nelerdir?
```

```text
Bu bölümde hangi konular anlatılıyor?
```

```text
Belgede belirtilen ana maddeleri özetler misin?
```

---

## Kullanılan Teknolojiler

* Python 3.12+
* Streamlit
* PDF işleme teknolojileri
* Yapay zekâ ve LLM tabanlı soru-cevap
* HTML
* CSS
* Batch Script
* Yerel web uygulaması mimarisi

Kullanılan yapay zekâ modeli ve yardımcı Python kütüphaneleri projenin yapılandırmasına bağlı olarak değişebilir.

---

## Kurulum

Kurulum işlemi yalnızca ilk kullanımda bir kez yapılmalıdır.

### 1. setup.bat Dosyasını Çalıştırın

Proje klasöründe bulunan aşağıdaki dosyaya çift tıklayın:

```text
setup.bat
```

Kurulum işlemi otomatik olarak başlayacaktır.

### 2. Kurulumun Tamamlanmasını Bekleyin

Kurulum işlemi bilgisayarınızın performansına ve internet bağlantınızın hızına bağlı olarak yaklaşık 5-10 dakika sürebilir.

Kurulum sırasında gerekli Python paketleri ve uygulama bileşenleri yüklenir.

Önemli: İlk kurulum sırasında internet bağlantısı gereklidir.

### 3. Kurulum Tamamlandıktan Sonra

Kurulum tamamlandıktan sonra uygulamayı kullanmak için setup.bat dosyasını tekrar çalıştırmanız gerekmez.

Uygulamayı doğrudan start.bat üzerinden başlatabilirsiniz.

---

## Uygulamayı Çalıştırma

Uygulamayı her kullanmak istediğinizde aşağıdaki adımları uygulayın.

### 1. start.bat Dosyasını Çalıştırın

Proje klasöründe bulunan aşağıdaki dosyaya çift tıklayın:

```text
start.bat
```

### 2. Tarayıcıyı Açın

Uygulama başlatıldıktan sonra tarayıcınızda aşağıdaki adresi açın:

```text
http://localhost:8501
```

### 3. PDF Dosyanızı Yükleyin

Uygulama arayüzünden analiz etmek istediğiniz PDF dosyasını yükleyin.

### 4. Sorunuzu Sorun

PDF içerisindeki bilgiler hakkında doğal dil kullanarak sorularınızı yazabilirsiniz.

Uygulama, yüklenen PDF içerisindeki bilgilere göre yanıt üretir.

---

## Sistem Gereksinimleri

| Gereksinim      | Değer                            |
| --------------- | -------------------------------- |
| İşletim Sistemi | Windows 10 veya Windows 11       |
| Python          | 3.12 veya üzeri                  |
| RAM             | 8 GB önerilir                    |
| Disk Alanı      | En az 2 GB boş alan              |
| İnternet        | İlk kurulum için gerekli         |
| Tarayıcı        | Güncel Chrome, Edge veya Firefox |

Yapay zekâ modeli ve kullanılan kütüphanelere bağlı olarak RAM ve disk kullanımı değişiklik gösterebilir.

---

## Proje Yapısı

Temel proje yapısı aşağıdaki şekildedir:

```text
E.ARSLAN-PDF-Soru-Cevap-Asistani/
│
├── setup.bat
├── start.bat
│
├── logs/
│   └── app.log
│
├── Masaüstü-Görünüm.png
├── Mobil-görünüm.png
│
└── ...
```

### Önemli Dosyalar

| Dosya veya Klasör    | Açıklama                                    |
| -------------------- | ------------------------------------------- |
| setup.bat            | İlk kurulum işlemini başlatır               |
| start.bat            | Uygulamayı çalıştırır                       |
| logs/app.log         | Uygulama çalışma ve hata kayıtlarını içerir |
| Masaüstü-Görünüm.png | Masaüstü arayüz ekran görüntüsü             |
| Mobil-görünüm.png    | Mobil arayüz ekran görüntüsü                |

---

## Sorun Giderme

Uygulama çalışmıyorsa aşağıdaki kontrolleri gerçekleştirin.

### Log Dosyasını Kontrol Edin

Uygulama tarafından oluşturulan hata ve çalışma kayıtlarını aşağıdaki dosyadan kontrol edin:

```text
logs/app.log
```

### Kurulumu Tekrar Çalıştırın

Gerekli bağımlılıkların eksik olması durumunda aşağıdaki dosyayı tekrar çalıştırabilirsiniz:

```text
setup.bat
```

### Python Sürümünü Kontrol Edin

Komut İstemi'ni açın ve aşağıdaki komutu çalıştırın:

```bash
python --version
```

Python sürümünüzün 3.12 veya üzeri olduğundan emin olun.

### Uygulama Adresini Kontrol Edin

Uygulama çalıştıktan sonra aşağıdaki adresin tarayıcıda açıldığından emin olun:

```text
http://localhost:8501
```

---

## Güvenlik ve Gizlilik

PDF belgeleri kişisel, ticari veya başka hassas bilgiler içerebilir.

Bu nedenle:

* Yalnızca güvenilir PDF dosyaları kullanın.
* Hassas belgeleri kullanmadan önce uygulamanın veri işleme yöntemini kontrol edin.
* API anahtarlarını kaynak koduna doğrudan eklemeyin.
* Gizli yapılandırma bilgilerini güvenli yapılandırma mekanizmalarında saklayın.
* Log dosyalarında PDF içeriği veya hassas kullanıcı bilgilerinin gereksiz şekilde tutulmasını engelleyin.
* Uygulamayı internete açık şekilde yayınlamadan önce erişim kontrolü ve güvenlik yapılandırmalarını değerlendirin.

localhost üzerinde çalışan bir uygulama ile internete açık bir sunucuda çalışan uygulamanın güvenlik gereksinimleri aynı değildir.

---

## Test Senaryoları

Uygulamanın güvenilir şekilde çalıştığını doğrulamak için aşağıdaki senaryolar test edilmelidir.

### PDF İşleme

* Geçerli PDF yükleme
* Boş PDF yükleme
* Bozuk PDF yükleme
* Çok büyük PDF yükleme
* Türkçe karakter içeren PDF yükleme
* Görsel ağırlıklı PDF yükleme

### Soru-Cevap

* PDF içerisindeki mevcut bilgi hakkında soru sorma
* PDF içerisinde bulunmayan bilgi hakkında soru sorma
* Uzun soru gönderme
* Birden fazla soru gönderme
* Türkçe karakter içeren soru gönderme
* PDF yüklemeden soru sorma

### Sistem

* İnternet bağlantısı kesildiğinde davranış
* Eksik Python bağımlılıkları
* start.bat çalıştırma
* setup.bat tekrar çalıştırma
* Log dosyasının oluşturulması
* Uygulamanın yeniden başlatılması

---

## Kullanım Akışı

```text
setup.bat
    |
    v
İlk Kurulum
    |
    v
start.bat
    |
    v
http://localhost:8501
    |
    v
PDF Yükle
    |
    v
PDF İçeriğini İşle
    |
    v
Soru Sor
    |
    v
Yapay Zekâ Yanıtı
```

---

## Sürüm Bilgisi

### Versiyon 1.0.0

İlk sürüm.

### İçerdiği Özellikler

* PDF dosyası yükleme
* PDF içeriği üzerinden soru-cevap
* Yapay zekâ destekli yanıt oluşturma
* Responsive kullanıcı arayüzü
* Masaüstü uyumluluğu
* Mobil uyumluluk
* setup.bat ile otomatik kurulum
* start.bat ile uygulama başlatma
* Loglama altyapısı
* localhost:8501 üzerinden çalışma

---

## Geliştirici

### E.ARSLAN

Yazılım geliştirme, yapay zekâ ve uygulama çözümleri.

---

## Lisans

Copyright © 2026 E.ARSLAN

Tüm hakları saklıdır.

Bu proje, geliştiricinin izni olmadan ticari amaçlarla kopyalanamaz, yeniden dağıtılamaz veya değiştirilerek başka bir ürün olarak sunulamaz.

---

<div align="center">

E.ARSLAN PDF Soru-Cevap Asistanı

PDF belgelerinizle daha hızlı ve pratik çalışın.

</div>
