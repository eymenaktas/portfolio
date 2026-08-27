# eymen.akts.tr

Kişisel portfolyo sitem.

**Canlı:** [eymen.akts.tr](https://eymen.akts.tr)

## Hakkında

Minecraft ekosisteminde çalışıyorum; yanında makine öğrenmesi ve derin
öğrenmeyle ilgileniyorum.

- **Ecstacy Anticheat** — Media Manager
- **TrPrac** — eski owner
- **wrus.net** — eski developer

Site tek sayfalık statik bir çalışma: koyu/açık tema, marka renkli
teknoloji ikonları ve bölüm bazlı içerik.

## Kaynak kod

Tek `index.html` — CSS ve JS gömülü, build adımı yok. Görseller
`assets/` altında.

```bash
python3 -m http.server 4173     # sonra http://localhost:4173
```

**Yayın:** sunucuda `/var/www/portfolio/`, nginx doğrudan diskten
servis ediyor.

```bash
scp index.html akts:/var/www/portfolio/index.html
```

## İletişim

- E-posta: <eymen@akts.tr>
- GitHub: [@eymenaktas](https://github.com/eymenaktas)
