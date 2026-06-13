# Tetris - Çok Oyunculu

Firebase ile gerçek zamanlı çok oyunculu Tetris oyunu.

## 🚀 GitHub Pages'e Yükleme

1. Bu repoyu GitHub'a pushla
2. Settings > Pages > "main" branch'ini seç
3. Birkaç dakika sonra `https://KULLANICIADI.github.io/REPO-ADI` adresinde oyun yayında olur

## 🔥 Firebase Kurulumu (Multiplayer için)

Multiplayer oynamak için Firebase lazım:

1. [Firebase Console](https://console.firebase.google.com/)'a git
2. "Proje Oluştur" de
3. Proje ayarlarına gir > "Web uygulaması" ekle
4. Aldığın config bilgilerini `index.html` içindeki `firebaseConfig` kısmına yapıştır
5. **Firestore**'u aç > "Veritabanı Oluştur" > "Test modunda başlat" seç

## 🎮 Oynanış

- **Tek Oyunculu**: Hemen başla
- **Çok Oyunculu**: Oda oluştur, kodu arkadaşına ver, ikiniz de "Hazır" deyince oyun başlar

### Kontroller

| Tuş | İşlem |
|-----|-------|
| ← → | Hareket |
| ↑ | Döndür |
| ↓ | Yavaşlat |
| Boşluk | Direkt bırak |
| P | Duraklat |

## 📁 Dosyalar

- `index.html` - Oyun dosyası (GitHub Pages'e bunu yükle)
- `firestore.rules` - Firebase güvenlik kuralları
