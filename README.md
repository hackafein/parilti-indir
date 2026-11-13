# Parıltı — test sürümleri (APK)

Bu repo **yalnız derlenmiş Android test sürümlerini** (GitHub Releases) barındırır; kaynak kod içermez.

**İndirme sayfası:** https://parilti-api.onrender.com/

| Uygulama | Kalıcı indirme bağlantısı | Sürüm etiketi |
|---|---|---|
| Parıltı — çocuk uygulaması | https://parilti-api.onrender.com/indir/parilti | `parilti-YYYYMMDD-HHMM` |
| Parıltı Hekim — hekim uygulaması | https://parilti-api.onrender.com/indir/hekim | `hekim-YYYYMMDD-HHMM` |

Her sürümde APK'nın yanında bir `.sha256` dosyası bulunur; özet ayrıca sürüm notundadır.

```
Windows:      certutil -hashfile Parilti.apk SHA256
macOS/Linux:  shasum -a 256 Parilti.apk
```

Kurulum: Android 8.0+. Samsung'da "Bilinmeyen uygulamaları yükle" iznini tarayıcıya/Dosyalarım'a verin;
Google Play Protect uyarısında "Diğer ayrıntılar › Yine de yükle". Ayrıntı ve gizlilik metni indirme sayfasında.
