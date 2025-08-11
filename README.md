# StashToken - Tasarım Klonu

Bu proje, [Ryzome AI](https://ryzome.ai/) sitesinin tasarımından esinlenerek oluşturulmuş StashToken sitesidir.

## 📁 Dosya Yapısı

```
stashtoken_v4/
├── 📄 index.html              # Ana sayfa
├── 📄 README.md               # Bu dosya
└── 📁 assets/                 # Varlıklar
    ├── 📁 css/                # Stil dosyaları
    │   ├── main.css           # Ana CSS dosyası
    │   └── styles.css         # Ek stiller
    ├── 📁 fonts/              # Font dosyaları
    │   ├── MonaSans-Bold.woff2
    │   ├── MonaSans-Light.woff2
    │   ├── MonaSans-Medium.woff2
    │   ├── MonaSans-Regular.woff2
    │   └── MonaSans-SemiBold.woff2
    └── 📁 images/             # Görseller
        ├── cta-background.webp      # CTA arkaplan görseli
        ├── demo-video.webm          # Demo videosu
        ├── favicon.ico              # Site ikonu
        ├── footer-graphic.svg       # Footer grafiği
        ├── hero-background.svg      # Ana sayfa arkaplan
        ├── logo.svg                 # StashToken logosu
        └── product-demo.webp        # Ürün demo görseli
```

## 🎨 Özellikler

- ✅ **Tamamen Statik**: Sadece HTML, CSS ve görseller
- ✅ **Mobil Uyumlu**: Responsive tasarım
- ✅ **Hızlı Yükleme**: Optimize edilmiş dosyalar
- ✅ **Temiz Kod**: Anlaşılır dosya yapısı
- ✅ **Türkçe İçerik**: Metinler Türkçe'ye çevrilmiş

## 🚀 Kullanım

1. **Dosyaları İndirin**
2. **Tarayıcıda Açın**: `index.html` dosyasını çift tıklayın
3. **Web Sunucusunda Çalıştırın** (opsiyonel):
   ```bash
   # Python ile basit sunucu
   python -m http.server 8000
   
   # Node.js ile
   npx serve .
   ```

## 🔧 Özelleştirme

### Renkler
- Ana renk: `#012212` (koyu yeşil)
- Accent renk: `#9AE064` (açık yeşil)
- Gri tonları CSS dosyalarında tanımlı

### Fontlar
- MonaSans font ailesi kullanılıyor
- Farklı ağırlıklar: Light, Regular, Medium, SemiBold, Bold

### Görseller
- SVG formatında vektör grafikler
- WebP formatında optimize edilmiş resimler
- WebM formatında video

## 📱 Bölümler

1. **Hero Section** - Ana başlık ve CTA butonları
2. **Video Section** - Demo videosu
3. **About Section** - StashToken nasıl çalışır
4. **Features Section** - 3 ana özellik
5. **CTA Section** - Call-to-action bölümü
6. **Footer** - Logo ve sosyal medya linkleri

## 🛠️ Geliştirici Notları

- Orijinal Next.js JavaScript kodları kaldırıldı
- Sadece gerekli CSS dosyaları korundu
- Dosya isimleri anlaşılır hale getirildi
- Gereksiz auth sayfaları silindi
- KaTeX fontları kaldırıldı (kullanılmıyordu)

## 📄 Lisans

Bu proje StashToken için tasarım çalışması amaçlıdır. Orijinal tasarım [Ryzome AI](https://ryzome.ai/)'dan esinlenilmiştir.
