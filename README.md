# Praktikum 2 - HTML Lanjutan

## Identitas Mahasiswa

- NIM: 312510377
- Nama: RAFIF MIZANUROHMAN
- Program Studi: Teknik Informatika
- Mata Kuliah: Pemrograman Web

---

## Deskripsi

Praktikum 2 membahas HTML Lanjutan dengan materi:

1. Tabel
2. Form dan Input
3. Radio Button dan Checkbox
4. Select dan Textarea
5. Validasi Form
6. Semantic HTML
7. Multimedia
8. Mini Project Biodata Mahasiswa

---

## 1. Tabel

Pada latihan pertama dibuat tabel data mahasiswa yang berisi:

- NIM
- Nama
- Program Studi

Pada latihan berikutnya tabel dikembangkan menggunakan:

- `caption`
- `thead`
- `tbody`
- `tfoot`
- `colspan`

---
# Screenshot Hasil Praktikum
![Tabel HTML 1](SS/TABEL_HTML1.png)
![Tabel HTML 2](SS/TABEL_HRML2.png)
![Struktur Tabel 1](SS/STUKTUR_TABEL1.png)
![Struktur Tabel 2](SS/STUKTUR_TABEL2.png)


## 2. Form

Form pendaftaran dibuat menggunakan beberapa jenis input:

- Text
- Email
- Password
- Number
- Date
- Radio Button
- Checkbox
- Select
- Textarea

---
# Screenshot Hasil Praktikum
![Form HTML 1](SS/FORM_HTML.png)
![Form HTML 2](SS/FORM_HTML2.png)
## 3. Validasi Form

Validasi dasar HTML digunakan untuk memastikan data yang dimasukkan sesuai ketentuan.

Atribut yang digunakan:

- `required`
- `minlength`
- `min`
- `max`

---

![Validasi Form 1](SS/VALIDASIFORM1.png)

![Validasi Form 2](SS/VALIDASIFORM2.png)

![Radio Button dan Checkbox 1](SS/RADIOBUTTON&CEKBOX.png)

![Radio Button dan Checkbox 2](SS/RADIOBUTTON&CEKBOX2.png)

![Select dan Textarea 1](SS/SELEK&TEXTAREA.png)


![Select dan Textarea 2](SS/SELEK&TEXTAREA2.png)
## 4. Semantic HTML

Struktur halaman menggunakan elemen semantic:

- `header`
- `nav`
- `main`
- `section`
- `article`
- `aside`
- `footer`

---


![Semantic HTML 1](SS/SEMATIKHTML.png)

![Semantic HTML 2](SS/SEMATIKHTML2.png)

## 5. Multimedia

Halaman HTML menggunakan elemen multimedia:

- Audio
- Video

File multimedia disimpan di dalam folder `media`.

---
![Multimedia](SS/MULTIMEDIA.png)
## 6. Mini Project Biodata

Mini project dibuat pada file `biodata.html`.

Mini project menggabungkan:

- Semantic HTML
- Tabel biodata
- Form biodata
- Validasi dasar
- Multimedia

---

![Mini Project 1](SS/PROJECKMINI.png)


![Mini Project 2](SS/PROJECKMINI2.png)

```text
Lab2Web/
├── index.html
├── biodata.html
├── README.md
└── media/
    ├── audio.mp3
    └── video.mp4

---

# Pertanyaan dan Jawaban

## 1. Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?

**Jawaban:**

`<table>` digunakan untuk membuat tabel dalam HTML.  
`<tr>` digunakan untuk membuat baris pada tabel.  
`<th>` digunakan untuk membuat sel sebagai header atau judul kolom.  
`<td>` digunakan untuk membuat sel yang berisi data.

---

## 2. Apa perbedaan `<th>` dan `<td>`?

**Jawaban:**

`<th>` digunakan sebagai sel header atau judul kolom pada tabel, sedangkan `<td>` digunakan untuk menampilkan data atau isi dari tabel.

---

## 3. Apa fungsi `colspan` pada tabel?

**Jawaban:**

`colspan` digunakan untuk menggabungkan beberapa kolom menjadi satu sel pada tabel. Contohnya, `colspan="3"` berarti satu sel akan menggunakan lebar tiga kolom.

---

## 4. Apa fungsi `<form>` dalam HTML?

**Jawaban:**

`<form>` digunakan untuk membuat formulir yang dapat digunakan untuk menerima atau memasukkan data dari pengguna, seperti nama, email, password, tanggal, dan informasi lainnya.

---

## 5. Apa perbedaan radio button dan checkbox?

**Jawaban:**

Radio button digunakan untuk memilih satu pilihan dari beberapa pilihan yang tersedia dalam satu kelompok. Sedangkan checkbox digunakan untuk memilih satu atau lebih pilihan secara bersamaan.

---

## 6. Mengapa `<label>` sebaiknya terhubung dengan id input melalui atribut `for`?

**Jawaban:**

Atribut `for` pada `<label>` digunakan untuk menghubungkan label dengan elemen input melalui atribut `id`. Dengan begitu, label dapat digunakan untuk memilih atau memfokuskan input yang sesuai dan membuat form lebih mudah digunakan.

---

## 7. Apa perbedaan `<textarea>` dengan input type text?

**Jawaban:**

`<input type="text">` digunakan untuk memasukkan teks dalam satu baris, sedangkan `<textarea>` digunakan untuk memasukkan teks yang lebih panjang dan dapat terdiri dari beberapa baris.

---

## 8. Apa fungsi semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`?

**Jawaban:**

Semantic HTML digunakan untuk memberikan struktur dan makna yang lebih jelas pada halaman web.

- `<header>` digunakan untuk bagian kepala halaman.
- `<nav>` digunakan untuk navigasi.
- `<main>` digunakan untuk konten utama.
- `<section>` digunakan untuk mengelompokkan bagian konten.
- `<article>` digunakan untuk konten yang berdiri sendiri.
- `<aside>` digunakan untuk informasi tambahan.
- `<footer>` digunakan untuk bagian bawah halaman.

---

## 9. Apa fungsi `required`, `min`, `max`, dan `minlength`?

**Jawaban:**

Atribut tersebut digunakan untuk melakukan validasi input pada form.

- `required` membuat input wajib diisi.
- `min` menentukan nilai minimum.
- `max` menentukan nilai maksimum.
- `minlength` menentukan jumlah karakter minimum yang harus dimasukkan.

---

## 10. Apa perbedaan elemen `<audio>` dan `<video>`?

**Jawaban:**

Elemen `<audio>` digunakan untuk menampilkan atau memutar file audio, sedangkan elemen `<video>` digunakan untuk menampilkan atau memutar file video pada halaman web.

---

# Kesimpulan

Pada Praktikum 2 HTML Lanjutan, saya mempelajari penggunaan tabel, form, input, validasi form, semantic HTML, serta multimedia menggunakan elemen audio dan video. Selain itu, saya juga membuat mini project biodata mahasiswa dengan menggabungkan beberapa materi yang telah dipelajari.

