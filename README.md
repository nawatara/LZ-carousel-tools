# LZ Carousel Tools

**LZ Carousel Tools** adalah generator carousel berbasis browser untuk membuat konten Instagram 4:5 dari satu draft teks.

Tools ini dibuat untuk workflow developer dan content team yang ingin mengubah brief panjang menjadi carousel siap publish tanpa harus menyusun setiap slide secara manual.

## Cara Kerja

1. Paste seluruh draft carousel ke dalam input.
2. Klik **Generate Carousel**.
3. Sistem membaca marker `SLIDE`, `Headline`, `Visual Utama`, `Subtext`, `Bottom Text`, dan `CTA`.
4. Preview carousel dibuat otomatis dengan design system LZ Tools.
5. Download hasil dalam format PNG atau PDF.

## Fitur

- One-paste workflow untuk seluruh draft carousel.
- Parser otomatis untuk maksimal 5 slide.
- Preview live dengan rasio Instagram `4:5`.
- Output PNG berukuran `1080 x 1350 px`.
- Download semua slide sebagai file PNG terpisah.
- Generate PDF multi-halaman.
- Design system konsisten untuk preview, PNG, dan PDF.
- Auto-save draft terakhir di browser melalui `localStorage`.
- Mendukung navigasi antar-slide.
- Responsive untuk desktop dan mobile.
- Tidak membutuhkan build tool atau backend untuk penggunaan dasar.

## Format Draft

Parser paling akurat jika draft menggunakan struktur berikut:

```text
SLIDE 1 - HOOK
[ SECTION LABEL ]

Visual Utama:
Deskripsi visual atau isi UI slide.

Headline:
Headline utama slide.

Subtext:
Copy pendukung slide.

Bottom Text:
Insight atau footer slide.

CTA:
Call to action jika diperlukan.
```

Marker yang didukung:

- `SLIDE 1` sampai `SLIDE 5`
- `Visual Utama:`
- `Headline:`
- `Small Text:`
- `Subtext:`
- `Bottom Text:`
- `CTA:`

## Menjalankan Secara Lokal

Tidak ada proses instalasi khusus.

```text
1. Clone repository.
2. Buka file index.html di browser.
3. Paste draft carousel.
4. Generate dan download hasilnya.
```

Untuk pengalaman yang lebih stabil, jalankan melalui local server sederhana:

```bash
npx serve .
```

## Struktur File

```text
index.html   # Interface aplikasi
styles.css   # Design system dan responsive layout
script.js    # Parser draft, renderer canvas, PNG, dan PDF generator
```

## Design System

Visual generator mengikuti karakter LZ Tools:

- Near-black charcoal background.
- Charcoal UI cards.
- Pale developer blue sebagai accent.
- Monospace untuk technical content.
- Bold uppercase headline.
- Layout editorial yang mobile-first.
- Rasio output Instagram `4:5`.

## Catatan AI Provider

Versi saat ini menggunakan parser lokal berbasis marker sehingga dapat berjalan tanpa API key dan tanpa backend.

Jika ingin menggunakan ChatGPT atau provider AI lain untuk memahami draft bebas secara semantik, tambahkan backend API sebagai lapisan pemrosesan sebelum hasil dikirim ke renderer. API key tidak boleh ditanam langsung di `script.js` pada aplikasi browser publik.

## Repository

[github.com/nawatara/LZ-carousel-tools](https://github.com/nawatara/LZ-carousel-tools)

## License

Tambahkan lisensi repository sesuai kebutuhan distribusi project.
