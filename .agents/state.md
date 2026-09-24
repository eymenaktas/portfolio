# Durum — websitesi (eymen.akts.tr)

Güncelleme: 2026-09-25 | Son araç: claude

## Hedef

Kişisel portfolyo. Tek `index.html`; projeler `PROJECTS` dizisinde. Proje yayına
çıkınca ya da kapanınca bu dizi de güncellenir.

## Yapıldı

- [x] StudyTrack, Ezan Vaktim, Maske Pack, BlankReel kartları; OyunHub 40 oyun (f94a1e3). Canlıda.

- [x] Aktaş Fit kartı, Maske Packs → maskepacks.com, trCore açık kaynak (2026-09-25). Canlıda.

## Sıradaki adım

Gizli depolar açılırsa kartlara `repo:` ekle (maske-pack, ezan-vaktim, studytrack, aktas-fit, blankreel/blankreel).

## Bilinen tuzaklar

- Yayın: `rsync -a index.html assets akts:/var/www/portfolio/` (önce sunucuda
  `index.html.yedek-*` al). Dal `gizlilik-footer-404`, canlı bundan.
- Karo logoları 64'lük viewBox; akts-landing'deki 48'lik glifler 1.4545 ile ölçeklenip
  2 birim kaydırılıyor.
- Önizleme: `akts-landing/.claude/launch.json` içindeki `portfolyo` (4193).
