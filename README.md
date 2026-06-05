<div align="center">
  <img src="logo.png" width="180" alt="Acamay Matematik Serüveni">
  
  # Acamay Matematik Serüveni
  
  **7-12 yaş çocuklar için eğlenceli matematik ve zeka oyunları**

  [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://KULLANICIN.github.io/acamay-matematik)
  [![PWA](https://img.shields.io/badge/PWA-Ready-blue)](https://web.dev/progressive-web-apps/)
  [![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
</div>

---

## 🎮 Özellikler

### 📐 Matematik Oyunları
| Mod | Açıklama |
|-----|----------|
| 🎯 Klasik | 10 soru, 3 seviye (Kolay/Orta/Zor) |
| 🔍 Eksik Sayı | `? + 5 = 12` — boşluğu bul |
| 📖 Kelime Problemi | Hikâyeli gerçek hayat soruları |
| 🎲 Çoktan Seçmeli | 4 şıktan doğruyu seç |

### 🧠 Zeka Oyunları
| Oyun | Açıklama |
|------|----------|
| 🃏 Hafıza | 16 kartlı eşleştirme, 4 farklı tema |
| 🧩 Kayan Bulmaca | 1-8 sırala, klasik sliding puzzle |
| 🔢 Dizi Tamamla | Fibonacci, kareler, aritmetik diziler |
| 🎨 Örüntü Bul | Emoji örüntüsünün devamını tahmin et |

### ⭐ Ödül Sistemi
- Her doğru cevapta anlık ödül animasyonu (8 farklı mesaj)
- Üst üste doğrularda 🔥 Seri Bonusu
- 10/10 yapınca 🏆 Mükemmel kutlaması + konfeti
- Yanlış cevapta 💪 moral mesajları (5 farklı)
- Skor tablosu ile aile içi yarışma

---

## 🚀 Kurulum

### GitHub Pages ile Yayınlama (Ücretsiz)

```bash
# 1. Repoyu fork'la veya klonla
git clone https://github.com/KULLANICIN/acamay-matematik.git
cd acamay-matematik

# 2. GitHub'a push'la
git add .
git commit -m "İlk yayın 🚀"
git push origin main

# 3. GitHub Settings → Pages → Source: main branch → Save
# URL: https://KULLANICIN.github.io/acamay-matematik
```

### Lokal Çalıştırma

```bash
# Python ile
python3 -m http.server 8080
# → http://localhost:8080

# Node ile
npx serve .
# → http://localhost:3000
```

---

## 📱 Google Play Store'a Çıkış

Bu bir PWA (Progressive Web App). Google Play'e göndermek için:

```bash
# Bubblewrap kur
npm install -g @bubblewrap/cli

# APK/AAB oluştur (GitHub Pages URL'ni kullan)
bubblewrap init --manifest https://KULLANICIN.github.io/acamay-matematik/manifest.json
bubblewrap build
# → app-release-bundle.aab dosyasını Play Console'a yükle
```

**Play Console:** play.google.com/console (25$ tek seferlik)

---

## 📁 Dosya Yapısı

```
acamay-matematik/
├── index.html          # Ana uygulama (tek dosya, ~51KB)
├── manifest.json       # PWA manifesti
├── sw.js               # Service Worker (offline destek)
├── logo.png            # Uygulama logosu
├── icons/              # Tüm ikon boyutları
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── README.md
```

---

## 🛠️ Teknik Detaylar

- **Saf HTML/CSS/JS** — framework yok, dependency yok
- **PWA** — offline çalışır, ana ekrana eklenebilir
- **localStorage** — skor tablosu cihazda saklanır
- **Web Audio API** — ses efektleri
- **CSS animations** — konfeti, ödül pop-up, geçişler
- **Responsive** — telefon ekranına tam sığar, scroll yok

---

## 📄 Lisans

MIT License — özgürce kullanabilir, değiştirebilir, dağıtabilirsin.

---

<div align="center">
  Made with ❤️ by <strong>Acamay</strong>
</div>
