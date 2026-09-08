# KidsLearn — Prasekolah KSPK & Tahun 1 KSSR

Aplikasi belajar interaktif untuk kanak-kanak Malaysia **umur 3–7 tahun**.
Satu fail HTML sahaja — tiada pemasangan, tiada pelayan, tiada akaun.

**Buka aplikasi:** https://shhrlnf.github.io/kidslearn/

## Kandungan

| Umur | Peringkat | Bilangan bab |
|---|---|---|
| 3 tahun | Taska / PERMATA | 20 bab |
| 4 tahun | Prasekolah 1 (KSPK) | 31 bab |
| 5 tahun | Prasekolah 2 (KSPK) | 36 bab |
| 6 tahun | Pra-Tahun 1 (KSPK) | 37 bab |
| 7 tahun | Tahun 1 (KSSR) | 51 bab |

**10 subjek · 108 bab · 570 slaid · 535 soalan kuiz**

Bahasa Melayu · English · Matematik Awal · Islam & Jawi · Sains & Alam ·
Kreativiti & Seni · Pendidikan Moral · Kesihatan & Keselamatan ·
Malaysia Negaraku · Sosioemosi

Subjek dan bab **ditapis mengikut umur** yang dipilih — anak hanya melihat
bahan yang sesuai untuknya.

## Cara ia berfungsi

Setiap bab ada dua fasa:

1. **Belajar dahulu** — slaid interaktif: surih huruf dengan jari, bilang
   sambil tekan, tarik & lepas (drag and drop), makmal campuran warna,
   papan muzik, bina ayat, cerita baris demi baris.
2. **Kuiz mini** — 5 soalan, 100% tekan sahaja (tiada menaip).

Kemajuan direkod: setiap percubaan disimpan dengan tarikh, masa, skor dan
peningkatan. **Laporan Ibu Bapa** (dilindungi soalan matematik ringkas)
menunjukkan kemajuan silibus, sejarah percubaan dan cadangan ulangkaji.

## Ciri lain

- **Bunyi tanpa fail audio** — kesan bunyi disintesis dengan Web Audio API
  (nada marimba pentatonik + reverb), jadi ia berfungsi luar talian.
- **Suara Saya** — ibu bapa atau guru boleh merakam sebutan sendiri untuk
  setiap frasa. Rakaman disimpan dalam peranti (IndexedDB) dan menggantikan
  suara komputer. Perlu `https://` untuk mikrofon.
- **Sebutan Melayu untuk suara Inggeris** — jika peranti tiada suara Bahasa
  Melayu, perkataan ditulis semula secara fonetik ("tiga" → "teegah").
- **Kanvas mewarna** — 14 warna, 4 saiz berus, 10 cop gambar, undur, templat.

## Pemasangan pada iPad / telefon

Buka URL di Safari atau Chrome → **Share** → **Add to Home Screen**.
Aplikasi akan buka skrin penuh dengan ikonnya sendiri, dan rekod kemajuan
kekal (tidak dibersihkan oleh Safari selepas 7 hari).

## Nota

- Rekod kemajuan dan rakaman suara disimpan **pada peranti itu sahaja**
  (localStorage / IndexedDB). Ia tidak disatukan antara peranti.
- Tiada data dihantar ke mana-mana pelayan. Tiada pengumpulan data, tiada iklan.
- Perlu internet pada kali pertama untuk memuatkan Tailwind CSS, fon Google
  dan canvas-confetti dari CDN.

## Selari kurikulum

Selari **Kurikulum Standard Prasekolah Kebangsaan (KSPK)** untuk umur 4–6,
Kurikulum PERMATA/Taska untuk umur 3, dan **KSSR Tahun 1** untuk umur 7.
Ia bahan latihan tambahan — bukan pengganti sekolah.
