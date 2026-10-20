# Hafıza Oyunu — Beyin Fırtınası

## Konsept
Arapça harflerle kart eşleştirme (memory/matching game). Tek sayfa web uygulaması.

## Mekanik
- Kartlar arka yüzü kapalı başlar
- Oyuncu iki kart çevirir → eşleşirse açık kalır, eşleşmezse kapanır
- Tüm kartlar eşleşince tur biter
- Her turda kartlar rastgele karıştırılır

## Zorluk Seviyeleri
- **Kolay:** 4×3 (12 kart = 6 çift)
- **Orta:** 4×4 (16 kart = 8 çift)
- **Zor:** 6×4 (24 kart = 12 çift)

## Kart İçeriği
Arapça harfler (elif, ba, ta, sa, cim, ha, hı, dal, zel, ra, ze, sin, şin, sad, dad, tı, zı, ayın, gayın, fe, kaf, kef, lam, mim, nun, he, vav, ye)
— 28 harf, en zor seviyede bile yeterli.

## Skor Sistemi
- Hamle sayısı (az = iyi)
- Süre (kısa = iyi)
- Yıldız sistemi: ★★★ mükemmel, ★★ iyi, ★ tamamladın
- localStorage ile seviye bazında en iyi skor

## Tasarım Notları
- Karanlık arka plan, altın/krem tonlu kartlar
- Arapça harfler büyük, okunaklı (Amiri veya Noto Naskh Arabic fontu)
- Kart çevirme animasyonu (CSS 3D transform)
- Minimalist, mobil uyumlu
- İslami geometrik desen — kartların arkası için

## Teknik
- Vanilla HTML/CSS/JS, framework yok
- CSS Grid ile kart düzeni
- CSS transitions ile animasyon
- localStorage API ile skor kayıt
