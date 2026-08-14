# Kırmızı Balık 🐠

Tarayıcıda çalışan, tek dosyalık su altı oyunu — Flappy Bird mekaniği, deniz dibinde.
Kurulum yok, bağımlılık yok, internet gerekmiyor. Sadece `index.html`.

**▶️ Oyna: https://dali123123123.github.io/kirmizi-balik/**

## Kontroller

| Tuş | Ne yapar |
|---|---|
| `Boşluk` / `↑` / `W` / fare tıklaması | Kuyruk vur, yüksel |
| `R` | Yeniden başla |
| `M` (veya sağ üstteki hoparlör) | Sesi kapat / aç |

## Özellikler

- **Su fiziği** — havadan farklı: daha düşük yerçekimi (0.38) ve her karede 0.985'lik sürtünme çarpanı, balık süzülerek batar
- **Mercan sütunları** — kenarları tırtıklı, ucunda tomurcuklu mercan başlıkları olan engeller
- **Canlı deniz ortamı** — dalgalanan su yüzeyi, yüzeyden inen ışık huzmeleri, kumdan yükselen baloncuklar, salınan yosunlar
- **Baloncuk efektleri** — her kuyruk vuruşunda arkada baloncuk kalır, çarpışmada baloncuk patlaması olur
- **Ters dönen balık** — ölünce karnı yukarı gelecek şekilde dönerek kuma çöker
- **Artan zorluk** — skor yükseldikçe mercan arası boşluk 184 px'den 138 px'e daralır, hız 2.5'ten 4.3'e çıkar
- **Madalyalar** — 5 / 12 / 25 / 40 skorda mercan, gümüş, altın, inci
- **Sabit 60 Hz fizik adımı** — ekran tazeleme hızı 144 Hz olsa da oyun hep aynı hızda akar
- **Rekor kaydı** — `localStorage` ile tarayıcıda saklanır

Tamamı HTML5 Canvas + saf JavaScript. Hiçbir kütüphane kullanılmıyor.

## Yerelde çalıştırma

`index.html` dosyasını indirip herhangi bir tarayıcıda aç. Hepsi bu.

## Kardeş proje

Havadaki versiyonu: [ucan-kus](https://github.com/DALI123123123/ucan-kus)
