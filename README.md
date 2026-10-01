# Lab2Web - Praktikum 2:HTML Lanjutan
**Mata Kuliah:** Pemrograman Web
**Nama:** Alfi Iftihal Nurul Afiat
**NIM:** 312510041
**Kelas:** I251D
**Program Studi:** Teknik Informatika, Universitas Pelita Bangsa

## Tujuan
1. Memahami penggunaan tabel pada HTML.
2. Memahami penggunaan form dan berbagai jenis input HTML.
3. Menerapkan semantic HTML untuk menyusun struktur halaman.
4. Menambahkan elemen multimedia pada halaman web.
5. Menerapkan validasi form dasar menggunakan atribut HTML.

## Struktur Folder
```
Lab2Web/
├── index.html      (latihan langkah 1-8)
├── biodata.html    (proyek mini)
├── media/
│   ├── audio.mp3
│   └── video.mp4
└── README.md
```

## Langkah Praktikum
### 1. Membuat Tabel Data Mahasiswa
Membuat tabel dengan `<table>`, `<tr>`, `<th>`, dan `<td>`, berisi minimal tiga data mahasiswa (NIM, Nama, Program Studi).

![Screenshot Langkah 1](screenshots/langkah1.png)

### 2. Tabel dengan thead, tbody, tfoot
Menambahkan `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, dan `colspan` untuk menggabungkan sel pada baris rata-rata.

![Screenshot Langkah 2](screenshots/langkah2.png)

### 3. Form Registrasi Mahasiswa
Membuat form dengan input `text`, `email`, `password`, `date`, serta tombol `submit` dan `reset`. Setiap input dihubungkan dengan `<label for="...">`.

![Screenshot Langkah 3](screenshots/langkah3.png)

### 4. Radio Button dan Checkbox
Radio button (`name="jk"`) untuk jenis kelamin (satu pilihan), checkbox (`name="skill"`) untuk keahlian (boleh lebih dari satu).

![Screenshot Langkah 4](screenshots/langkah4.png)

### 5. Select dan Textarea
Menambahkan `<select>` untuk program studi dan `<textarea>` untuk alamat.

![Screenshot Langkah 5](screenshots/langkah5.png)

### 6. Validasi Form Dasar
Menggunakan atribut `required`, `minlength`, `min`, dan `max`. Saat tombol Kirim ditekan tanpa mengisi data, browser menampilkan pesan validasi.

![Screenshot Langkah 6](screenshots/langkah6.png)

### 7. Halaman Semantic HTML
Menyusun halaman dengan `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`.

![Screenshot Langkah 7](screenshots/langkah7.png)

### 8. Multimedia
Menambahkan `<audio controls>` dan `<video controls>` dengan elemen `<source>`.

![Screenshot Langkah 8](screenshots/langkah8.png)

### 9. Proyek Mini: Biodata Mahasiswa
File `biodata.html` menggabungkan semantic structure, tabel, form dengan validasi, dan satu elemen video.

![Screenshot Proyek Mini](screenshots/proyek-mini.png)

## Jawaban Pertanyaan

**1. Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?**
`<table>` membuat struktur tabel, `<tr>` membuat satu baris, `<th>` membuat sel header (judul kolom/baris), dan `<td>` membuat sel data.

**2. Apa perbedaan `<th>` dan `<td>`?**
`<th>` adalah sel header: teksnya otomatis tebal dan rata tengah, serta bermakna sebagai judul bagi data di bawah/sampingnya (membantu screen reader). `<td>` adalah sel data biasa.

**3. Apa fungsi `colspan` pada tabel?**
`colspan` menggabungkan beberapa kolom menjadi satu sel. Contoh `colspan="2"` membuat sel melebar selama dua kolom, seperti pada label "Rata-rata".

**4. Apa fungsi `<form>` dalam HTML?**
`<form>` membungkus kumpulan elemen input untuk menerima data dari pengguna, lalu mengirimkannya (submit) ke server atau halaman tujuan.

**5. Apa perbedaan radio button dan checkbox?**
Radio button hanya memungkinkan satu pilihan dari satu grup (grup ditentukan oleh `name` yang sama). Checkbox memungkinkan memilih satu, beberapa, atau tidak sama sekali.

**6. Mengapa `<label>` sebaiknya terhubung dengan `id` input melalui atribut `for`?**
Agar label dan input saling terhubung: mengklik label otomatis memfokuskan input (atau mencentang checkbox/radio), area klik lebih besar, dan lebih mudah diakses oleh pengguna screen reader.

**7. Apa perbedaan `<textarea>` dengan `input type="text"`?**
`<textarea>` untuk teks panjang dan banyak baris (ukuran diatur `rows` dan `cols`), sedangkan `input type="text"` hanya untuk teks satu baris.

**8. Apa fungsi semantic HTML?**
Elemen semantic memberi makna pada struktur halaman: `<header>` kepala halaman/bagian, `<nav>` navigasi, `<main>` konten utama, `<section>` pengelompokan konten, `<article>` konten mandiri, `<aside>` konten pelengkap, `<footer>` kaki halaman/bagian. Manfaatnya: kode lebih mudah dibaca, lebih ramah SEO, dan lebih aksesibel.

**9. Apa fungsi `required`, `min`, `max`, dan `minlength`?**
`required` mewajibkan input diisi; `min` dan `max` membatasi nilai terkecil dan terbesar (untuk angka/tanggal); `minlength` menentukan panjang minimum teks.

**10. Apa perbedaan `<audio>` dan `<video>`?**
`<audio>` untuk memutar suara saja (hanya tampil kontrol pemutar), sedangkan `<video>` untuk memutar gambar bergerak beserta suara dan bisa diatur ukuran tampilannya (`width`/`height`).

## Kesimpulan
Pada praktikum ini saya mempelajari penggunaan tabel, form beserta berbagai jenis input, semantic HTML, multimedia, dan validasi form dasar, lalu menggabungkannya dalam proyek mini biodata mahasiswa.
