# Secret Notes - Python Tkinter Enkripsiyon Uygulaması

Bu proje, kullanıcıların kişisel notlarını güvenli bir şekilde saklamasını sağlayan, **Vigenère şifreleme** mantığına dayalı ve **Base64** kodlaması kullanan bir masaüstü uygulamasıdır. Kullanıcılar bir anahtar kelime (master key) belirleyerek notlarını şifreleyebilir ve aynı anahtarla tekrar çözebilirler.

## ✨ Özellikler

- **Metin Şifreleme:** Notlarınızı belirlediğiniz parola ile geri döndürülemez (parolasız) hale getirin.
- **Dosya Kayıt:** Şifrelenmiş notlar otomatik olarak `mysecret.txt` dosyasına kaydedilir.
- **Şifre Çözme:** Şifreli metni ve doğru parolayı girerek orijinal nota ulaşın.
- **Kullanıcı Dostu Arayüz:** Python Tkinter kütüphanesi ile hazırlanmış sade ve etkili UI.

## 🛠️ Kullanılan Teknolojiler

- **Dil:** Python 3.x
- **Arayüz:** Tkinter (Yerleşik kütüphane)
- **Kodlama & Şifreleme:** Base64, ASCII manipülasyonu

## 🚀 Kurulum ve Çalıştırma

Proje dizinine gidin:

```bash
cd repository_adin
```

Uygulamayı çalıştırın:

```bash
python main.py
```

## 📖 Nasıl Kullanılır?

Not Kaydetme: Başlık ve notunuzu girin, bir parola belirleyin ve "Kaydet ve Şifrele" butonuna basın. Notunuz şifrelenmiş olarak mysecret.txt dosyasına eklenecektir.

Şifre Çözme: mysecret.txt içindeki şifreli metni alıp uygulama içindeki metin alanına yapıştırın, ardından şifrelerken kullandığınız parolayı girip "Şifreyi Çöz" butonuna tıklayın.

## 📄 Hazırlayan: Yasin ARSLAN
