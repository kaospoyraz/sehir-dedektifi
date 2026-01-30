# 🔍 Şehir Dedektifi - İstanbul’un Gizli Hikayeleri

**Bomba gibi gündem olacak mobil uygulama konsepti!**

## 🎯 Konsept

Şehir Dedektifi, kullanıcıların şehirdeki gizli hikayeleri, tarihi sırları ve kentsel efsaneleri keşfetmesini sağlayan **gamified AR keşif uygulaması**.

### Neden Viral Olacak?

✅ **Eğitici + Eğlenceli**: Kültür öğreniyorsun ama oyun oynuyormuş gibi  
✅ **Sosyal Paylaşım**: Instagram’da bomba olacak AR fotoğraflar  
✅ **FOMO Etkisi**: “Bunu sen de keşfet” psikolojisi  
✅ **Yerel Bağ**: Her şehir kendi hikayelerini ekleyebilir  
✅ **Gamification**: Rozetler, liderlik tablosu, puan sistemi

## 🚀 Özellikler (MVP)

### ✨ Temel Özellikler

- **İnteraktif Harita**: İstanbul’daki 20 gizli hikaye noktası
- **AR Deneyim**: Kamera ile tarihi canlandırmalar
- **Quiz Sistemi**: Her hikayede bilgi testi
- **Puan & Rozet Sistemi**: 5 farklı rozet kazanma
- **Liderlik Tablosu**: Haftalık en iyi kâşifler
- **Sosyal Paylaşım**: Tek tık ile Instagram/Twitter’a paylaş

### 🎮 Gamification Mekaniği

- **Zorluk Seviyeleri**: Kolay (🟢), Orta (🟡), Zor (🔴)
- **Puan Sistemi**: Her hikaye 15-50 puan arası
- **Rozet Sistemi**:
  - 🎯 İlk Keşif (1 hikaye)
  - ⭐ 5 Hikaye
  - 💎 10 Hikaye
  - 🎓 Bölge Uzmanı (15 hikaye)
  - 👑 Şehir Efsanesi (20 hikaye)

## 📍 İlk 10 Hikaye Noktası

1. **Yerebatan Sarnıcı’nın Medusa Sırrı** (Sultanahmet)
1. **Pera Palas’ın 411 Numaralı Oda** (Beyoğlu)
1. **İstiklal’in Gizli Pasajları** (Beyoğlu)
1. **Galata Kulesi’nin Hapishane Dönemi** (Galata)
1. **Moda İskelesi’nin Aşk Mektupları** (Kadıköy)
1. **Haydarpaşa Garı’nın Hayalet Treni** (Kadıköy)
1. **Çiçek Pasajı’nın Büyük Yangını** (Beyoğlu)
1. **Balat’taki Gizli Havra** (Fatih)
1. **Topkapı Sarayı’nın Gizli Tünelleri** (Sultanahmet)
1. **Kız Kulesi’nin Gerçek Hikayesi** (Üsküdar)

## 💻 Teknoloji Stack

### Frontend

- **Framework**: React Native (iOS + Android tek kod)
- **Harita**: Leaflet.js / Google Maps API
- **AR**: ARCore (Android) + ARKit (iOS)
- **State**: React Context / Redux
- **UI**: Custom design (gradient-heavy, modern)

### Backend

- **Option 1 (Hızlı MVP)**: Firebase
  - Firestore (database)
  - Firebase Auth (kullanıcı yönetimi)
  - Cloud Storage (görseller)
  - Cloud Functions (serverless)
- **Option 2 (Scalable)**:
  - Node.js + Express
  - PostgreSQL + PostGIS (location data)
  - Redis (caching)
  - AWS S3 (medya depolama)

### AI/İçerik

- OpenAI GPT-4 API (hikaye zenginleştirme)
- Text-to-Speech (hikaye anlatımı)
- Moderasyon sistemi (kullanıcı içeriği)

## 📱 Kurulum

### Web Versiyonu (Mevcut Prototip)

```bash
# Dosyaları bir web server'da çalıştır
# Option 1: Python
python3 -m http.server 8000

# Option 2: Node.js
npx http-server

# Tarayıcıda aç:
http://localhost:8000
```

### Mobil Uygulama (Gelecek)

```bash
# React Native kurulumu
npx react-native init SehirDedektifi
cd SehirDedektifi

# Dependencies
npm install @react-navigation/native
npm install react-native-maps
npm install @react-native-community/geolocation
npm install react-native-viro # AR için

# iOS
cd ios && pod install && cd ..
npx react-native run-ios

# Android
npx react-native run-android
```

## 🎯 Roadmap

### Faz 1: MVP (2-3 ay)

- ✅ 20 hikaye noktası (İstanbul)
- ✅ Temel harita + marker sistemi
- ✅ Quiz mekanizması
- ✅ Profil + rozet sistemi
- ✅ Liderlik tablosu
- ⏳ Basit AR (QR kod bazlı)

### Faz 2: Beta (1-2 ay)

- 50+ hikaye noktası
- Gelişmiş AR (3D modeller)
- Kullanıcı kayıtlı hikayeler (moderasyonlu)
- Rota önerileri
- Offline mod
- Push notifications

### Faz 3: Launch (1 ay)

- 100+ hikaye noktası
- Tüm İstanbul semtleri
- Influencer kampanyaları
- PR push
- App Store & Play Store yayını

### Faz 4: Büyüme (Ongoing)

- Yeni şehirler (Ankara, İzmir, Antalya)
- Kullanıcı topluluğu özellikleri
- Premium abonelik modeli
- Belediye/müze partnership’leri
- Uluslararası genişleme

## 💰 Monetizasyon Stratejisi

### Freemium Model

- **Ücretsiz**: İlk 10 hikaye
- **Premium** (₺39.99/ay veya ₺299/yıl):
  - Tüm hikayeler
  - Özel rotalar
  - Reklamsız deneyim
  - Erken erişim (yeni hikayeler)
  - Premium rozetler

### Ek Gelir Kaynakları

- **Şehir Paketleri**: ₺99.99 (tek seferlik)
- **Sponsorluklar**: Belediyeler, turizm ofisleri
- **Branded Content**: Markalar için özel hikayeler
- **In-App Advertising**: Banner + video ads (ücretsiz kullanıcılar)

## 📊 Başarı Metrikleri

### KPI’lar

- **DAU/MAU**: Günlük/Aylık aktif kullanıcı
- **Retention Rate**: 7-gün, 30-gün retention
- **Stories Completed**: Tamamlanan hikaye sayısı
- **Share Rate**: Sosyal medya paylaşım oranı
- **Conversion Rate**: Free → Premium dönüşüm

### Hedefler (İlk 6 Ay)

- 100K+ indirme
- 20K+ aktif kullanıcı
- %15+ Premium conversion
- %40+ 30-gün retention
- 1M+ sosyal medya impression

## 🚀 Launch Stratejisi

### Pre-Launch (1 ay)

- Landing page + email listesi
- Teaser video (TikTok, Instagram Reels)
- Influencer seeding (10 mikro-influencer)
- Beta test programı (100 kullanıcı)

### Launch Week

- Product Hunt lansmanı
- PR push (TimeOut İstanbul, Hürriyet, vs.)
- Instagram/TikTok challenge: #ŞehirDedektifi
- Belediye ortaklıkları duyurusu

### Post-Launch

- Haftalık yeni hikaye ekleme
- Kullanıcı içeriği kampanyaları
- Event’ler (offline keşif gezileri)
- Referral program

## 🎨 Design Prensipleri

- **Modern Gradient**: Mor-mavi gradient (667eea → 764ba2)
- **Card-Based UI**: Her hikaye bir card
- **Minimal İcons**: Emoji + simple icons
- **Dark Mode Ready**: Hikaye modunda dark theme
- **Gesture-Based**: Kaydır, yakınlaştır, tıkla
- **Micro-Interactions**: Button press animations

## 🔐 Privacy & Security

- **Location**: Sadece uygulama kullanımı sırasında
- **KVKK Uyumlu**: Türk kullanıcı verileri koruması
- **GDPR Ready**: Avrupa pazarına hazır
- **Moderasyon**: AI + manuel moderasyon
- **Raporlama**: Uygunsuz içerik bildirimi

## 📞 Sonraki Adımlar

1. **Prototip Test Et**: Bu web versiyonunu test et
1. **Feedback Topla**: İlk 50 kullanıcıdan geribildirim
1. **İçerik Üret**: 10 hikaye daha ekle
1. **Teknik Karar**: Firebase mi, custom backend mi?
1. **Designer Bul**: UI/UX tasarımcısı ile çalış
1. **Developer Ekibi**: React Native developer(lar) kirala
1. **Seed Funding**: Melek yatırımcı veya hibe programları

## 🎯 Hedef Kitle

### Primer

- **Yaş**: 18-35
- **Profil**: Şehir meraklısı, tarih/kültür ilgisi olan
- **Davranış**: Instagram aktif, weekend aktivite arayan
- **Lokasyon**: İstanbul (başlangıç)

### Sekonder

- **Turistler**: İstanbul’u keşfetmek isteyen
- **Eğitimciler**: Okul gezileri için
- **Fotoğrafçılar**: Benzersiz lokasyon arayanlar

## 💡 Uzun Vadeli Vizyon

Şehir Dedektifi, sadece bir uygulama değil - **şehir kültürünü koruma ve paylaşma hareketi**.

- 100+ şehir (global)
- 10K+ hikaye
- 1M+ aktif kullanıcı
- Gezi şirketleri ile entegrasyon
- Eğitim kurumlarında kullanımı
- UNESCO miras alanları partnership

-----

## 📝 Notlar

Bu prototip **proof of concept** amaçlıdır. Gerçek production için:

- Backend API gerekli
- Gerçek AR integration
- App store deployment
- Analytics tracking
- Crash reporting
- A/B testing infrastructure

**Sonuç**: Şehir Dedektifi sadece bir uygulama değil, insanların şehirleriyle yeniden bağ kurmasını sağlayan bir **sosyal deneyim**. Viral potansiyeli çok yüksek!

-----

**Hazırlayan**: poyraz
**Tarih**: 30 Ocak 2026  
**Versiyon**: 1.0 (MVP Prototype)
