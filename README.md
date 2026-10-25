# Deport Law Turkey

Statik web sitesi. Derleme adımı yok, kurulum yok — dosyalar olduğu gibi yayınlanır.

## Sayfalar

| Dil | Dosya | Adres |
|---|---|---|
| English | `index.html` | `/` |
| Türkçe | `tr/index.html` | `/tr/` |
| Русский | `ru/index.html` | `/ru/` |
| العربية | `ar/index.html` | `/ar/` |
| Oʻzbekcha | `uz/index.html` | `/uz/` |
| Türkmençe | `tk/index.html` | `/tk/` |
| Azərbaycanca | `az/index.html` | `/az/` |
| Кыргызча | `ky/index.html` | `/ky/` |
| Қазақша | `kk/index.html` | `/kk/` |
| Dari | `dari/index.html` | `/dari/` |
| فارسی | `fa/index.html` | `/fa/` |

Her dil ayrı bir sayfadır ve kendi metnini HTML içinde taşır; arama motorları ve yapay zekâ
tarayıcıları JavaScript çalıştırmadan tüm içeriği okuyabilir.

## Klasör yapısı

```
index.html          İngilizce (ana sayfa)
tr/ ru/ ar/ uz/ tk/ az/ ky/ kk/ dari/ fa/
assets/             logo, avukat fotoğrafları, paylaşım görseli
robots.txt          arama motoru ve yapay zekâ tarayıcı izinleri
sitemap.xml         11 sayfa + hreflang
vercel.json         yönlendirmeler, önbellek ve güvenlik başlıkları
404.html            bulunamayan sayfa
```

## Vercel'e yükleme

1. Bu klasörün içindekileri GitHub'da yeni bir repoya yükleyin.
2. vercel.com → **Add New → Project** → repoyu seçin.
3. Framework Preset: **Other**. Build Command ve Output Directory **boş** kalsın.
4. **Deploy**.
5. Proje → **Settings → Domains** → `deportlawturkey.com` ekleyin ve Vercel'in verdiği
   DNS kayıtlarını alan adı sağlayıcınıza girin.

## Yayından sonra

- Google Search Console'a siteyi ekleyin ve `sitemap.xml` adresini gönderin.
- Google Business Profile açın (yerel aramada en etkili adım).

## İçerik güncelleme

Metinler her sayfanın HTML'i içindedir. Bir metni değiştirirken aynı cümleyi
ilgili dilin dosyasında güncelleyin; diğer diller bağımsızdır.
