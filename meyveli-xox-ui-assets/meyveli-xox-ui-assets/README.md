# Meyveli XOX UI Asset Paketi

Bu paketteki tüm WebP görseller yazısızdır. Başlıkları, skorları ve düğme metinlerini HTML katmanında ekleyin.

## Ana kullanım

- `background.webp`: Tam ekran arka plan; `background-size: cover`.
- `hud-panel.webp`: Skor, sıra ve üst bilgi alanı.
- `board-frame.webp`: 10×10 HTML/CSS ızgarasının dış çerçevesi.
- `cell.webp`, `cell-hover.webp`, `cell-winning.webp`: Hücre durumları.
- `marker-apple.webp`, `marker-banana.webp`: Oyun taşları.
- `player-panel-red.webp`, `player-panel-yellow.webp`: Oyuncu kartları.
- `button-*.webp`: Yazı ve ikon HTML ile üstüne bindirilecek boş düğmeler.
- `icons/`: Şeffaf zeminli kontrol ve oyun ikonları.
- `decorations/`: Şeffaf zeminli bulut, yaprak ve parıltı süsleri.
- `decorations-overlay.webp`: Arka planın üstüne bindirilebilen tamamen şeffaf dekor katmanı.
- `PREVIEW.webp`: Paket kökündeki yazısız kullanım önizlemesidir; oyun içinde çağrılacak bir UI asseti değildir.

`background.webp` tam ekran fon olduğu için doğal olarak opaktır. Bunun dışındaki bütün WebP bileşenlerinde, nesnenin dışındaki tuval gerçek alfa şeffaflığı taşır.

## Önerilen CSS

`object-fit: contain` ikon ve işaretlerde; `background-size: 100% 100%` panellerde kullanılabilir. Tahta hücrelerini tek bir görselden kesmek yerine CSS Grid ile 10 sütun halinde oluşturun.
