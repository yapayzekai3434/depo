# Halat Çekme – Şeffaf Renkli UI Paketi v2

Bu paket, HTML5 tabanlı çocuk eğitim oyunu için hazırlanmış yazısız WebP arayüz varlıklarını içerir. Metinleri görsellere gömmek yerine HTML katmanında ekleyebilirsiniz.

## Klasörler

- `assets/ui/`: ana paneller, çerçeveler ve renkli butonlar
- `assets/ui/icons/`: 256×256 piksel kontrol ikonları
- `assets/ui/status/`: takım, ilerleme ve sonuç rozetleri
- `assets/ui/decor/`: halat ve merkez kurdelesi
- `assets/ui/png/`: bütün şeffaf UI öğelerinin PNG uyumluluk kopyaları
- `assets/ui/preview/`: bütün arayüzü gösteren örnek ekran

## Kullanım

`assets/ui/ui-theme.css` dosyasını sayfaya ekleyin:

```html
<link rel="stylesheet" href="assets/ui/ui-theme.css">
```

Örnek:

```html
<button class="game-button game-button--red">Beyaz</button>
<button class="icon-button" aria-label="Ana sayfa">
  <img src="assets/ui/icons/home.webp" alt="">
</button>
```

## Notlar

- `background.webp` ve örnek ekran dışındaki bütün oyun varlıkları gerçek şeffaf alfa kanalına sahiptir.
- WebP şeffaflığını doğru göstermeyen bir uygulama kullanıyorsanız `assets/ui/png/` altındaki aynı adlı PNG dosyasını kullanabilirsiniz.
- `transparency-check.html` dosyasını tarayıcıda açarak her öğeyi dama desenli zemin üzerinde kontrol edebilirsiniz.
- Buton ve panel görselleri yazısızdır; yazılar HTML/CSS ile eklenmelidir.
- İkonlar eşit 256×256 tuvaldedir.
- Paneller en iyi sonucu, özgün en-boy oranları korunarak verir.
- Tüm dosya adları ve ölçüler `assets/ui/asset-manifest.json` içinde listelenmiştir.
