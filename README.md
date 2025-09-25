# Praktikum 1 - Dasar HTML
## Langkah - langkah praktikum
### 1. Membuat repository
- Membuat repository baru dengan nama **Lab1Web**
- Repository digunakan untuuk menyimpan file praktikum

<img width="1218" height="908" alt="Cuplikan layar 2025-09-25 200450" src="https://github.com/user-attachments/assets/0ce9981a-46de-4ac9-81da-f33f0af05d4c" />

### 2. Membuat file HTML dasar
- Membuat file `lab1_tag_dasar.html`

### 3. Membuat paragraf
- Menambahkan bebrapa paragraf menggunakan tag `<p>`
- Menggunakan atribut `align` (center, right, left, justify).

<img width="864" height="212" alt="Cuplikan layar 2025-09-25 204128" src="https://github.com/user-attachments/assets/1112ad50-bd03-4921-b402-18d64e4cd186" />

### 4. Menambakan judul
- Menambahkan judul `<h1>` dan `<h2>` untuk subjudul

<img width="656" height="168" alt="image" src="https://github.com/user-attachments/assets/7b6e060c-9be6-43ff-9e0f-eaab8dec5ebe" />

### 5. Memformat teks
- Menggunakan tag `<b>`, `<u>`, `<i>`, `<del>`

<img width="701" height="156" alt="image" src="https://github.com/user-attachments/assets/4599beca-0fa4-4450-aba6-85baa876e8eb" />

### 6. Menyisipkan gambar
- Menggunakan gambar menggunakan tag `<img>` dengan atribut `src`, `width`, `alt`

<img width="1567" height="146" alt="image" src="https://github.com/user-attachments/assets/d81d6af8-ce1f-48c7-bb2d-87f0df2d0206" />

### 7. Menambahkan Hyperlink
- Membuat navigasi link ke halaman lain `(lab1_halaman2.html)`

<img width="685" height="169" alt="image" src="https://github.com/user-attachments/assets/0e464e3a-8b41-494d-ac16-0263382de876" />

### Hasil

<img width="922" height="856" alt="image" src="https://github.com/user-attachments/assets/de7e063f-c7f9-454b-88d0-b80209103c27" />

### 8. Halaman 2
<img width="945" height="406" alt="image" src="https://github.com/user-attachments/assets/6e4b0f55-78a3-4771-a9dd-73acd1ba1a75" />

## Pertanyaan teori
**1. Apa yang terjadi jika ada kesalahan penulisan tag?**
Browser tetap akan berusaha menampilkan halaman, tetapi hasilnya sering kali tidak sesuai dengan yang diharapkan.

**2. Perbedaan `<p>` dan `<br>`**
- `<p>` digunakan untuk membuat sebuah paragraf
- `<br>` berfungsi untuk memindahkan teks ke baris berikutnya tanpa membuat paragraf baru

**3. Perbedaan atribut `title` dan `alt` pada `<img>`?**
- `alt` teks alternatif jika gambar tidak bisa ditampilkan.
- `title` teks yang muncul saat kursor diarahkan ke gambar.

**4. Pengaturan ukuran gambar (`width` dan `height`)?**

Sebaiknya hanya isi salah satu atribut (misalnya `width`).
Kalau keduanya diisi sembarangan, gambar bisa jadi gepeng/terdistorsi.

**5. Fungsi atribut target pada link?**
- `_blank` buka link di tab baru
- `_self` buka di tab yang sama (default)
- `_top` buka di jendela utama (hilangkan frame)
- `_parent` buka di frame induk (kalau ada iframe)
