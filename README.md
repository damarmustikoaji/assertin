# Assertin — Browser-Based API Testing, Scenario Runner & Performance Testing

**Test with confidence. Ship with proof.**

[assertin.com](https://assertin.com) adalah landing page resmi **Assertin**, platform API testing berbasis browser yang dirancang untuk QA pemula hingga engineer berpengalaman. Kirim request, lihat response, susun skenario otomatis dengan **Scenario Runner**, dan jalankan **performance test** berbasis k6 — semua tanpa instalasi.

🔗 **Live site:** https://assertin.com
🚀 **Coba aplikasi:** https://forge.assertin.com

---

## ✨ Fitur Utama

- **API Testing** — kirim request HTTP (GET, POST, PUT, DELETE, dll) langsung dari browser, lihat response secara real-time.
- **Scenario Runner** — susun flow API otomatis (automation testing): login, ambil token, validasi data, dan lainnya dalam satu skenario yang bisa dijalankan berulang.
- **Performance Testing** — jalankan load test berbasis [k6](https://k6.io) untuk mengukur RPS, latency (p95/p99), dan error rate.
- **Environment & Variables** — kelola environment dan variabel `{{var}}` untuk reuse request antar workspace.
- **History & Collections** — simpan, kelola, dan kelompokkan request ke dalam collection untuk kebutuhan tim.

---

## 📚 Belajar Testing

Repo ini juga berisi artikel edukasi seputar API testing yang bisa diakses publik:

- [Apa itu API Testing?](https://assertin.com/learn/api-testing)
- [Apa itu Performance Testing?](https://assertin.com/learn/performance-testing)
- [Apa itu API Automation Testing?](https://assertin.com/learn/automation-testing)

---

## 🗂️ Struktur Project

Static site (tanpa build step), dideploy ke [Vercel](https://vercel.com):

```
assertin.com/
├── index.html                  # Landing page utama
├── learn/                       # Artikel edukasi (API, Performance, Automation testing)
│   ├── api-testing/
│   ├── performance-testing/
│   └── automation-testing/
├── sitemap.xml                  # Sitemap untuk SEO
├── robots.txt                   # Konfigurasi crawler
├── favicon.ico / favicon-32.png / apple-touch-icon.png
└── forge.png                    # Aset gambar produk
```

Vercel secara otomatis merute `/learn/<slug>/` ke `/learn/<slug>/index.html`.

---

## 🛠️ Tech Stack

- **HTML5 + CSS3** (vanilla, tanpa framework, tanpa build step)
- **Bootstrap Icons** untuk ikonografi
- **JSON-LD Schema** (`Organization`, `SoftwareApplication`, `FAQPage`, `Article`) untuk rich results di search engine
- **Vercel** untuk hosting & deployment

---

## 🔍 SEO

- Sitemap: [`sitemap.xml`](./sitemap.xml)
- Robots: [`robots.txt`](./robots.txt)
- Structured data: FAQ schema & Article schema pada setiap halaman `/learn/*`
- Open Graph & Twitter Card meta tags untuk social sharing

---

## Tentang Assertin

Assertin adalah produk dari ekosistem **Assertin Forge** — toolkit API testing yang menggabungkan kemudahan Postman dengan kemampuan performance testing bawaan via k6, dibuat untuk QA non-teknis, QA pemula, dan developer yang ingin belajar API testing.

**Topics:** `api-testing` `performance-testing` `automation-testing` `scenario-runner` `qa` `sdet` `testing-tool` `browser-based` `assertin`
