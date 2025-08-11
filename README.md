# QR Personel Takip Uygulaması (Clomosy)

## 📌 Proje Hakkında

**QR Personel Takip Uygulaması**, işyerindeki personellerin giriş-çıkış zamanlarını ve işlemleri gerçekleştirdiği konumları güvenli ve pratik biçimde kaydeden bir sistemdir. QR kod teknolojisiyle geliştirilen bu uygulama, personelin iş yerine ne zaman girip çıktığını ve işlemin doğru lokasyonda olup olmadığını otomatik olarak doğrular.

### Temel Özellikler
- **Konum Doğrulama:** Sadece işlem anında konum alınır, sürekli takip edilmez. Gizlilik ve güvenlik bir arada.
- **QR Kod ile Giriş/Çıkış:** Her personel, kendine özel QR kod ile mobil cihazdan işlem yapar.
- **Yönetici Paneli:** Giriş-çıkış saatleri, konumlar, kullanıcı bilgileri ve toplam çalışma süresi detaylı tablolar halinde sunulur.
- **Raporlama & Filtreleme:** Kayıt silme, çıktı alma, filtreleme ve raporlama işlemleri pratik şekilde yapılır.

---

## 🎯 Hedefler

- Personel takibini dijitalleştirip hata oranını azaltmak
- Sadece yetkili cihaz ve konumda işlem yapılmasını sağlamak
- Çalışma süresinin doğru ve şeffaf biçimde hesaplanması
- Yöneticilere hızlı ve kullanımı kolay bir denetim paneli sunmak
- İş güvenliğini QR kod ve konum doğrulamasıyla maksimuma çıkarmak
- Raporlama ve çıktıyı kolaylaştırmak

---

## 👥 Kullanıcı Tipleri

### Personel
- Mobil uygulama üzerinden QR kod okutarak giriş-çıkış yapar.
- Her işlemde anlık konum doğrulaması olur.

### Yönetici
- Tüm personel verilerini tablo halinde görüntüler.
- Filtreleme, raporlama, kayıt silme, çıktı alma gibi işlemleri kolayca yapar.

---

## 📱 Ekran Görüntüleri & Uygulama Akışı

### Ana Menü (Kullanıcıyı Karşılayan Alan)
<p align="center">
  <img src="https://github.com/user-attachments/assets/83256366-e3d9-484a-8211-4f665152757d" alt="Ana Menü" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Kayıt Ol
<p align="center">
  <img src="https://github.com/user-attachments/assets/c8cdd296-f813-42ec-b5a0-32ffe7d89ea9" alt="Kayıt Ol" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Giriş Yap
<p align="center">
  <img src="https://github.com/user-attachments/assets/577f68af-e06c-4b2f-8f6a-624b9b255800" alt="Giriş Yap" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Şifre Değiştirme
<p align="center">
  <img src="https://github.com/user-attachments/assets/ea34bc37-ee7b-454f-9758-6c74c77b37b2" alt="Şifre Değiştirme 1" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
  <img src="https://github.com/user-attachments/assets/866328e7-5a7f-4e4f-bbcb-ed1318f47041" alt="Şifre Değiştirme 2" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
  <img src="https://github.com/user-attachments/assets/7c7c9787-1b5d-4575-b045-da3985eb7f29" alt="Şifre Değiştirme 3" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### MQTT Bağlantı Mesajı
<p align="center">
  <img src="https://github.com/user-attachments/assets/056ef6c3-80e5-4e03-b342-30422715d9f2" alt="MQTT Bağlantı Mesajı" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Giriş-Çıkış İşlemleri
<p align="center">
  <img src="https://github.com/user-attachments/assets/e60a5a36-0b6f-42ac-8790-10e4f71fa7e1" alt="Giriş-Çıkış İşlemleri" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Yönetici Girişi
<p align="center">
  <img src="https://github.com/user-attachments/assets/90bd29d2-466e-4aab-8abf-fb5cb12ffb3a" alt="Yönetici Giriş" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Personel Listeleme (Mobil)
<p align="center">
  <img src="https://github.com/user-attachments/assets/5bbaa535-5b4a-4fc9-91e9-89a9e5af499a" alt="Personel Listeleme Mobil" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### JSON Formatında Kullanıcı Listeleme (Mobil)
<p align="center">
  <img src="https://github.com/user-attachments/assets/1831fb63-3b3d-4066-bf4e-1132e9a33a25" alt="JSON Listeleme Mobil" width="250" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

### Personel Listeleme (Masaüstü)
<p align="center">
  <img src="https://github.com/user-attachments/assets/e43f9a0b-08b3-42d1-a248-94c8599a3f54" alt="Personel Listeleme Masaüstü" width="500" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

## 📝 Katkı ve Geliştirme

- Proje ile ilgili öneri, geliştirme ve hata bildirimleri için [Issues](https://github.com/mahmutdmrr0/QR-Personel-Takip-Uygulamasi-Clomosy/issues) kısmını kullanabilirsin.
- Katkı sağlamak isteyenler için PR’lar (pull request) açıktır.

---

## 📧 İletişim

Daha fazla bilgi veya destek için repository sahibi ile iletişime geçebilirsiniz.

---

**Bu sistem sayesinde işyerinizde personel takibi daha güvenli, düzenli ve hızlı!**
