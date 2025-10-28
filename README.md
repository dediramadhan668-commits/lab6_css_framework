# lab6_css_framework
# Laporan Praktikum – Lab 6 CSS Framework (Bootstrap)
Identitas

# Nama: Dedi Ramadhan
# NIM: 312410171
# Kelas: TI.24.A1
# Mata Kuliah: Pemrograman Web

# Tujuan

Mahasiswa mampu memahami konsep dasar dari web framework.

Mahasiswa mampu memahami struktur dasar layout web menggunakan CSS framework.

Mahasiswa mampu memanfaatkan elemen-elemen yang ada pada CSS framework (Bootstrap).

Langkah Praktikum

Buka Visual Studio Code.

Buat folder baru dengan nama lab6_css_framework.

Buat file baru dengan nama about.html.

Tulis struktur dasar dokumen HTML.

Tambahkan link Bootstrap 5.3.3 melalui CDN.

Bangun layout web menggunakan komponen dari Bootstrap.

Lakukan validasi HTML di validator.w3.org
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - Web Framework</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">My Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link active" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <section class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-5 fw-bold">Tentang Kami</h1>
      <p class="lead text-muted">Halaman ini menjelaskan profil dan tujuan pembuatan website Bootstrap pada praktikum ini.</p>
    </div>
  </section>

  <!-- CONTENT -->
  <div class="container my-5">
    <div class="row">
      <div class="col-md-8">
        <h2>Profil Website</h2>
        <p>Website ini dibuat sebagai bagian dari tugas Praktikum 6 - Web Framework, Program Studi Teknik Informatika Universitas Pelita Bangsa. Tujuannya adalah mempelajari penggunaan framework CSS, khususnya Bootstrap, untuk membuat layout web yang responsif.</p>
        <p>Dengan Bootstrap, pembuatan halaman web menjadi lebih mudah dan cepat karena sudah disediakan banyak komponen seperti navbar, card, grid, dan tombol.</p>
      </div>
      <div class="col-md-4">
        <img src="https://dummyimage.com/350x250/6c757d/fff.png" class="img-fluid rounded" alt="About Image">
      </div>
    </div>
  </div>

  <!-- FEATURETTE -->
  <div class="container my-5">
    <hr class="featurette-divider">
    <div class="row featurette align-items-center">
      <div class="col-md-7">
        <h2 class="featurette-heading fw-normal lh-1">Mengapa Bootstrap?</h2>
        <p class="lead">Bootstrap merupakan framework yang paling populer di dunia karena mudah digunakan dan mendukung desain responsif untuk semua ukuran layar.</p>
      </div>
      <div class="col-md-5">
        <img src="https://dummyimage.com/150x150/9b9b9b/fff.png" class="img-fluid rounded" alt="Featurette">
      </div>
    </div>
  </div>

  <!-- FOOTER -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 - Universitas Pelita Bangsa</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
Penjelasan

Navbar: Menggunakan kelas navbar, navbar-expand-lg, dan bg-primary untuk membuat menu navigasi yang responsif dan berwarna biru.

Hero Section: Menampilkan judul dan deskripsi dengan gaya text-center dan py-5 agar tampak profesional.

Content Section: Menggunakan sistem grid Bootstrap (row dan col-md-8/4) untuk membagi area teks dan gambar.

Featurette: Menjelaskan keunggulan Bootstrap dengan layout dua kolom dan featurette-divider sebagai pembatas.

Footer: Dibuat sederhana menggunakan kelas bg-dark dan text-white agar kontras dengan konten utama.
Hasil Tampilan

📸 Tampilan Navbar dan Hero Section:
<img width="1366" height="587" alt="image" src="https://github.com/user-attachments/assets/6a42ab07-6816-4ce2-a9ef-1766f0712b03" />

📸 Tampilan Featurette dan Footer:
<img width="1366" height="587" alt="image" src="https://github.com/user-attachments/assets/66eb0e97-8d19-47b2-8a46-42c30a200045" />

Kesimpulan

Dari praktikum ini saya belajar:

Cara menggunakan Bootstrap untuk membuat layout web modern dan responsif.

Mengenali struktur komponen seperti Navbar, Grid System, dan Footer.

Bahwa framework CSS seperti Bootstrap sangat membantu mempercepat pembuatan website dengan tampilan yang konsisten dan menarik.
