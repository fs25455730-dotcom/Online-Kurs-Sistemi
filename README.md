# Online-Kurs-Sistemi

# 🎓 EduPlatform — Online Kurs Platformu

Modern eğitim süreçlerini dijital ortama taşıyan gelişmiş kurs yönetim sistemi.

---

# 📌 Proje Tanıtımı

**EduPlatform**, online kurs yönetimi, öğrenci kayıt işlemleri, eğitmen takibi ve raporlama süreçlerini merkezi bir yapı altında toplamak amacıyla geliştirilmiş masaüstü tabanlı bir eğitim platformudur.

Sistem sayesinde:

* Kurs oluşturma işlemleri kolaylaşır
  
* Öğrenci kayıt süreçleri hızlanır
  
* Eğitmen yönetimi yapılabilir
  
* Kontenjan takibi sağlanır
  
* Eğitim raporları görüntülenebilir

---

# 🚀 Projenin Amacı

Bu platformun temel amacı:

✅ Eğitim süreçlerini dijitalleştirmek

✅ Kurs yönetimini kolaylaştırmak

✅ Öğrenci kayıtlarını merkezi hale getirmek

✅ Eğitmen takibini düzenlemek

✅ Kullanıcı dostu bir eğitim sistemi sunmaktır

---

# 🛠️ Kullanılan Teknolojiler

| Teknoloji          | Açıklama                       |
| ------------------ | ------------------------------ |
| Python             | Ana programlama dili           |
| PyQt5              | Grafik kullanıcı arayüzü       |
| OOP                | Nesne yönelimli programlama    |
| UUID / ID Yapıları | Veri yönetimi ve kayıt sistemi |

---

# 🧠 Yazılım Mimarisi

Sistem nesne yönelimli programlama prensiplerine göre geliştirilmiştir.

Kod yapısı modüler şekilde hazırlanmış olup 3 temel sınıf üzerine kuruludur.

---

# 👨‍🏫 Egitmen Sınıfı

Kurs veren eğitmenlerin bilgilerini yöneten yapıdır.

## Tutulan Bilgiler

* Eğitmen adı
  
* Uzmanlık alanı
  
* E-posta adresi
  

## Görevleri

* Eğitmen bilgilerini yönetme
  
* Uzmanlık alanlarını görüntüleme
  
* Bilgi güncelleme işlemleri

## Kullanılan Metotlar

```python id="hzjqpw"
get_uzmanlik()
bilgileri_guncelle()
```

---

# 👨‍🎓 Ogrenci Sınıfı

Platforma kayıtlı öğrencileri temsil eder.

Bir öğrenci birden fazla kursa kayıt olabilir.

## Tutulan Bilgiler

* Öğrenci adı
  
* Öğrenci bilgileri
  
* Kayıtlı kurs listesi

## Özellikler

✅ Kurs kaydı oluşturma

✅ Kayıtlı kursları listeleme

✅ Öğrenci bilgilerini yönetme

## Kullanılan Metotlar

```python id="mklfqs"
kurs_ekle()
kurs_listesi()
```

---

# 📚 Kurs Sınıfı

Kurs yönetim işlemlerini gerçekleştiren temel yapıdır.

## Tutulan Bilgiler

* Kurs adı
  
* Eğitmen bilgisi
  
* Başlangıç tarihi
  
* Kontenjan bilgisi
  
* Öğrenci listesi

## Temel Özellikler

✅ Öğrenci kayıt işlemleri

✅ Kontenjan kontrolü

✅ Kurs raporlama

✅ Öğrenci çıkarma işlemleri

## Kullanılan Metotlar

```python id="qazxsw"
ogrenci_kaydet()
ogrenci_cikar()
kurs_raporu()
```

---

# 🖥️ Grafik Kullanıcı Arayüzü (GUI)

Sistem arayüzü **PyQt5** kullanılarak geliştirilmiştir.

Platform toplamda 6 ana navigasyon sekmesinden oluşmaktadır.

---

# 📊 Dashboard

Sistemin genel durumunu görüntüleyen ana paneldir.

Kullanıcı giriş yaptıktan sonra ilk açılan ekrandır.

## Gösterilen Bilgiler

* Toplam kurs sayısı
  
* Toplam öğrenci sayısı
  
* Aktif kurslar
  
* Eğitmen bilgileri
  
* Kurs doluluk oranları

## Özellikleri

✅ KPI kartları

✅ Kurs listeleri

✅ Eğitmen görüntüleme

✅ Doluluk analizleri

---

# ➕ Kurs Ekle Modülü

Yeni kurs oluşturmak için kullanılan ekrandır.

## Girilen Bilgiler

* Kurs adı
  
* Eğitmen seçimi
  
* Başlangıç tarihi
  
* Kontenjan bilgisi

## Sağlanan Avantajlar

* Hızlı kurs oluşturma
  
* Eğitmen atama sistemi
  
* Kontenjan belirleme
  
* Tarih yönetimi

---

# 🧾 Öğrenci Kayıt Yönetimi

Öğrenci kayıt işlemlerinin gerçekleştirildiği modüldür.

## Yapılabilen İşlemler

✅ Öğrenci ekleme

✅ Kurs seçimi

✅ Otomatik kontenjan güncellemesi

✅ Kayıt yönetimi

Kayıt yapılan öğrenciler otomatik olarak ilgili kursun kontenjanına dahil edilir.

---

# 👥 Tüm Öğrenciler Modülü

Platformdaki tüm öğrencilerin listelendiği bölümdür.

## Özellikler

* Öğrenci listeleme
  
* Kayıtlı kursları görüntüleme

* Kurs detaylarını inceleme
  
* Öğrenci bazlı takip sistemi

## Ek Özellik

```text id="xzjduw"
"Kurs Listesi" butonu ile öğrencinin kayıtlı olduğu tüm kurslar görüntülenebilir.
```

---

# 📈 Raporlama Sistemi

Kurs analizlerinin görüntülendiği gelişmiş raporlama modülüdür.

## Sunulan Veriler

* Kurs doluluk oranı
  
* Dinamik progress bar
  
* Öğrenci iletişim bilgileri
  
* Kayıt analizleri

## Sağlanan Avantajlar

✅ Hızlı analiz

✅ Kurs yoğunluk takibi

✅ Öğrenci erişim bilgileri

✅ Görsel raporlama sistemi

---

# 🔐 Admin Paneli

Yönetici işlemlerinin gerçekleştirildiği güvenli alandır.

## Güvenlik

```text id="plmokn"
Varsayılan Yönetici Şifresi: 123
```

## Yönetici Yetkileri

✅ Kurs silme

✅ Öğrenci silme

✅ Sistem loglarını görüntüleme

✅ Kritik işlemleri yönetme

✅ Sistem denetimi yapma

---

# 🔒 Yazılım Güvenliği ve Yaklaşımı

Projede güvenli veri yönetimi için çeşitli yazılım prensipleri uygulanmıştır.

## Kullanılan Yaklaşımlar

* Encapsulation (Kapsülleme)

* Private değişken kullanımı
  
* Modüler yazılım mimarisi
  
* Nesne yönelimli programlama

---

# 🌟 Platform Avantajları

✅ Kullanıcı dostu arayüz

✅ Hızlı kurs yönetimi

✅ Kolay öğrenci kayıt sistemi

✅ Eğitmen takip altyapısı

✅ Kontenjan kontrol sistemi

✅ Gelişmiş raporlama modülü

✅ Güvenli yönetici paneli

---

# 📷 Sistem Özeti

EduPlatform;

🎯 Eğitim süreçlerini dijitalleştirir

🎯 Kurs yönetimini merkezi hale getirir

🎯 Öğrenci kayıtlarını kolaylaştırır

🎯 Eğitmen organizasyonunu düzenler

🎯 Modern bir kullanıcı deneyimi sunar

---

# 🏁 Sonuç

EduPlatform, online eğitim ve kurs yönetim süreçlerini daha verimli hale getirmek amacıyla geliştirilmiş modern bir masaüstü uygulamasıdır.

Nesne yönelimli programlama yaklaşımı sayesinde sistem:

* Düzenli
  
* Güvenli
  
* Ölçeklenebilir
  
* Kullanıcı dostu

bir yapı sunmaktadır.

Bu proje hem yazılım mimarisi hem de eğitim yönetim süreçleri açısından güçlü bir dijital eğitim altyapısı sağlamaktadır.
