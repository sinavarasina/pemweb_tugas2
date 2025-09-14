# Dokumentasi Tugas 2 Pemweb  
Varasina Farmadani - 123140107  
[Github Pages](https://sinavarasina.github.io/pemweb_tugas2/index.html)

## 1. Alasan Struktur Semantik
Dalam pembuatan halaman web ini digunakan elemen **HTML5 semantik** seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, dan heading `<h1>`–`<h6>`.  

Alasan penggunaan struktur semantik:  
- **Keterbacaan kode** → struktur halaman lebih mudah dipahami baik oleh developer maupun orang lain.  
- **Aksesibilitas** → mempermudah screen reader membaca halaman karena elemen built-in semantic.  
- **SEO (Search Engine Optimization)** → mesin pencari lebih mudah mengindeks konten berdasarkan semantic meaning.  
- **Standar web** → sesuai best practice HTML5 modern, bukan hanya menggunakan `<div>`.  

Mengapa web ini dapat disebut sebagai **website dengan struktur semantik**:  
1. Bagian **atas halaman** menggunakan `<header>` untuk menampilkan logo, judul, dan navigasi, bukan hanya `<div>`.  
2. Navigasi utama ditulis dengan `<nav>` dan `<ul><li>` sehingga jelas fungsinya sebagai menu, bukan sekadar list biasa.  
3. Konten utama dibungkus dalam `<main>` yang menjadi identitas utama isi halaman.  
4. Informasi tambahan ditempatkan dalam `<aside>` yang sesuai peruntukannya (konten samping).  
5. Setiap kelompok konten dipisahkan dengan `<section>` yang memiliki judul `<h2>`.  
6. Artikel atau konten berita ditempatkan dalam `<article>` sehingga dapat berdiri sendiri secara semantik.  
7. Bagian bawah halaman menggunakan `<footer>` dengan informasi penulis/tugas.  
8. Struktur heading `<h1>` sampai `<h6>` digunakan secara berurutan sesuai hirarki.  

## 2. Tantangan dan Solusi
- **Tantangan 1:** Menentukan layout dengan header, nav, main, aside, dan footer agar rapi.  
  - **Solusi:** Menggunakan CSS `flexbox` untuk mengatur posisi header (logo, judul, dan navigasi).  

- **Tantangan 2:** Menyusun navigasi antar halaman (index → news).  
  - **Solusi:** Menggunakan path relatif (`news/news-page.html` dan `../index.html`) agar link dapat berjalan sesuai struktur folder.  

- **Tantangan 3:** Memastikan heading terstruktur sesuai hirarki.  
  - **Solusi:** Menggunakan `<h1>` pada judul utama halaman, `<h2>` pada subjudul section, dan seterusnya hingga `<h6>`, sehingga valid secara semantik.  

- **Tantangan 4:** Validasi HTML agar sesuai standar W3C.  
  - **Solusi:** Melakukan pengecekan menggunakan **W3C Validator** dan memperbaiki error seperti atribut yang salah atau struktur tag yang tidak lengkap.  

## 3. Hasil Validasi
Validasi dilakukan melalui [W3C Markup Validation Service](https://validator.w3.org/).  
- **index.html:** ✔ Lolos validasi tanpa error.  
![alt text](https://github.com/sinavarasina/pemweb_tugas2/blob/main/screenshoot/Screenshot_2025-09-14_23-08-42.png)
- **news/news-page.html:** ✔ Lolos validasi tanpa error. 
![alt text](https://github.com/sinavarasina/pemweb_tugas2/blob/main/screenshoot/Screenshot_2025-09-14_23-05-02.png)
