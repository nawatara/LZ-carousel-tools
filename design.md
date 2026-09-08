# LZ Tools — Developer Carousel Master Design System

## 1. Purpose

Template ini menjadi acuan visual dan content direction untuk seluruh creative team saat membuat carousel **LZ Tools – Telegram Bot APK Builder**.

Tujuan utamanya bukan membuat iklan yang terasa seperti iklan, melainkan membuat konten developer yang terasa **relatable, credible, dan useful**, lalu membawa audience secara natural menuju LZ Tools sebagai solusi.

**Funnel utama:**  
`TOFU → Pain → Reframe → Solution → Proof/CTA`

**Jumlah slide:** maksimum **5 slide**.

---

# 2. Core Positioning

LZ Tools **bukan** diposisikan sebagai pengganti Android Studio atau native Android development.

Posisi yang benar:

> **LZ Tools membantu mempercepat kebutuhan Web → APK ketika web app sudah siap dan kebutuhan tidak memerlukan development native dari nol.**

Core message:

> **Coding-nya sudah selesai. Jangan biarkan packaging-nya yang makan waktu.**

Supporting message:

> **LESS SETUP. MORE SHIPPING.**

Product payoff:

> **WEB → APK kurang dari 5 menit\***  
> \*Waktu build dapat bervariasi tergantung project.

---

# 3. Creative Personality

Konten harus terasa seperti:

- dibuat developer untuk developer;
- teknis tapi mudah dipahami;
- minimal;
- premium;
- dark;
- modern;
- sedikit witty;
- tidak salesy;
- bukan generic SaaS advertising.

Hindari gaya:

- terlalu banyak jargon tanpa konteks;
- bombastis;
- terlalu banyak badge;
- neon cyberpunk berlebihan;
- visual gaming;
- 3D/chibi;
- ilustrasi karakter;
- stock photography;
- headline panjang seperti artikel.

---

# 4. Canvas & Export

## Instagram Feed
- **Aspect ratio:** 4:5
- **Working resolution:** 2160 × 2700 px
- **Minimum delivery:** 1080 × 1350 px
- **Color:** RGB / sRGB
- **Safe area:** minimum 6–8% dari seluruh sisi

Elemen headline, CTA, dan informasi penting tidak boleh keluar safe area.

---

# 5. Color System

## Background
`#080A0B` — Near Black / Deep Charcoal

Boleh menggunakan variasi sangat subtle:
- `#0B0D0F`
- `#101316`

Jangan menggunakan pure-black polos jika membuat desain terasa flat.

## Primary Card
`#25282B`

## Secondary Card
`#303438`

## Main Text
`#F1F1F1`

## Muted Text
`#92989D`

## Developer Blue
`#AFC8F5`

Gunakan untuk:
- highlighted words;
- UI label;
- arrow;
- focus state.

## Success
`#42D985`

Gunakan hanya untuk:
- success;
- done;
- ready;
- checkmark.

## Warning
`#E4B94F`

Gunakan hanya untuk:
- pending;
- warning;
- build status.

## Error
`#FF5B5B`

Gunakan hanya untuk:
- failed;
- error;
- conflict.

### Rule
Accent color harus mempunyai **makna fungsional**, bukan dekorasi.

---

# 6. Typography System

## Headline

Karakter:
- Bold / Extra Bold
- Sans-serif
- UPPERCASE preferred
- maksimal ±5–9 kata
- tight line height
- boleh split menjadi 2–3 baris

Recommended:
- Inter Black
- Manrope ExtraBold
- SF Pro Display Heavy
- Helvetica/Arial equivalent jika font tidak tersedia

Contoh:

> CODING SELESAI.  
> APK-NYA BELUM JADI.

atau:

> CUMA MAU BIKIN  
> APK DARI WEB.

---

## Technical / Code Copy

Gunakan monospace.

Recommended:
- JetBrains Mono
- IBM Plex Mono
- Space Mono

Dipakai untuk:
- JSON;
- terminal;
- filename;
- build log;
- small labels;
- technical caption.

---

## Body Copy

Gunakan:
- Inter
- Manrope
- SF Pro

Body copy maksimal **2–4 baris** jika berada di luar UI card.

---

# 7. Layout Anatomy

Setiap slide idealnya mempunyai struktur:

```text
┌─────────────────────────────────────┐
│ SECTION LABEL                01 / 05│
│                                     │
│ BIG HEADLINE                        │
│ BIG HEADLINE                        │
│                                     │
│ Supporting copy                     │
│                                     │
│      ┌───────────────────────┐      │
│      │                       │      │
│      │ MAIN CODE / UI CARD   │      │
│      │                       │      │
│      └───────────────────────┘      │
│                                     │
│ SMALL INSIGHT                 →     │
└─────────────────────────────────────┘
```

## Top
Left:
`ANDROID DEVELOPER`

atau setelah reveal:
`LZ TOOLS / WEB TO APK`

Right:
`01 / 05`

Gunakan ukuran kecil dan monospace.

---

## Headline Area
Tempatkan di **upper third**.

Headline adalah elemen visual terkuat.

---

## Main UI Area
Sekitar **45–55% tinggi canvas**.

Bentuk UI bisa berupa:

- terminal;
- JSON editor;
- build log;
- client chat;
- checklist;
- Telegram interface;
- APK result card.

---

## Footer
Gunakan 1 short thought.

Contoh:

> PROGRESS DI CODING  
> BUKAN BERARTI SIAP DELIVERY.

Tambahkan minimal directional arrow `→`.

---

# 8. Card Style

Semua card harus:

- charcoal grey;
- rounded;
- tipis;
- terasa seperti aplikasi desktop;
- shadow sangat soft;
- tidak glossy.

Recommended:

```text
Fill        #25282B
Stroke      #3B4248 / low opacity
Radius      24–40 px @ 2160px canvas
Shadow      subtle
```

Card header boleh menggunakan tiga window controls kecil:

`● ● ●`

Tetapi jangan harus muncul di semua slide.

---

# 9. Technical UI Visual Language

## JSON

Contoh:

```json
{
  "project": "ready",
  "ui": "done",
  "backend": "done",
  "api": "done",

  "build_apk": "...",
  "gradle_sync": "pending",
  "sdk_version": "pending",
  "signing": "pending"
}
```

Warna syntax boleh ringan tetapi tidak menyerupai rainbow theme.

---

## Terminal

Contoh:

```bash
$ ./gradlew assembleDebug

✕ Gradle version mismatch
✕ SDK / target compatibility
✕ Dependency conflict
✕ Manifest configuration
✕ Signing / keystore

BUILD FAILED
```

Red hanya digunakan pada failure.

---

## Checklist

Contoh:

```text
Android Studio
Gradle
SDK
Manifest
Keystore
Build
Test
Fix
Rebuild
```

Tujuan checklist adalah menunjukkan **friction**, bukan mengajari keseluruhan Android build pipeline.

---

# 10. 5-Slide Content Framework

## SLIDE 1 — HOOK

**Purpose:** membuat Android developer berhenti scroll.

Headline:

> **CODING SELESAI.  
> APK-NYA BELUM JADI.**

Supporting:

> And that's where the headache starts.

Visual:

```json
{
  "UI": "DONE",
  "BACKEND": "DONE",
  "API": "DONE",
  "DATABASE": "DONE",

  "BUILD APK": "..."
}
```

Product visibility:
**0%**

---

# SLIDE 2 — DEEP PAIN

Headline:

> **1 APK KECIL,  
> KENAPA TOOLCHAIN-NYA PANJANG?**

Supporting:

> Kadang bukan aplikasinya yang kompleks.  
> Proses membungkusnya yang makan waktu.

Main visual:

```text
BUILD FAILED

✕ Gradle version mismatch
✕ SDK / target compatibility
✕ Dependency conflict
✕ Manifest configuration
✕ Signing / keystore
✕ WebView / permission

Build again...
```

Product visibility:
**0%**

---

# SLIDE 3 — REFRAME

Headline:

> **CUMA MAU BIKIN  
> APK DARI WEB.**

Supporting:

> Tapi akhirnya harus buka Android Studio + Gradle + SDK + konfigurasi lainnya.

Left UI:

```text
CLIENT
"Pak, bisa dibikin APK?"

DEV
"Web-nya sudah responsive?"

CLIENT
"Sudah."

DEV
"..."
```

Right UI:

```text
Android Studio
Gradle
SDK
Manifest
Keystore
Build
Test
Fix
Rebuild
```

Core insight:

> **OVERKILL UNTUK KEBUTUHAN YANG SEBENARNYA SEDERHANA.**

Product visibility:
**0%**

---

# SLIDE 4 — SOLUTION REVEAL

Gunakan screenshot atau UI yang berasal dari **real LZ Tools workflow** jika memungkinkan.

Headline:

> **KALAU WEB-NYA SUDAH SIAP,  
> KENAPA HARUS MULAI DARI NOL?**

Supporting:

> Dengan Telegram Bot, proses Web → APK bisa dibuat lebih sederhana.

Flow:

```text
Kirim URL Web
      ↓
Pilih Fitur / Permission
      ↓
Build
      ↓
APK Ready
```

Contoh fitur permission:

```text
✓ Kamera & Mikrofon
✓ Lokasi (GPS)
✓ Bluetooth / Printer
✓ Notifikasi
```

Important:

Jangan membuat klaim bahwa tool menggantikan Android native development.

Product visibility:
**50–70%**

---

# SLIDE 5 — PAYOFF / CTA

Headline:

> **WEB → APK  
> KURANG DARI 5 MENIT\***

Supporting:

> Convert website menjadi Android APK langsung melalui Telegram Bot.

Feature summary:

```text
⚡ Tanpa setup Android Studio
⚙ Kirim URL web
🛡 Pilih fitur yang dibutuhkan
📦 APK siap diunduh
```

Primary CTA:

> **COBA LZ TOOLS SEKARANG →**

Footer:

> LESS SETUP.  
> MORE SHIPPING.

Disclaimer:

> \*Waktu build dapat bervariasi tergantung project.

Product visibility:
**100%**

---

# 11. Copywriting Rules

## Do

Gunakan bahasa seperti:

- “Pernah ngalamin?”
- “Build failed.”
- “Cuma mau…”
- “Kenapa harus…”
- “Kalau web-nya sudah siap…”
- “Less setup.”
- “More shipping.”

Buat kalimat terasa seperti developer berbicara ke developer.

---

## Don't

Hindari:

> “Revolusi aplikasi Android tercanggih!”

> “Tidak perlu Android Studio selamanya!”

> “Bikin aplikasi native tanpa coding!”

> “100% tanpa error!”

> “APK pasti jadi dalam 5 menit!”

Ini menurunkan kredibilitas.

---

# 12. Image Generation Master Prompt

Gunakan struktur ini untuk setiap slide:

```text
Create a premium 4:5 developer carousel poster for LZ Tools.

VISUAL STYLE:
Near-black charcoal background, muted grey floating cards, thin cool blue-grey borders, crisp white and pale-blue typography, monospace technical details, minimalist terminal/code-editor aesthetic, generous negative space, subtle vignette, premium developer-oriented visual language.

SLIDE:
{{SLIDE_NUMBER}} / 05

TOP LABEL:
{{SECTION_LABEL}}

HEADLINE:
{{HEADLINE}}

SUPPORTING COPY:
{{SUPPORTING_COPY}}

MAIN UI:
{{MAIN_UI_TYPE}}

UI CONTENT:
{{UI_CONTENT}}

FOOTER:
{{FOOTER_MESSAGE}}

CTA:
{{CTA}}

RULES:
- 4:5 portrait composition.
- Mobile-first text readability.
- Main headline in upper third.
- Main UI occupies the middle 45–55%.
- Small slide number at top-right.
- Charcoal grey UI cards, not pure black cards.
- Use pale blue for emphasis.
- Use green only for success.
- Use red only for errors.
- Use yellow only for warnings.
- Do not use 3D cartoon characters.
- Do not use stock photography.
- Do not use excessive neon.
- Do not make it look like a generic SaaS advertisement.
- Make it feel like a real developer environment transformed into editorial content.
```

---

# 13. Creative QA Checklist

Sebelum desain dianggap final, cek:

- [ ] Rasio 4:5.
- [ ] Headline terbaca tanpa zoom.
- [ ] Maksimal satu pesan utama per slide.
- [ ] Grey card konsisten.
- [ ] Background konsisten.
- [ ] Slide counter benar.
- [ ] Monospace digunakan untuk technical UI.
- [ ] Accent color tidak berlebihan.
- [ ] LZ Tools tidak muncul terlalu cepat.
- [ ] Slide 1–3 terasa seperti konten, bukan iklan.
- [ ] Slide 4 menunjukkan solusi / real workflow.
- [ ] Slide 5 mempunyai payoff + CTA.
- [ ] Klaim “<5 menit” mempunyai disclaimer.
- [ ] Tidak mengklaim menggantikan native Android development.
- [ ] Tidak ada teks kecil penting di luar safe area.
- [ ] UI tidak terlalu ramai.
- [ ] Tidak ada typo teknis seperti `Gradle`, `SDK`, `Manifest`, `Keystore`, `WebView`, `APK`.

---

# 14. File Naming Convention

Gunakan:

```text
LZTools_Carousel_[CampaignName]_S01_v01.png
LZTools_Carousel_[CampaignName]_S02_v01.png
LZTools_Carousel_[CampaignName]_S03_v01.png
LZTools_Carousel_[CampaignName]_S04_v01.png
LZTools_Carousel_[CampaignName]_S05_v01.png
```

Contoh:

```text
LZTools_Carousel_WebToAPK_S01_v03.png
```

Master source:

```text
LZTools_Carousel_WebToAPK_MASTER.fig
```

atau format source design yang digunakan tim.

---

## Final Principle

> **Jangan mulai dari “Apa fitur LZ Tools?”**  
> Mulai dari **“Apa hal menyebalkan yang developer alami sebelum membutuhkan LZ Tools?”**

Jika slide 1–3 tetap menarik walaupun logo LZ Tools dihapus, berarti konten TOFU-nya bekerja.
