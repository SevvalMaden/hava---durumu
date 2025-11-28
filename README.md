# Hava Durumu Uygulaması 🌤️

Türkiye için özelleştirilmiş, modern ve kullanıcı dostu bir hava durumu uygulaması. OpenWeatherMap API kullanarak güncel hava durumu bilgilerini gösterir.

## 🚀 Özellikler

- **Gerçek Zamanlı Hava Durumu**: Türkiye'deki şehirler için anlık hava durumu bilgisi
- **Detaylı Bilgiler**: Sıcaklık, hissedilen sıcaklık, nem, rüzgar hızı ve basınç
- **Geocoding Desteği**: İl, ilçe ve mahalle bazında konum arama
- **Alternatif Konumlar**: Aynı isimde birden fazla yer varsa seçim yapma imkanı
- **Türkçe Arayüz**: Tamamen Türkçe dil desteği
- **Responsive Tasarım**: Mobil, tablet ve masaüstü uyumlu
- **Modern UI**: Gradient renkler ve şık tasarım

## 📋 Kullanılan Teknolojiler

- HTML5
- CSS3 (Gradient, Flexbox, Grid)
- Vanilla JavaScript (ES6+)
- OpenWeatherMap API
- Fetch API

## 🎨 Proje Yapısı

```
hava---durumu/
│
├── index.html          # Ana HTML dosyası
├── css/
│   └── main.css       # Stil dosyası (tüm CSS kuralları)
└── README.md          # Proje dokümantasyonu
```

## 🔧 Kurulum

1. Projeyi bilgisayarınıza klonlayın:
```bash
git clone https://github.com/SevvalMaden/hava---durumu.git
```

2. Proje klasörüne gidin:
```bash
cd hava---durumu
```

3. `index.html` dosyasını bir web tarayıcısında açın:
   - Dosyaya çift tıklayın veya
   - Sağ tıklayıp "Birlikte Aç" → Tarayıcı seçin

## 💡 Kullanım

1. Şehir adı, ilçe veya mahalle ismini giriş kutusuna yazın
2. "GETİR" butonuna tıklayın veya Enter tuşuna basın
3. Hava durumu bilgilerini görüntüleyin
4. Birden fazla sonuç varsa, alternatif konumlardan birini seçebilirsiniz

### Örnek Aramalar
- İstanbul
- Ankara Çankaya
- İzmir Karşıyaka
- Antalya

## 🌐 API Bilgileri

Proje OpenWeatherMap API kullanmaktadır:
- **Geocoding API**: Konum koordinatlarını bulma
- **Current Weather Data API**: Güncel hava durumu bilgileri

## 📱 Responsive Tasarım

Uygulama farklı ekran boyutları için optimize edilmiştir:
- **Desktop**: 768px ve üzeri
- **Tablet**: 480px - 768px arası
- **Mobile**: 480px ve altı

## 🎯 Özellikler Detayları

### Gösterilen Bilgiler
- 📍 Konum adı ve koordinatlar
- 🌡️ Güncel sıcaklık
- 🤔 Hissedilen sıcaklık
- 💧 Nem oranı
- 💨 Rüzgar hızı
- 🔽 Hava basıncı
- ☁️ Hava durumu açıklaması ve ikonu

### Kullanıcı Deneyimi
- Yükleme göstergeleri
- Hata mesajları
- Enter tuşu ile arama
- Smooth animasyonlar
- Modern gradient renkler

## 🛠️ Geliştirme

### CSS Yapısı
- Temiz ve modüler CSS
- Class bazlı stil yönetimi
- Responsive media queries
- Gradient ve transition efektleri

### JavaScript Özellikleri
- Async/Await kullanımı
- Error handling
- Dynamic HTML rendering
- Event listeners

## 📝 Lisans

Bu proje açık kaynaklıdır ve serbestçe kullanılabilir.

## 👤 Geliştirici

**SevvalMaden**
- GitHub: [@SevvalMaden](https://github.com/SevvalMaden)

## 🤝 Katkıda Bulunma

1. Bu projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun

## 📞 İletişim

Sorularınız veya önerileriniz için GitHub üzerinden iletişime geçebilirsiniz.

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!