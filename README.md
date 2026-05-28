# 🤖 YZ Asistani - Capacitor Android

Gökhan'ın yapay zeka asistanı - telefonda çalışan, öğrenebilen, geliştirilebilen uygulama.

## 🚀 GitHub'da APK Otomatik Derleme (Telefondan bile!)

### 1. GitHub Repo Oluştur
- github.com'a git (tarayıcıdan, telefondan da olur)
- "New" → Repo adı: `YZAsistani` → "Create repository"

### 2. Dosyaları Yükle
- "Add file" → "Upload files"
- Bu ZIP'teki tüm dosyaları seç ve yükle
- "Commit changes"

### 3. Otomatik Build Başlasın
- Push ettikten 3-5 dakika sonra Actions sekmesinde build başlar
- Yeşil tik olunca hazır!

### 4. APK'yi İndir
- "Actions" sekmesine git → En üstteki workflow'u tıkla
- Aşağıda "Artifacts" bölümünde `YZAsistani-APK` yazan dosyayı indir
- VEYA "Releases" sekmesinden en son sürümü indir

## 🎨 Uygulamayı Düzenleme

### HTML Dosyasını Değiştir
1. `www/index.html` dosyasını aç
2. Developer panelinden veya doğrudan kodu düzenle
3. Commit et → Otomatik yeni APK derlenir!

### Yeni Kural Ekleme
Developer sekmesindeki "Yeni Kural Ekle" bölümünü kullan, veya `index.html` içindeki `baseKnowledge` objesini düzenle.

## 📱 Özellikler
- ✅ Chat, Hafıza, Developer sekmeleri
- ✅ Öğrenme ve düzenleme
- ✅ JSON export/import
- ✅ Tema değiştirme
- ✅ Offline çalışır
- ✅ Telefon hafızasında kalıcı

## 🔧 Geliştirici Bilgileri
- **Framework:** Capacitor 6
- **Platform:** Android (API 24+)
- **WebView:** Chrome Tabanlı
- **Storage:** LocalStorage + IndexedDB

---
**Hazırlayan:** Gökhan Kaya 🚀
