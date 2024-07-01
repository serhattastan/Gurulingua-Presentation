# Gurulingua

Gurulingua, dil öğrenme sürecini eğlenceli, etkili ve erişilebilir kılmak amacıyla tasarlanmış kapsamlı bir dil öğrenme uygulamasıdır. Bu uygulama, interaktif egzersizler, kişiselleştirilmiş öğrenme deneyimleri, kullanıcı profili takibi ve daha fazlasını sunar. Kullanıcılar, favori kelimelerini işaretleyebilir, yaptıkları hataları takip edebilir ve öğrenme süreçlerini özelleştirebilirler.

Gurulingua'nın başlıca özellikleri arasında kullanıcı girişi ve kayıt, etkileşimli oyunlar ve egzersizler, kullanıcı profili kurulumu, ilerleme takibi, sosyal entegrasyon ve daha fazlası bulunmaktadır. Uygulama, kullanıcıların dil öğrenme süreçlerini daha etkili ve keyifli hale getirmek için modern teknolojiler ve kullanıcı dostu bir arayüz ile geliştirilmiştir.

## Özellikler

### Kullanıcı Girişi ve Kayıt
- Firebase Auth ve Google ile giriş seçenekleri ile güvenli kullanıcı girişi.

### Kullanıcı Profili
- Kullanıcılar profil bilgilerini güncelleyebilir ve ilerlemelerini takip edebilir.
- Kullanıcılar favori kelimelerini işaretleyebilir ve hatalarını takip edebilir.
- Kullanıcılar diledikleri zaman profillerini tamamlayabilir veya güncelleyebilir.

### Etkileşimli Egzersizler
- Dil öğrenme sürecini destekleyen çeşitli oyunlar ve egzersizler.
- Doğru eşleştirme yapan kullanıcılar için animasyonlu buton kaybolma özelliği.
- Kullanıcılar doğru cevaplar vererek puan toplayabilir ve ilerlemelerini görebilir.

### Favori Kelimeler ve Hata Takibi
- Kullanıcılar favori kelimelerini işaretleyebilir.
- Kullanıcılar hatalarını takip edebilir ve bu hataları tekrar gözden geçirebilir.

## Kullanılan Teknolojiler

### Dil ve Çerçeveler
- **Kotlin**: Android geliştirme için kullanılan modern ve güçlü bir programlama dili.
- **Firebase Auth**: Kullanıcı kimlik doğrulama ve yönetimi için kullanılır.
- **Google Sign-In**: Kullanıcıların Google hesaplarıyla uygulamaya giriş yapmalarını sağlar.

### Ana Özellikler
- **Kullanıcı Girişi ve Kayıt**: Firebase Auth ve Google Sign-In entegrasyonu.
- **Kullanıcı Profili**: Kullanıcı bilgilerini yönetmek için Firebase Firestore kullanımı.
- **Etkileşimli Egzersizler**: Oyun ve egzersizlerin yönetimi için MVVM mimarisi.
- **Favori Kelimeler ve Hata Takibi**: Room veri tabanı kullanarak kullanıcı verilerini saklama.

### Kod Yapısı
- **MVVM Mimarisi**: View ve ViewModel sınıfları ile yapılandırılmış modüler kod yapısı.
- **Dagger Hilt**: Dependency Injection için kullanılır.
- **Room**: Veritabanı yönetimi için kullanılır.
- **SharedPreferences**: Kullanıcı tercihlerini saklamak için kullanılır.

### Yapı ve Konfigürasyon Dosyaları
- **Gradle Yapı Betikleri**: Proje bağımlılıklarını yönetmek ve yapılandırmak için kullanılır.
- **Firebase Konfigürasyon Dosyası** (`google-services.json`): Firebase projeleri ile entegrasyon için gerekli ayarları içerir.
- **Proguard Kuralları**: Kod gizleme ve optimizasyon için kullanılır.

## Kurulum

### Geliştirme Ortamında Kurulum

1. Bu depoyu klonlayın:
   ```bash
   git clone https://github.com/kullanici_adi/Gurulingua.git
