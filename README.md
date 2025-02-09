# LibMaster (Kütüphane Yönetim Sistemi)

Bu proje, kütüphanelerin kitap yönetimini kolaylaştırmak için geliştirilmiş bir uygulamadır. Kullanıcılar kitap ekleyebilir, ödünç alabilir, raporları inceleyebilir ve sistem ayarlarını özelleştirebilir. Ayrıca her tablodaki veriler **Excel formatında içe ve dışa aktarılabilir.

---

## Proje İçeriği

### 1. Kitap Ekleme Ekranı
Kitapların eklendiği, güncellendiği ve yönetildiği ekrandır.

#### 📷 Kitap Ekleme Ekranı
_(Buraya kitap ekleme ekranının resmi eklenmelidir)_

### 2. Ödünç Alma & Verme İşlemleri
Kütüphaneden kitap ödünç alma ve geri verme işlemlerinin yönetildiği ekrandır.

#### 📷 Ödünç Alma & Verme Ekranı
_(Buraya ödünç alma & verme ekranının resmi eklenmelidir)_

### 3. Ayarlar
Her bir kütüphanenin kendine göre özelleştireceği **mail gönderme ayarları, kitap teslim tarihi gibi bilgilerin** tutulduğu ekrandır.

#### 📷 Ayarlar Ekranı
_(Buraya ayarlar ekranının resmi eklenmelidir)_

### 4. Rapor Modülü
Kullanıcıların ödünç aldığı veya teslim etmediği kitapları gösteren rapor sayfalarını içerir.

#### 4.1. Kitap Geçmişi
Kullanıcının ödünç aldığı kitapların geçmişini gösteren rapordur.

#### 📷 Kitap Geçmişi Raporu
_(Buraya kitap geçmişi raporunun resmi eklenmelidir)_

#### 4.2. Geciken Kitaplar
Süresi geçmiş ve henüz teslim edilmemiş kitapları gösteren rapordur.

#### 📷 Geciken Kitaplar Raporu
_(Buraya geciken kitaplar raporunun resmi eklenmelidir)_

### 5. Dashboard
Kütüphaneye ait güncel özet verilerini gösteren ana sayfadır.

#### 📷 Dashboard Ekranı
_(Buraya dashboard ekranının resmi eklenmelidir)_

---

## Tanımlar
Bu bölümde uygulamada kullanılan temel tanımlamalar mevcuttur. Her biri için ayrı bir ekran resmi eklenmeyecektir.
- **Kitap**: Kütüphanede bulunan eserleri ifade eder.
- **Yazar**: Kitapları yazan kişileri temsil eder.
- **Kategori**: Kitapların konu bazlı gruplandırılmasını sağlar.
- **Çevirmen**: Yabancı dilden çevrilen kitaplar için çeviri yapan kişilerdir.
- **Dil**: Kitabın yazıldığı veya çevrildiği dili ifade eder.
- **Ödünç Alma & Verme**: Kullanıcıların kitap alıp geri verme süreçlerini yönetir.
- **Raporlar**: Kullanıcıların aldığı veya teslim etmediği kitapların detaylarını içerir.
- **Ayarlar**: Kütüphane bazlı özelleştirmelerin yapıldığı yerdir.

---

## Kullanılan Teknolojiler
- **Backend**: .NET Core, Entity Framework Core, MSSQL
- **Frontend**: Angular, DevExtreme Componentleri
- **Mimari**: N Katmanlı Mimari
- **API**: REST API

Bu doküman, proje hakkında genel bir bilgilendirme sunmaktadır. Detaylı kurulum ve kullanım bilgileri için ilgili dökümantasyonlara göz atabilirsiniz.
