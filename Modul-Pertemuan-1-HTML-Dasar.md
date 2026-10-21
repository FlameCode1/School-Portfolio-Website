# 📘 MODUL PERTEMUAN 1 — HTML Dasar
**Student Club Junior Web Developer · Paket B (SMP)**

> 🎯 **Target pertemuan:** Siswa mampu membuat halaman web sederhana dengan HTML.
> ⏱️ **Durasi:** 90 menit (2 × 45 menit)
> 🧰 **Yang dibutuhkan:** Laptop/PC, browser (Chrome/Edge/Firefox), text editor (Notepad / VS Code)

---

## 1. Cerita Pembuka (5 menit) 🎬

Bayangkan kamu punya **buku catatan digital** yang bisa dilihat seluruh dunia lewat internet. Nah, **HTML** adalah "bahasanya" buku catatan itu.

```
Browser (Chrome)  =  Pembaca buku
HTML              =  Bahasa penulisannya
Website           =  Buku catatan digitalnya
```

Tujuan hari ini: **setiap siswa berhasil membuat 1 halaman biodata sendiri di browser.** 🧑‍💻

---

## 2. Apa itu HTML? (10 menit) 🌐

**HTML** = *HyperText Markup Language*

Bukan bahasa pemrograman! HTML adalah **bahasa (markup)** untuk menyusun struktur halaman web.

Analogi gampangnya:

| HTML | Analogi Sehari-hari |
|------|--------------------|
| Tag `<h1>` | Judul buku |
| Tag `<p>` | Isi paragraf |
| Tag `<img>` | Foto di majalah |
| Tag `<a>` | Tautan/link |

---

## 3. Tools yang Harus Disiapkan (5 menit) 🛠️

1. **Browser**: Chrome / Edge / Firefox (pilih salah satu)
2. **Text Editor**:
   - Pemula: **Notepad** (Windows) / **TextEdit** (Mac)
   - Disarankan: **VS Code** (gratis) → https://code.visualstudio.com

**Cara cek sudah siap:**
- Buka Notepad/VS Code → bisa ngetik ✅
- Buka Chrome → bisa buka google.com ✅

---

## 4. Struktur Dasar HTML (15 menit) 🏗️

Setiap file HTML **wajib** punya struktur seperti ini. Hafalkan pola berikut:

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Judul Halaman</title>
</head>
<body>
    <!-- Konten tampil di sini -->
    Halo Dunia!
</body>
</html>
```

**Penjelasan singkat:**
- `<!DOCTYPE html>` → menyatakan ini dokumen HTML5
- `<html>` → pembungkus seluruh halaman
- `<head>` → info halaman (judul, karakter, dll) — **tidak tampil di browser**
- `<body>` → isi yang **tampil di browser**

---

## 5. Tag-Tag HTML Penting (30 menit) 📚

### A. Judul & Paragraf
```html
<h1>Judul Besar</h1>     <!-- paling besar -->
<h2>Sub Judul</h2>
<h3>Sub Sub Judul</h3>
<h6>Judul Paling Kecil</h6>

<p>Ini paragraf. Bisa ditulis panjang lebar di sini.</p>
```

### B. Teks Tebal & Miring
```html
<p><b>Tebal</b> dan <strong>Penting</strong></p>
<p><i>Miring</i> dan <em>Ditekankan</em></p>
<p>Garis <u>bawah</u> dan <s>coret</s></p>
```

### C. Daftar (List)
```html>
<!-- Daftar tidak berurut (bullet) -->
<ul>
    <li>Apel</li>
    <li>Mangga</li>
    <li>Jeruk</li>
</ul>

<!-- Daftar berurut (angka) -->
<ol>
    <li>Bangun tidur</li>
    <li>Sarapan</li>
    <li>Sekolah</li>
</ol>
```

### D. Tautan (Link)
```html>
<a href="https://www.google.com">Buka Google</a>
<a href="halaman2.html">Halaman 2</a>
```

### E. Gambar
```html
<img src="foto.jpg" alt="Foto Saya" width="200">
```
> ⚠️ `alt` wajib diisi → teks alternatif kalau gambar gagal dimuat (juga untuk aksesibilitas).

### F. Garis Pemisah & Baris Baru
```html
<hr>          <!-- garis horizontal -->
<p>Baris 1<br>Baris 2</p>   <!-- ganti baris -->
```

---

## 6. Praktikum: **Biodata Digital** (20 menit) ✍️

### Langkah 1 — Buat folder kerja
Buat folder baru di Desktop: `SCJWD-Pertemuan1`

### Langkah 2 — Buat file
Di dalam folder itu, buat file baru: `biodata.html`
> 💡 Tips: pastikan ekstensi file benar `.html`, bukan `.html.txt`

### Langkah 3 — Ketik kode berikut (jangan copy-paste dulu, coba ketik supaya ingat!)

**📄 File: `biodata.html`**

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Biodata Saya</title>
</head>
<body>
    <h1>Biodata Saya</h1>
    <hr>

    <h2>👋 Hai, Kenalan Yuk!</h2>
    <p>Halo, nama saya <b>Rama</b>. Saya siswa kelas 9 SMP.</p>

    <h3>📍 Data Diri</h3>
    <ul>
        <li>Nama: Rama Pratama</li>
        <li>Kelas: IX-A</li>
        <li>Hobi: Ngoding & Basket</li>
        <li>Sekolah: SMP Nusantara</li>
    </ul>

    <h3>🎯 Hobi & Minat</h3>
    <ol>
        <li>Bermain bola basket</li>
        <li>Belajar programming</li>
        <li>Membaca komik</li>
    </ol>

    <h3>🔗 Teman Ngoding</h3>
    <p>Cek website belajar di <a href="https://www.w3schools.com">W3Schools</a>.</p>

    <h3>📸 Foto</h3>
    <p>(Nanti di pertemuan 2 kita bikin bingkai fotonya pakai CSS!)</p>

    <hr>
    <p><i>Dibuat dengan ❤️ di Student Club JWD</i></p>
</body>
</html>
```

### Langkah 4 — Buka di Browser
- Klik 2 kali file `biodata.html`, **atau**
- Drag file ke jendela Chrome

🎉 Selamat! Kamu baru saja membuat **halaman web pertama**.

---

## 7. Mini Challenge 🏆 (sisa waktu)

Pilih minimal **2** dari tantangan berikut:

1. Tambahkan **3 hobi lagi** di daftar `<ol>`
2. Tambah **link** ke Google (`https://google.com`) dengan teks "Cari di Google"
3. Buat halaman **`jadwal.html`** berisi jadwal pelajaran minggu ini (pakai `<table>` atau `<ul>`)
4. Coba ubah `<h1>` menjadi `<h2>` dan lihat bedanya di browser
5. Tambahkan **emoji** di setiap heading (misal: 🎓 untuk sekolah, ⚽ untuk hobi)

---

## 8. Rangkuman ✅

| Konsep | Bentuk Kode |
|--------|-------------|
| Judul | `<h1>` s/d `<h6>` |
| Paragraf | `<p>...</p>` |
| List bullet | `<ul><li>...</li></ul>` |
| List angka | `<ol><li>...</li></ol>` |
| Link | `<a href="url">teks</a>` |
| Gambar | `<img src="..." alt="...">` |
| Garis | `<hr>` |
| Enter | `<br>` |

---

## 9. Tugas Rumah 📝

1. **Kirimkan** file `biodata.html` ke chat grup kelas (screenshot + file).
2. Buat halaman **`tentang-saya.html`** yang lebih lengkap, minimal berisi:
   - 1 judul utama
   - 2 sub judul
   - 1 paragraf perkenalan
   - 1 daftar (bullet atau angka)
   - 1 link
3. **Jangan lupa** simpan file di folder yang sama dan rapi.

---

## 10. Preview Pertemuan 2 🚀

> Pertemuan depan kita akan **mewarnai & mempercantik** biodata ini pakai **CSS**, lalu **upload ke GitHub** supaya bisa diakses seluruh dunia! 🌍

---

### ❓ FAQ (Pertanyaan yang Sering Muncul)

**Q: Kenapa file saya berubah jadi .txt?**
A: Pastikan saat "Save As" di Notepad, ubah **Save as type** ke **All Files**, lalu ketik nama lengkap `biodata.html`.

**Q: Tag `<b>` dan `<strong>` bedanya apa?**
A: Secara visual sama (tebal). Tapi `<strong>` punya makna "penting" untuk pembaca layar (aksesibilitas). Untuk pemula, pakai `<strong>` lebih baik.

**Q: Boleh pakai bahasa Inggris semua?**
A: Boleh! Tapi untuk tugas awal, pakai bahasa Indonesia dulu biar lebih mudah dipahami.
