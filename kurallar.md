# Kurallar

Bu dosya projenin tek el kitabıdır. Kalıcı kopya GitHub’dadır: https://github.com/noobcoderturkey/site-rehberi

İş yerindeki bilgisayar aynı remote’u klonlar. Klasör yolu makineden makineye değişebilir. Sabah ilk mesajda bu dosya baştan okunur; yapılan iş bitince Günlük’e yazılır.

## Amaç

Site, şunları kurmak isteyenlere yol gösteren bir tanıtım olacak:

- e-ticaret
- kişisel web sitesi
- küçük ve orta ölçekli işletme sitesi

Yapılmış gerçek işlere atıf verilir. Meta reklamı, piksel ve reklam metni bu el kitabının kapsamında değildir; sayfa yayına girmeden ele alınmaz.

## Yasaklar

- Uydurma müşteri, logo, alıntı veya rakam yazılmaz.
- Mor-mavi gradient, her yerde Inter, iç içe kart, başlığın üstünde yuvarlak ikon kutusu ve sahte aciliyet kullanılmaz.
- Marka alanları dolmadan sayfa üretilmez.

## Mobil

- Tasarım önce 390px genişlikte kurulur.
- Yatay kaydırma olmaz.
- Hedefler başparmakla basılır.
- Form alanları tek sütundur.

## Marka

Sayfa üretilmeden doldurulacaklar. Boş satır, bilinmiyor demektir; tahmin yazılmaz.

- Ad:
- Şehir:
- Telefon:
- WhatsApp:
- Gerçek işler:

## Oturum

1. Sohbetin ilk işi bu dosyayı okumaktır. Okumadan dosya değişmez.
2. İstenen dilim bu kuralların içinde yapılır.
3. İş bitince Günlük’e yeni kayıt üste eklenir. Eski kayıt silinmez.
4. Önemli dilim tek commit ile `main`’e push edilir.

Önemli dilim: kural dosyası, skill kurulumu, `PRODUCT.md`, `DESIGN.md`, sayfa veya görsel sistem. Yazım düzeltmesi ayrı push beklemez; o dilimin commit’ine girer.

Force push yok. Hook atlanmaz. Git config değişmez.

## İş yerinde devam

```powershell
git clone https://github.com/noobcoderturkey/site-rehberi.git
```

Klasörü Cursor’da aç. İlk mesajda bu dosya okunur. Impeccable skill’i repodadır. Motor ikili dosyası her makinede bir kez `~/.impeccable` altına iner; repoya konmaz.

## Günlük

Yeni kayıt bu başlığın hemen altına eklenir.

### 2026-11-23

- Ne bitti: Public repo açıldı. El kitabı, oturum kuralı ve Impeccable (Cursor, proje kapsamı, hook) eklendi. `PRODUCT.md` onaylanan brief’ten yazıldı. Marka alanları ve stack boş. Sayfa yok.
- Sıradaki iş: Marka adı, şehir, telefon, WhatsApp ve gerçek işler dolduktan sonra stack seçilip mobil tanıtım sayfası kurulacak.
- Commit:
