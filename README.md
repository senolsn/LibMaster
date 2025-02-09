# LibMaster (Kütüphane Yönetim Sistemi)

Bu proje, kütüphanelerin kitap yönetimini kolaylaştırmak için geliştirilmiş bir uygulamadır. Kullanıcılar kitap ekleyebilir, ödünç alabilir, raporları inceleyebilir ve sistem ayarlarını özelleştirebilir. Ayrıca her tablodaki veriler **Excel formatında içe ve dışa aktarılabilir**.

---

## Proje İçeriği

### 1. Tanım Ekranları
Burada örnek olarak **Kitap Tanım** ekranı gösterilmektedir. Daha fazla bilgi için aşağıdaki **Tanımlar** bölümüne göz atabilirsiniz.
Kitap Tanım ekranında her türlü kitap ekleme, güncelleme ve silme işlemleri gerçekleşmektedir.

#### 📷 Kitap Ekleme Ekranı
![Kitap Ekleme Ekranı](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/KitapTanim.png)

### 2. Ödünç Alma & Verme İşlemleri
Kütüphaneden kitap ödünç alma ve geri verme işlemlerinin yönetildiği ekrandır.

#### 2.1 Ödünç Alma
Kullanıcıların kütüphaneden kitap ödünç alma işlemlerini gerçekleştirdiği yerdir. Kullanıcı, almak istediği kitabı seçer ve sistem bu işlemi kayıt altına alarak kitabın o kullanıcıya ait olduğunu belirtir. Ayrıca, ödünç alma süresi ve teslim tarihi gibi bilgiler de burada belirlenir.

#### 📷 Ödünç Alma Ekranı
![Ödünç Alma Ekranı](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/OduncKitapAl.png)

#### 2.2 Ödünç Verme Ekranı
Kullanıcıların ödünç aldığı kitapları kütüphaneye geri iade ettiği işlemleri yönetir. Kullanıcı, teslim ettiği kitabı seçerek iade işlemini tamamlar. Eğer kitap teslim tarihi geçmişse, sistem gecikme süresini hesaplayarak gerekli uyarıları yapar.

#### 📷 Ödünç Verme Ekranı
![Ödünç Verme Ekranı](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/OduncKitapVer.png)

### 3. Ayarlar
Her bir kütüphanenin kendine göre özelleştireceği **mail gönderme ayarları, kitap teslim tarihi gibi bilgilerin** tutulduğu ekrandır.

#### 📷 Ayarlar Ekranı
![Ayarlar Ekranı](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/Ayarlar.png)

### 4. Rapor Modülü
Kullanıcıların ödünç aldığı veya teslim etmediği kitapları gösteren rapor sayfalarını içerir.

#### 4.1. Kitap Geçmişi
Kullanıcının ödünç aldığı kitapların geçmişini gösteren rapordur.

#### 📷 Kitap Geçmişi Raporu
![Kitap Geçmişi Raporu](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/MevcutUyeKitapGecmisi.png)

#### 4.2. Geciken Kitaplar
Süresi geçmiş ve henüz teslim edilmemiş kitapları gösteren rapordur.

#### 📷 Geciken Kitaplar Raporu
![Geciken Kitaplar Raporu](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/GecikmisKitaplar.png)

### 5. Dashboard
Kütüphaneye ait güncel özet verilerini gösteren ana sayfadır.

#### 📷 Dashboard Ekranı
![Dashboard Ekranı](https://raw.githubusercontent.com/senolsn/LibMaster/refs/heads/main/img/Dashboard.png)

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

Bu doküman, proje hakkında genel bir bilgilendirme sunmaktadır.  

📌 **Dikkat:**  
Projemiz, **Uludağ Üniversitesi İnegöl İşletme Fakültesi** ve **Bursa Uludağ Üniversitesi Türk Devletleri ve Akraba Toplulukları Uygulama ve Araştırma Merkezi (TÜDAM)** tarafından kullanılmaktadır.  
Bu nedenle, proje kaynak kodları gizli tutulmakta ve herkese açık olarak paylaşılmamaktadır.  

📌 **Önceki Sürüm:**  
Bu projenin eski sürümü **Windows Forms** tabanlı olarak geliştirilmiştir.  
Önceki sürüme ulaşmak için aşağıdaki bağlantıyı ziyaret edebilirsiniz:  

🔗 [Windows Forms Sürümü](https://github.com/senolsn/inif)

