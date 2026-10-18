# CV Creator

A free, browser-based CV builder made with React and Vite. Fill in the form on the left, watch your CV take shape on the right, then download it as a PDF or PNG. The layout is plain and clean, so applicant tracking systems (ATS) can read it.

## Features

- **CV language:** Turkish or English; headings and labels switch with it.
- **Personal information:** photo, name, title, e-mail, phone, LinkedIn, GitHub, address, age, military status, driving license and a professional summary.
- **Education:** institution, degree, field, location, dates, GPA and a description.
- **Experience:** company, position, location, technologies, dates, a "current" option and a description.
- **Skills** and **languages** (with levels A1 to C+).
- **Date format:** month and year (`07.2021`) or year only (`2021`), chosen per date.
- **Export:** A4 PDF or PNG.
- **Your data stays with you:** everything is saved in your own browser (`localStorage`), so it survives a page refresh. Nothing is sent to a server.

## Run

Requires [Node.js](https://nodejs.org/) 20.19 or later (22.12 or later on the 22 line).

```bash
git clone https://github.com/saitkaplan/cvcreator.git
cd cvcreator
npm install
npm run dev
```

Then open the address shown in the terminal (usually `http://localhost:5173`).

Other commands:

| Command | What it does |
| --- | --- |
| `npm run build` | Builds the site into `dist/` |
| `npm run preview` | Serves the built site locally |
| `npm run lint` | Checks the code with ESLint |

## Notes

- To start over, clear this site's data in your browser; the form has no reset button yet.
- A very large profile photo may not fit in the browser's storage; the app keeps working, but the data is not saved until the photo is smaller.

## License

[MIT](LICENSE) © 2025 Sait Kaplan. You are free to use, change and share it, including commercially, as long as the copyright notice and the license text are kept.

---

## CV Creator (Türkçe)

React ve Vite ile yapılmış, tarayıcıda çalışan ücretsiz bir CV oluşturucu. Soldaki formu doldurursun, CV'n sağda anında oluşur, sonra PDF ya da PNG olarak indirirsin. Düzeni sade ve temizdir; böylece başvuru takip sistemleri (ATS) tarafından okunabilir.

### Özellikler

- **CV dili:** Türkçe ya da İngilizce; başlıklar ve etiketler buna göre değişir.
- **Kişisel bilgiler:** fotoğraf, ad soyad, unvan, e-posta, telefon, LinkedIn, GitHub, adres, yaş, askerlik durumu, ehliyet ve profesyonel özet.
- **Eğitim:** kurum, derece, alan, konum, tarihler, not ortalaması ve açıklama.
- **İş deneyimi:** şirket, pozisyon, konum, teknolojiler, tarihler, "devam ediyor" seçeneği ve açıklama.
- **Yetenekler** ve **diller** (A1'den C+'ya seviyelerle).
- **Tarih biçimi:** her tarih için ay ve yıl (`07.2021`) ya da yalnızca yıl (`2021`).
- **Dışa aktarma:** A4 PDF ya da PNG.
- **Verilerin sende kalır:** her şey kendi tarayıcında (`localStorage`) saklanır, sayfa yenilense de kaybolmaz. Hiçbir bilgi bir sunucuya gönderilmez.

### Çalıştırma

[Node.js](https://nodejs.org/) 20.19 ya da üzeri gerekir (22 serisinde 22.12 ya da üzeri).

```bash
git clone https://github.com/saitkaplan/cvcreator.git
cd cvcreator
npm install
npm run dev
```

Ardından terminalde gösterilen adresi aç (genellikle `http://localhost:5173`).

Diğer komutlar:

| Komut | Ne yapar |
| --- | --- |
| `npm run build` | Siteyi `dist/` klasörüne derler |
| `npm run preview` | Derlenen siteyi yerelde açar |
| `npm run lint` | Kodu ESLint ile denetler |

### Notlar

- Baştan başlamak için tarayıcında bu sitenin verilerini temizle; formda henüz sıfırlama düğmesi yok.
- Çok büyük bir profil fotoğrafı tarayıcının depolama alanına sığmayabilir; uygulama çalışmaya devam eder ama fotoğraf küçültülene kadar veriler kaydedilmez.

### Lisans

[MIT](LICENSE) © 2025 Sait Kaplan. Ticari kullanım dahil serbestçe kullanabilir, değiştirebilir ve paylaşabilirsin; yeter ki telif bildirimi ve lisans metni korunsun.
