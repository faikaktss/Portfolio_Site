
# 🎨 Bootstrap ve CSS ile Web Tasarımı Uygulaması

Bu depo, Bootstrap 5 ve özel CSS kullanılarak hazırlanmış bir web arayüzü projesini içermektedir. Proje kapsamında modern web tasarımında kullanılan temel bileşenler, responsive yapı, sayfa düzenleme, grid sistemi ve stil katmanları gibi pek çok özellik örneklenmiştir.  
**Amacım**, HTML, CSS ve Bootstrap bilgimi pratikle pekiştirmek ve gerçek dünya arayüzlerine yakın tasarımlar oluşturmaktır.

---

## 🔧 Kullanılan Teknolojiler
- HTML5  
- CSS3 (özelleştirilmiş)  
- [Bootstrap 5.3](https://getbootstrap.com/)  
- Google Fonts / Font Awesome (isteğe bağlı)

---

## 📁 Proje Yapısı

Depodaki dosya ve stiller aşağıdaki yapıyı içermektedir:

### 1. Header ve Navigasyon
- `nav.nav-bg`: Özel arka plan rengiyle tanımlanmış responsive navbar yapısı.
- Bootstrap sınıfları kullanılarak mobil uyumlu hale getirilmiştir.

### 2. Avatar ve Tanıtım Alanı
- `.avatar-bg`, `.img-bg`, `.information`:  
  Sayfanın üst bölümünde yer alan avatar görseli, isim ve kısa tanıtım bilgisi.
- Görsel hizalama ve metin düzenlemeleri custom CSS ile yapılmıştır.

### 3. Portfolio Bölümü
- Responsive `grid` yapısıyla oluşturulmuş 6 görsellik portföy alanı.
- Bootstrap'ın `row` ve `col` yapılarıyla dinamik hale getirilmiştir.

### 4. Hakkımda (About) Alanı
- `.about-container`: Yeşil zemin üzerine 2 farklı paragraf ve çağrı butonu (`FREE DOWNLOAD`).
- `.paragraf`, `.paragraf-2`, `.button-1`: Elemanların hizalanması özel `margin` değerleriyle ayarlanmıştır.

### 5. Ek Bilgiler (Alt Bilgi Alanı)
- `.about-2` (Konum, Sosyal Medya, Bilgilendirme):  
  Üç sütun şeklinde konum, sosyal medya ve lisans bilgileri verilmektedir.
- `.location`, `.around`, `.about-3`: Her başlık ve açıklama kendi içinde düzenlenmiştir.

### 6. Footer
- `.about-4`, `.paragraf-7`:  
  Alt kısımda yer alan sade bir telif (copyright) bilgisi içerir.

---

## 💡 Özelleştirilmiş CSS Sınıfları

Projede Bootstrap dışında kullanılan özel sınıfların bazıları:

| Sınıf Adı | Açıklama |
|-----------|----------|
| `.nav-bg` | Navbar arka plan rengi |
| `.avatar-bg` | Avatar bölümünün arka plan rengi |
| `.img-bg` | Avatar görselinin yüksekliği |
| `.information`, `.paragraf-*` | Metin yerleşimi ve hizalama |
| `.about-container`, `.about-2`, `.about-4` | Hakkımda ve footer bölümleri arka plan düzenlemeleri |
| `.button-1` | Çağrı butonunun konumu |

---

## 📌 Notlar
- Tüm görseller `/resimler/` klasörüne yerleştirilmelidir.
- Proje responsive olarak Bootstrap ızgara sistemi ile yapılandırılmıştır.
- `.css` dosyası `WT-1255.css` adıyla dışarıdan çağrılmaktadır.
- `!important` kullanımı sınırlı ama belirli stil önceliklendirmesi için gereklidir.

---

## 🖥️ Görsel Tasarım Hedefi
- Minimal ve okunabilir bir yapı
- Renk uyumu (yeşil-turkuaz tonları ile koyu zemin kontrastı)
- Mobil uyumlu grid sistemi
- Görsel ağırlıklı tanıtım

---

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.  
Tasarım şablonu: [Start Bootstrap – Freelancer Teması](https://startbootstrap.com/theme/freelancer)
