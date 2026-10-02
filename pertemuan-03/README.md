# Pertemuan-03

## Baseline

- Menggunakan hasil P2 sebagai dasar pengembangan P3.
- Menyalin `index.html` dan `img/foto-profil.png` ke `pertemuan-03/`.

## Implementasi Formulir

- Elemen form yang digunakan: `<form>`, `<label>`, `<input>`, `<textarea>`, `<select>`, `<option>`, dan `<button>`.
- Tipe input yang digunakan: `text`, `email`, `number`, `date`, `radio`, dan `checkbox`.
- Atribut validasi yang digunakan: `required`, `minlength`, `maxlength`, `min`, dan `max`.

## Pengujian GET dan POST

- Hasil pengujian GET: Data form berhasil tampil di URL browser setelah tombol kirim ditekan.
- Contoh URL encoding yang ditemukan: `%40` untuk `@` pada alamat email.
- Hasil pengujian POST: Saat tombol kirim ditekan, hasilnya `405 Not Allowed`.

## CSS Dasar

- Selector elemen: `h2`, `h3`, `p`, `ol`, `label`, `button`.
- Selector class: `.form-group`, `.input-form`.
- Selector ID: `#about`, `#contact`.
- Properti CSS dasar yang digunakan: `background-color`, `color`, `border`, `padding`, `margin`, `font-family`, `font-size`, `font-weight`, dan `border-bottom`.

## Pengujian dan Perbaikan

- Galat yang ditemukan: Pengujian POST menghasilkan error `405 Not Allowed`.
- Penyebab galat: GitHub Pages tidak mendukung proses POST pada halaman HTML statis.
- Perbaikan yang dilakukan: Mengubah metode form menjadi GET.
- Hasil pengujian ulang: Metode GET berhasil dan data form tampil pada URL browser.
